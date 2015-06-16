XIPr: XInclude Processor
========================

XIPr is an implementation of [XML Inclusions (XInclude) 1.0](http://www.w3.org/TR/xinclude/) in [XSLT 2.0](http://www.w3.org/TR/xslt20/). XIPr exists because an include feature had to be provided in an XSLT-based project, and rather than implementing a custom include feature, it was decided to use XInclude. It turned out that there was no available implementation of XInclude in XSLT, so we decided to create one. XIPr is a fully conforming XInclude implementation, but it is only [minimally conformant](http://www.w3.org/TR/xinclude/#application), which means that it only supports the [XML Pointer Language (XPointer)](http://www.w3.org/TR/xptr-framework/) [element() scheme](http://www.w3.org/TR/xptr-element/).

Currently, only XInclude 1.0 is supported, but with [XML Inclusions (XInclude) 1.1](http://www.w3.org/TR/xinclude-11/) becoming stable, it would be interesting to see what would have to be added to the current implementation to turn it into an 1.1-compliant implementation.
