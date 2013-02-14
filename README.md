# Google Logging Documentation

This repository has all of files needed to create the [google logging](https://code.google.com/p/google-glog/) documentation created by Chad Skeeters for NCI Information systems.

The document is written in [reStructuredText](http://docutils.sourceforge.net/rst.html) and uses [rst2pdf](http://rst2pdf.ralsina.com.ar/) to process that markup into PDF.

## Building

rst2pdf -s ptsans,letter,friendly glog.txt

### Installing Dependencies

[Download rst2pdf](https://code.google.com/p/rst2pdf/downloads/list) from google code and run:

    $ python setup.py install

or if on a shared computer:

    $ python setup.py install --home=~

This will install rst2pdf with it's dependencies which include 

 * pdfrw 0.1
 * reportlab 2.6
 * Pygments 1.3.1
 * docutils 0.7
 * distribute 0.6.14

