<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Vampires"
       author="Te Pyke"
       banner="https://upload.wikimedia.org/wikipedia/commons/c/c6/Edvard_Munch_-_Vampire_%281893%29%2C_Munchmuseet.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q1987925"> <!-- Varney the Vampire -->
<param ve-entity eid="Q39473"> <!-- Transylvania -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://api.bl.uk/metadata/iiif/ark:/81055/vdc_0000000421F8/manifest.json"
       ref="7">

# Basic usage

## Image

_Varney the Vampire of The Feast of Blood_ was one of the first appearances of the vampire in British fiction. A serialised gothic horror story, it was first published in weekly installments printed on cheap pamphlets. As author James Malcolm Rymer was paid by the typeset line, the original edition was 667,000 words long.
<param ve-image 
       label="Varney the Vampire" 
       description="by James Malcolm Rymer" 
       license="public domain" 
       url="http://iiif.io/api/presentation/2/context.json">

## Origins

In one of the earliest and, possibly, most famous depictions of a vampire in Western fiction, Bram Stoker's **Dracula** (), the titular Count lives in the historical region of Transylvania, in the northwestern part of Romania.
<param ve-map center="Q39473" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q39473" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

