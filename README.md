# Kogi-Visual-Essay-Project
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-image fit="cover" manifest="(https://upload.wikimedia.org/wikipedia/commons/3/30/Koguis_Tribesman.jpg)">

<param ve-config 
       title="The Kogi People of Colombia"
       author="Lia, Lauren, and Zoe"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/3/30/Koguis_Tribesman.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

# Brief History of the Kogi People
- One of the few tribes from Columbia 
- Moved higher in the mountains to stay in isolation for centuries 
- Because of Spanish conquistadores in the 15th century 
- Descendants of ancient civilization: Tayrona	
- Since colonization, they have lost most of the mid to lower elevation of their ancestral land


## Image

_Kogi Tribesman_ is a photo by Dwayne Reilander, taken on one of the terraces at Ciudad Perdida, Colombia in 2017.[^1]
<param ve-image 
       label="Kogi Tribesman" 
       description="portrait by Dwayne Reilander" 
       license="public domain" 
       url="[https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg](https://upload.wikimedia.org/wikipedia/commons/3/30/Koguis_Tribesman.jpg)">


## Map

The Kogi People are in the Sierra Nevada de Santa Marta mountains in northern Colombia.

<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]:https://joshuaproject.net/people_groups/11402/CO

[^2]:https://www.culturalsurvival.org/publications/cultural-survival-quarterly/kogi-colombia-urgent-call-guardians-heart-world#:~:text=The%20Kogi%20were%20one%20of,for%20centuries%20in%20relative%20isolation.

[^3]:https://www.theguardian.com/sustainable-business/colombia-kogi-environment-destruction  
