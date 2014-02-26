# Python Workshop 2014

A workshop I'll be presenting at UAEU on the basics of Python. Not sure when yet. I'll update it as I work on it.

## Usage

I'm using [pandoc](http://johnmacfarlane.net/pandoc/) to convert Markdwon into a PDF. To generate the PDF, you'll need to install it and a TeX distro.

On Debian (or similar):

```bash
sudo apt-get install pandoc texlive lmodern # Installation
pandoc outline.md -s -o outline.pdf -H pre.tex # Generation
```