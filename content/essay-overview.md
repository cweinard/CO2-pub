---
label: 3
title: Collection Overview
subtitle: Showing the big picture
weight: 55
type: essay
class: 
contributor:
  - id: cweinard
abstract: |

---

The collection overview is the homepage for a museum collection. When you click on “Collection” or “Search the Collection” in the main navigation of a museum website, this is where you land. On one hand, the collection overview carries the symbolic weight of the whole museum on its shoulders: if museums are defined by their collections, then this page defines the museum on the web. On the other hand, this page rarely ranks high in terms of audience use; online collections as a whole often garner significant traffic, but collection overview pages, not so much. (Most visits to collection pages come via Google and organic search, rather than through the museum website itself.) For some museums, the collection overview can be the site of a titanic power struggle between curatorial departments jockeying for recognition, or worse—an afterthought. For other museums, though, the collection overview is an opportunity to introduce a broad audience to the collection—to show what makes up the museum’s collection, to reveal what makes it unique and interesting, and to equip and inspire audiences to search, browse and explore.


## A Typology of Overviews

Collection overview pages range from the very simple to full-featured and elaborate. Broadly, they fall within four distinct types:


### Search Box

A page with just a search box (and perhaps some explanatory text) is the archetypal collection overview. When collection databases were first ported onto the web, this was the access page. If you weren’t looking for something in particular, or didn’t know what terms might garner useful results, or if you didn’t know what sorts of things were in the collection, then this search box was a roadblock. Few of these remain, thankfully. (To this day, however, when staff access the collections management system internally, chances are good they’ll use a simple search page like this to do it.) 


### Departmental

The departmental view is based on the curatorial departments that support the collection. The collection overview links to pages that describe each curatorial department and its collection, perhaps including information about the curators themselves. Conservation and publications may be part of the mix as well. This approach mistakes internal org structure for an appropriate audience-facing finding aid, and risks creating information silos. It directs interest in the collection toward information about internal departments, making it hard for audiences to get to the business of browsing, exploring and looking at art.


### Highlights

This most popular type of collection overview features a curated selection of collection objects presented as a grid of thumbnail images. The immediate dive into visual browsing is a clear advantage here. Defining a collection by its “greatest hits,” however, risks focusing exclusively on individual “masterpieces” and perpetuating a popular status quo. (It’s no wonder that the most visited objects in the online collection are the ones on the first row.) Regularly changing the order of the curated set is one way to broaden the perspective. [Harvard Art Museums] [Art Institute of Chicago]


### Storytelling

Showcasing stories about the collection—through articles, blog posts, video or audio—is a natural way to provide context for the collection. Presenting sets of collection objects  using text and rich media leverages many museums’ core competency. This approach, however, requires significant editorial resources and ongoing organizational commitment, which can be hard for many museums to sustain. Further, the storytelling type risks reinforcing the museum’s authoritative perspective, adding an interpretive layer at a moment when audiences might be equipped to create their own stories with the collection. The Rijksmuseum shows a way forward here by featuring audience-created sets alongside stories developed by the museum. [V&A]


### Computational

The computational approach uses data visualization techniques to give a sense of the collection as a whole. Maps, charts, graphs, etc. translate quantitative collection data into broad insights that can inform the process of searching and browsing. The downside, perhaps, is the reduction of a nuanced cultural collection to a quantified dashboard report. Few of this type exist in the wild. Most computational collection overviews exist as alternate interfaces, providing a pure browsing experience separate from the online collection. [WCMA, australia collection]

The old Getty collection overview was a Departmental page at heart. A sentence of text describing the whole collection, then a search box, followed by six image links leading to pages for Getty’s six curatorial departments. (Images linking to a recent blog post and video are a nod to a Storytelling approach.) Getting to an object page required three clicks—first to a departmental page, then to a departmental highlight in a carousel, then a link in the caption of a modal image. That’s too much. (Audiences might be forgiven for thinking the only way to get to the art was through a departmental office.) The search logs pointed to the problem as well: when “cat” and “dog” are the most popular search terms, it may be that people will enter the first word that comes to mind just to see some art. It was difficult to get to a work of art, and the page offered no broad sense of the collection as a whole. There was ample room for improvement.


## Getty’s New Overview

The new collection overview sets out to re-imagine the Getty’s old collection landing page in order to improve the experience of enthusiasts and researchers alike. The page has several jobs to do:



1. Provide a marquee entryway for collection search.
2. Provide a view of what makes up the collection as-a-whole.
3. Offer direct links to works of art.

Moreover, we wanted the page to be visual, sustainable, and on-brand. We couldn’t dedicate editorial resources to write stories about the collection, so the idea was to show, not tell. The page would need to change and adapt over time, and it would need to fit beautifully within the design language of the new Getty site.

The prominent search remains a necessity for Getty’s research community, and it’s placed at the top of the page in the new design. A row of quick suggested searches have been added as a welcome mat for enthusiasts to enter through the search box. These suggested searches will be changed over time (perhaps to reflect a holiday season, or a current news event, or an exhibition theme). Even search can be made more approachable.

Below the search box, a new dynamic visualization provides a view of the collection as a whole. The component takes the form of a simple bar chart, with cropped images representing categories of objects in the collection. The bold colors of the Getty palette overlay the images to indicate the proportions of each category. The default view shows Getty’s collection by era: it’s clear antiquities make up a large part of the collection, along with modern and contemporary works of art. Creation date is just one way to look at the collection, however. A row of tabs offer other perspectives on the collection, like “Department” (Getty’s well-known paintings make up a small percentage of the collection; photographs abound), and “Image use” (most objects have open access images.) The visualization provides high-level perspectives on the collection as a whole, through images and color.  

The visualization’s interaction design is straightforward. Hovering over a column (on wider screens) reveals the representative image beneath, along with basic information about the object. A click leads to appropriate search returns, or directly to the object page for the item. The idea is to get people looking at art as quickly as possible. The visualization isn’t meant to provide a new way to browse, or to create an alternate interface for exploration. Much like a magazine cover, or a visitor center at a park, the visualization gives an appealing overview of what’s inside, tailored for interested enthusiasts—then it sends you on your way to explore.

The visualization is built to be a flexible and sustainable component of the Getty site. The content for the visualization—all the data for tabs, categories, colors, text labels, percentages, images, image crops, etc.—is drawn from a single text file (JSON). New tabs, showcasing new dimensions and new perspectives on the collection, can be added in time. The raw collection data is updated manually for the time being, though Getty’s infrastructure would allow even the most arcane collection queries could be automated, if need be. The image crops are delivered via IIIF, which Getty already uses throughout the collection online. The visual design is a natural extension of the modular design system developed for Getty.edu.

Collection Overview marks the beginnings of a new approach, and a new perspective. While the old site introduced the collection by way of institutional departments, this new overview sees the collection as a whole, from multiple perspectives. In many ways it’s a production example of a generous interface: it shows rather than tells; it provides samples; shows relationships (in the categories), and provides clues (in the suggestive crops and veils.) Perhaps most importantly, though, it signals a shift from an institutional to an audience-focused approach that seeks to open the collection and get people exploring.