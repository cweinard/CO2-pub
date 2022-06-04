---
label: 7
title: Collection Data
subtitle: 
weight: 90
type: essay
class: 
contributor:
  - id: cweinard
abstract: |

---

Collection data is the lifeblood of a museum’s online collection. The web is a presentation layer—and a brilliant one at that—but it is just one expression of the collection data that flows behind it. The collection data itself has a history: often starting as a personal inventory, with object notations written longhand in a ledger, then copied, perhaps transcribed onto index cards, then into a database, then migrated to a new database, and so on. Along the way, the data changes, with new information added, fixed, deleted, for different uses and applications, by people with different personalities (and perspectives and biases). Collection data is never complete and never finished; there’s always more to know and more to say about collections. Likewise, data formats and structures change; while there is no way to perfectly represent an object in data, there are ways that are more flexible, usable and shareable.

Getty is a trailblazer when it comes to collection data. Its research and scholarship, shared standards and resources, innovative data infrastructure, open images and data, all come together in the new collection online: 


## Research and Scholarship

Getty’s collection online showcases the organization’s collection knowledge and research. Scholarship is a high priority for the institution, and each object page strives to be a compendium of all the Getty knows about an object. Deep collection knowledge, coupled with thoughtful attention to how that knowledge is structured and kept, allows Getty’s new collection online to do things few other online collections can manage.



* The Provenance section shows how research and structure open new avenues for exploration. Getty, of course, is home to the Getty Provenance Index and other resources; it’s a leader for the field in provenance research—tracing the ownership of collection objects through time. Object pages reflect this rich knowledge in a robust object history. Moreover, the provenance section is not just free text, or a single styled block of HTML. Each owner has a separate entry, with structured fields for dates (display dates shown, with machine-readable dates behind the scenes), notes and citations. Constituent names are linked to pages that show every work of art in the collection associated with that person. 
* Exhibition entries show title, location and dates; titles link to an Exhibition page that features related objects (sometimes over multiple locations), as well as descriptive text, and links to exhibition websites and resources, when available. 
* Publications link to the publication, when possible. 
* For objects that are on view, the location links to a Gallery page that shows all works of art in the gallery, along with a map and descriptive text, when available.

The collection online aims for comprehensive, authoritative information, structured thoughtfully, and presented in a way that fosters usability and exploration.


## Data for discovery and social sharing

Collection data is also woven into the HTML itself to make the collection pages more discoverable and shareable. Object pages include Schema.org markup that lets Google (and other search engines) know exactly what the page contains. (The data is delivered as JSON-LD within the head section of the HTML.) Google uses this structured data for the rich results seen on search returns, and this markup also helps power voice assistants, like Siri, Alexa and Google Assistant. Similarly, OpenGraph tags are included in every object page to make sure that collection objects are well represented (with thumbnails, title, etc.) when shared on Facebook, Twitter and beyond. 

Tip: Look in the head section when you inspect the source HTML of an object page to find the structured markup.


## IIIF

The new collection online manages, displays and shares images using IIIF, an open standard for delivering digital resources. IIIF is perhaps best known for enabling audiences to zoom in to explore high resolution images, and Getty’s online collection certainly takes advantage of this capability for open-access images. The image viewer also allows for side-by-side presentations, handy for books and manuscripts. IIIF goes deeper than the presentation layer, though; Getty uses IIIF APIs to serve all collection images on collection online. The API is available for others to use as well, so Getty collection images can be shared, explored, and compared with IIIF images from other collections.

Tip: Check out the link to the IIIF manifest in the pulldown menu under the main image, and in the Technical Metadata section at the bottom of the page. To explore the object in a full-featured image viewer, click the link to “Open in comparison viewer.”


## Vocabularies 

Getty uses controlled vocabularies throughout its collection data. (This won’t come as a surprise, of course, as several of the most prominent vocabularies for art museums—[ULAN, AAT, TGN](https://www.getty.edu/research/tools/vocabularies/)—are administered by Getty Research Institute.) Using the vocabularies helps core systems disambiguate people, places and terms. It also can allow the collection online to tap into information from a shared authority, like artist’s birth and death dates, etc.

Tip: Check out the link to the ULAN record on artist pages in collection online.


## Multiple interfaces

This robust data backend opens up Getty’s deep collection knowledge, including rich context and stories. The data infrastructure supports many possible views into the collection. Researchers with detailed, complex questions can query the data directly, using a SPARQL endpoint. (SPARQL is also available in a helpful web application.) This expert access relieves some pressure on the collection online, allowing it to focus on a broader audience. Additional experimental interfaces are already on the drawing board. Data and infrastructure allows for a range of collection applications, tailored for audience needs.


## Linked Art

Getty’s online collection lives and breathes Linked Art, a new shared data model for describing museum collections. The Getty infrastructure feeds Linked Art data to internal systems—including the collection online—and to a public API. Every object page draws its content from a Linked Art data file (in JSON-LD) and presents it in the browser. Making Linked Art a core part of the infrastructure means the collection data and related services will always be central for Getty: maintained, tested, and available. If the Linked Art data infrastructure fails, the collection online (along with all other collection applications) will go offline as well.

(Getty’s Research Collection Viewer blazed a trail for the Collection Online’s data, systems and infrastructure. For a deep dive on Getty’s Linked Art infrastructure, see

[https://mw21.museweb.net/paper/building-linked-open-data-web-applications-from-the-outside-in-lessons-learned-from-building-the-gettys-research-collections-viewer/](https://mw21.museweb.net/paper/building-linked-open-data-web-applications-from-the-outside-in-lessons-learned-from-building-the-gettys-research-collections-viewer/) )

Tip: Find a link to the object’s Linked.art JSON-LD in the Technical Metadata section at the bottom of the page.

Using Linked Art opens the door for shared opportunities and collaboration. Getty isn’t the first museum to power its online collection with a public API, but it is one of the first to implement Linked Art at scale. What might this mean for museums? 



* Common apps: With a standard data model, an application that’s made to work with one museum’s collection data can easily use data from another museum. (eg. Collection pages built to work with one collection API can be repurposed for another.)
* Shared tooling: Application logic and code can also be shared when there’s a shared data model. For instance, Getty has developed linkedart.js, a javascript library that simplifies the process of presenting Linked Art data on a web page or other media. 
* Aggregation: It’s easier to bring together many collections when they share a data structure.
* Model for others: It’s hard to be on the cutting edge (especially for cultural organizations.) Museums—especially art museums—looking to build collection APIs and online collections can look to Getty as an example. 

Getty’s commitment to linked data holds promise for the museum sector as a whole. In many ways, the notion of linking collections has been the Holy Grail of museum technology. After all, many of the most interesting collection-related questions can only be answered by looking across collections. This ideal, however, requires a shared language and a shared medium. Until recently, museums have been content to tend their walled gardens of data. Getty has put the pieces in place to open the gardens: Linked.art provides a common model for describing collections, a shared language. Vocabularies establish shared authorities, so we know that one museum’s “Vincent van Gogh” is the same person as another’s “Vincent Willem van Gogh.” IIIF provides a standard for sharing images. Schema.org and OpenGraph standards encourage sharing on the web and through social networks. Getty has put the pieces in place to share its collection, and moreover, is dedicated to sharing its resources and know-how as well. As more and more museums do likewise, the long-term dividends of connected collections may be substantial. 
