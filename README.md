# Google Logging Documentation

This repository contains [the documentation](https://bitbucket.org/cskeeters/glog/src/tip/glog.pdf) created by Chad Skeeters and edited by Jerry Garcia for NCI Information systems on [google logging library](https://code.google.com/p/google-glog/).

This pdf file was generated from the glog.txt file in this source code repository.  The document is written in [reStructuredText](http://docutils.sourceforge.net/rst.html) and uses [rst2pdf](http://rst2pdf.ralsina.com.ar/) to process that markup into PDF.

## Building

rst2pdf -s ptsans,letter,friendly glog.txt

### Installing Dependencies

[Download rst2pdf](https://code.google.com/p/rst2pdf/downloads/list) from google code and run:

    $ python setup.py install

or if on a shared computer:

    $ python setup.py install --home=~

This will install rst2pdf with its dependencies which include:

 * pdfrw 0.1
 * reportlab 2.6
 * Pygments 1.3.1
 * docutils 0.7
 * distribute 0.6.14

