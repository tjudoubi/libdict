# libdict
The libdict is a python lib to do translations using google translator.

Install
=======

**Note:** python2 support was dropped. The latest release would work on python3 only.

~~~
pip install libdict
~~~

Usage
=====

**The python module**

You can use libdict in two ways, one of them is through the python class GoogleTranslator.

~~~python
    from libdict import *
    x = GoogleTranslator()
    print x.translate('word', 'en', 'pt')
    print x.translate('word is cool', 'en', 'pt')
~~~

**Command line**

The other way is through the script gdict.

~~~    
gdict -s en -t pt word is cool
~~~




