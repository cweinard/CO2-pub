---
label: 6
title: Complex Objects
subtitle: 
weight: 80
type: essay
class: 
contributor:
  - id: cweinard
abstract: |

---

Complex objects are...complicated! In museum collections, complex objects are those in which multiple objects make up a whole. (Many tea cups and a tea pot make up a tea service; multiple panels make up an altarpiece; multiple pages, each with two sides, make up a manuscript, etc.) Museums need to keep a separate record for each component, because each piece might be moved individually, and each might have its own exhibition history, etc. But all of these individual records pose a challenge for online collections, particularly in search and display. (It makes practical sense that the dozens of pottery sherds that make up a pot are each associated with the same ensemble image…but it makes displaying them together a challenge.) When faced with hundreds of pottery fragments, or dozens of manuscript pages, it’s easy to miss the forest in all the trees.

Getty’s old collection online presented complex objects without the context they needed. It treated all records as equal, separate entities, and didn’t do a good job of connecting parts and wholes. Due to display limitations, cataloging information was sometimes duplicated across parent and child records. In some cases, part records were withheld from public view to avoid confusion. There was a lot of room for improvement.


## Examples

Recent examples of online collections from Cleveland Museum of Art, Qatar Digital Library and the Walters show better ways of showcasing complex objects:


### Cleveland Museum of Art

Cleveland’s advanced search supports an option to “include object parts.” ([See screenshot](https://www.clevelandart.org/art/collection/search?search=1952.227&filter-include-parts=1).)
{{< q-figure src="image11.png" class="is-pulled-right" >}}


The resulting search results include a record for the primary object (the whole), along with records for the component objects (the parts). 

Object types (part/whole) are indicated by an icon overlaid on the thumbnail.

(See [blog post](https://medium.com/cma-thinker/searching-for-a-masterpiece-exploring-the-cmas-new-collection-online-658409747f5e) for more on Cleveland’s search.)

Each object page of a complex object includes a note and link: “Part of a set. See all set records” ([See screenshot](https://www.clevelandart.org/art/1952.227)) The link initiates a search for the accession number, with an option set to “include object parts.” The resulting search results page shows all component objects along with the cover (complete) object. 

Unfortunately, the Cleveland implementation doesn’t offer a way to view component objects together as a whole. There is no page-turning image viewer for the 15th-century French book of hours, for instance.

{{< q-figure src="image7.png" >}}


### Qatar Digital Library


{{< q-figure src="image4.png" class="is-pulled-right" >}}
{{< q-figure src="image3.png" class="is-pulled-right">}}


{{< q-figure src="image8.png" class="is-pulled-right">}}


The new Qatar Digital Library (built by Cogapp) includes full-featured accommodations for complex objects.

Search results include cover objects (whole objects) as well as component objects (pages), presented as mini-thumbnails. (Rollover a mini-thumbnail for a larger view.) Search terms are highlighted, and if the search term is found in a component page, that is noted.

Cover objects have a summary page with a unique layout, and the capability to search just the object’s component pages. ([See example](https://www.qdl.qa/en/archive/81055/vdc_100023512370.0x000005))

Component pages are primarily visual, with a robust IIIF viewer, including a side-by-side page view in a universal viewer. ([See example](https://www.qdl.qa/en/archive/81055/vdc_100023515410.0x000079))


Cogapp has a good [blog post](https://blog.cogapp.com/on-new-features-at-the-qatar-digital-library-200907d98536) on the thinking behind Qatar Digital Library.



### The Walters Ex Libris

{{< q-figure src="image10.png" class="is-pulled-right">}}
{{< q-figure src="image8.png" class="is-pulled-right">}}

The Walters has optimized the online presentation of their manuscript collection with a lovely custom IIIF viewer. There are no individual object pages for each manuscript page—each manuscript is presented as a whole, complete collection object, with a page-turning viewer as a main image. ([See example](https://manuscripts.thewalters.org/viewer.php?id=W.39#page/10/mode/2up))

Search results allow direct access to a view of individual component pages (within the manuscript viewer), along with options to download images directly. ([See example](https://manuscripts.thewalters.org/?search=fire))


### Getty Museum

The Getty’s new collection online strives to show complex objects in context. Ideally, when you come upon an object that’s part of a whole, it’s easy to find other parts, and to see the whole. When you encounter an object with parts, you should have easy access to all the parts, and you should be given a good sense of the whole. (In the best case, that sense of the whole might be different depending on what kind of object you’re seeing.) The connections between parts and whole are key.

Some broad requirements help put these ideas into action for collection online: 

* A search option can be activated to include object parts in search returns (returns include only parent records by default.) 
* Search returns are labeled “has parts” or “part of…” for easy identification. 
* Object pages for parent records include a section with images and links to its parts. 
    * If the parent object is composed of fragments, then show a text link to each child record. Individual fragments rarely have their own image. 
    * If the parent object is book-like, show the pages/parts together in a 2-up side-by-side book view
* Object pages for child records show and link to the parent record, as well as to other parts

Complex objects in Getty’s collection are now presented with valuable context, restoring some of the quirky and strange relationships between objects. The broad requirements can’t cover every situation; there are inconsistencies, and “edge cases” abound in museum collections. (This is to be celebrated! It’s part of what makes museum objects special.) Take for example the “[Poet as Orpheus with Two Sirens](https://www.getty.edu/art/collection/object/103QSY),” a nearly life-size sculptural ensemble featuring a male figure (with feet resting on a detached footstool and base—each separately accessioned), and two elegant female figures…accompanied by 304 (!) fragmentary curls. Each part and fragment has its own entry, description and history, but each is also connected and contextualized as parts of a greater whole.
