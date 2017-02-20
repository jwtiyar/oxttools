# oxttools
Tools for creating language support oxt extensions for LibreOffice

## Dependencies
oxttools depends on the lxml python library, which can be tricky to install on Windows.

## Usage
makeoxt is the tool for creating a LibreOffice extension. You will need to choose a language
tag to associate with your writing system. Also, adding new languages only works with
LibreOffice 5.3 or later.

For example:

```
makeoxt -d mywords.txt -l "My Language" -t ctl qax-x-complex qax-x-complex.oxt
```
