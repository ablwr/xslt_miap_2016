# GIMME AN X
## GIMME AN L
### GIMME AN S
### GIMME A T

# X S L T !

## Intro to XSLT

1. How is XSLT different from other programming languages?

XSLT to mediate between these different languages

1. Understanding XPath
1. Oxygen

Download [here](https://www.oxygenxml.com/xml_editor/download_oxygenxml_editor.html) if you don't already have it, register for a free 30-day trial, and confirm code.


## Oxygen

* Setting it up
* How to use it
* Valid or not?

## XPath

Resources:
[XSLT & XPath Cheatsheet](http://scraping.pro/res/xpath-cheat/XSLT-1.pdf)
[XPath/CSS/DOM/Selenium Rosetta Stone](http://scraping.pro/res/xpath-cheat/xpath_css_dom_recipes.pdf)

1. Nodes: Elements, attributes, siblings, ancestors, children, descendents?

/Element
@attribute
parent/..
../child(ren)

1. Notes

.. --  gets you up to the parent element
ancestor::___ -- gets you up as high as it needs to go
// -- finds everything underneath, like text//p finds all p under text, no matter how far down it is. All descendants.
select="following-sibling::_" -- all nodes after that node
gt for greater than and lt for lesser than when testing logic statements. Can't use < or > because that is used in the XML structure.
Three conditional statements: if, choose, for each.

## Examples 

* Example: Roles
* Example 2: [PBCore to DublinCore](https://github.com/ablwr/MIRCDVRXSLT/blob/master/pbcore_to_dc.xsl)
* Example 3: [MediaConch](https://mediaarea.net/MediaConch) output to HTML, to TXT, to XML
* Example 4: MARC to MODS in NYPL Metadata Management System
* Example 5: MODS to NYPL Digital Collections

## Workshoppin'

* scripts/mediainfo [xml](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/mediainfo.xml) [xsl](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/mediainfo_simple.xsl)
* scripts/roles [xml](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/roles.xml) [xsl](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/roles.xsl)
* scripts/movies [xml](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/movies.xml) [xsl](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/movies.xsl)
* scripts/movies (html) [xsl](https://github.com/ablwr/xslt_miap_2016/blob/master/scripts/movies_html.xsl)

## Command line tools
[xsltproc](http://xmlsoft.org/XSLT/xsltproc2.html)
[ffmpeg](https://ffmpeg.org/)
