---
label: 5
title: Related Objects
subtitle: 
weight: 70
type: essay
class: 
contributor:
  - id: cweinard
abstract: |

---

The related objects section of an object page is a unique space. On a page that’s otherwise focused on diving deep into everything that’s known about a single object, it’s a moment of diversion for those who might prefer skipping across the surface of the collection. While other sections may be painstakingly exact and authoritative, the related objects component might be optimized for serendipity and interestingness.

A related objects section makes an object page into a hub of connections. For those arriving at an object page directly from a Google search (as is the case for most visitors), the related objects component opens a door for further exploration. Even a handful of interesting thumbnail images can suggest new paths. For enthusiasts, who aren’t looking for a specific object to answer a specific question, following a chain of association may best satisfy their needs. (It may also help them formulate a specific question.) For researchers, who are searching for specific object information, encountering related objects may inspire lateral thinking, and a broader search. Related objects can transform an object page from a terminal into a hub for exploration.

Collection objects can be related in many different ways (see running list below). Some of these connections are machine-made, others come from cataloging practice over the years, and others are made through painstaking scholarly research and curatorial practice (exhibitions, publications, etc). 


## How might collection objects be related?

Two objects might share the same...



* Maker 
* Culture
* Creation date
* Accession date
* Place created, place depicted, place found
* Physical dimensions
* Material
* Classification
* Provenance (once owned by same constituent)
* Subject matter
* Keywords in descriptive text
* Exhibition
    * Shown in same exhibition, and shown next to each other
* Gallery
    * On view together and shown next to each other
* Publication (scholarly, but also blogs, social media, etc)
* Related media (audio tour)
* Highlights, or other themed collections
* Popularity (top downloads, visits, etc)
* Dominant color
* Visual similarity


## Related Objects in the Wild



* Brooklyn takes a simple visual approach, offering [30 square thumbnails](https://www.brooklynmuseum.org/opencollection/objects/81660) with no titles or metadata, seemingly looking to catch the eye of an enthusiast visitor. 
* The [Met](https://www.metmuseum.org/art/collection/search/203392) and [Art Institute of Chicago](https://www.artic.edu/artworks/129884/starry-night-and-the-astronauts) offer tabbed selections with various kinds of relationships. (An earlier [Met prototype](https://mw19.mwconf.org/paper/the-mets-object-page-towards-a-new-synthesis-of-scholarship-and-storytelling/) was made in response to research that indicated visitors wanted to know _why_ certain items were shown as related.) 
* The [Minneapolis Institute of Art](https://collections.artsmia.org/art/90972/forehead-ornament-for-a-horse-bernadine-real-bird) doesn’t have a related objects section per se, instead nearly every metadata field can be clicked to open a tiny thumbnail gallery of objects related according to that field.
* Related objects sections can also be immersive--even becoming a free-standing interpretive layer. The [Royal Academy](https://www.royalacademy.org.uk/art-artists/work-of-art/design) has both a section for associated works of art (with objects by the same maker) and a related objects feature that expands to full screen, showing an interactive network graph (driven by subject tags) with thumbnails as nodes. 
* The V&A takes a [playful approach](https://collections.vam.ac.uk/item/O267196/felix-the-cat-furnishing-fabric-calico-printers-association/), offering 6 thumbnails in a pinboard arrangement. Hit the shuffle button to load 6 new objects.
* The [Barnes](https://collection.barnesfoundation.org/objects/4720/The-Postman-(Joseph-Etienne-Roulin)/visually-similar) offers related objects based on visual similarities (in keeping with the founder Albert C. Barnes’ interest in visual ensembles, of course.)

Getty’s new related objects component, called “More from the collection,” is distinctive in its aim for serendipity and interesting-ness. The focus isn’t on filtering or narrowing, but on broadening and introducing the unexpected. These are objects you might not think to search for—like books discovered by chance on an adjacent library shelf, or images bundled together in a Picture Collection. There are ample opportunities on the object page—and in the collection online more broadly—for precise search and faceting; this is a moment for adjacency and generative juxtaposition.

The design is simple and straightforward. The section features six thumbnail images, justified along the bottom edge, with title and artist below. (This “shelf” configuration is a common Getty design element in desktop views.) The component falls just below the main image block and the alternate views sections; it’s strategically placed at the bottom of a visually vibrant section to give enthusiasts an inviting off-ramp before the text-heavy detail sections below. While a welcome diversion for enthusiasts, it’s important that the component isn’t a distraction for experts. The simple design is meant to work on both counts.

The Getty implementation leaves open the question of _how_ the six objects are related to the object page. In other online collections, you might see tabs or labels that define the kinds of relationships in the related objects section. (The Met recently added these, and the Art Institute of Chicago has them as well.) On the Getty page, such direct connections are provided in the object details section. (Links to artist, medium, culture, etc. take you to works of art related in that way.) This is important functionality, but it’s best handled elsewhere. Relieved of such responsibility, the related objects component has the freedom to offer an element of breadth, surprise and even playfulness.

Behind the simple visual design lies a complex algorithm crafted to generate interesting—and perhaps unlikely—juxtapositions. For each object page, the algorithm is tasked with selecting six interesting object records; each must be unique, and have an image. A number of handcrafted queries take a given object’s specific qualities—some of which aren’t displayed on the page—and combine them into searches that would be impossible in the search interface. Some examples:



* “Rank the most similar objects based on a combination of title, alternate title, and description.” 
* “Match the color palette, creation date (within a half century), and the same material or classification.” 
* “Match the color palette and creation date (within a half century), but from a different culture.”

Each query tries to return twelve results. The most relevant result from each query is selected (if it hasn’t already been selected by another query.) Inverse queries—those that might surface objects from different departments or classifications, etc—are given a slight preference when filling slots. One could describe the algorithm through the lens of generative art—a bespoke interesting-ness engine with a single work of art as a seed, and a set of six compelling objects as a result.

The plan is for the related objects component, and the algorithm behind it, to evolve over time. Each set of six selections is ephemeral; a new set is generated for each session. Two different visitors on the same page will almost certainly see two different sets. Analytics will track how often related objects are clicked in the aggregate, and can indicate just how far a chain of association might go. Even in the short time since launch, it’s clear that the related objects component is well-used. Tuning the algorithm may itself become a creative endeavor for the technical team!

It’s important to note that the results of algorithms can be unexpected, despite being well-crafted and well-intentioned. The Getty component was crafted to allow for serendipity and generative, even poetic, juxtaposition. With a collection as broad and diverse as Getty’s, however, there is a chance that the unexpected might be unsuitable for some audiences. This is something we’ll need to keep an eye on. The title of the section, “More from the collection” was chosen to set expectations. “You may also like” or similar would be a poor choice if inappropriate items were to appear. Also, the site doesn’t track individual users in order to feed the algorithm, so a personal address didn’t seem right.


>The feeling of fortuitous gratitude at coming across unexpected information is something most of us who’ve done any research, have experienced — that kismet of finding the perfect book, one spine away from the one that was sought.

Sometimes the most important find is one you didn’t think to search for. Like the pivotal book you find on a nearby library shelf, the related objects section aims to set the stage for unexpected discoveries..