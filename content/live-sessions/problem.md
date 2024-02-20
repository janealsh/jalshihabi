---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

design:
  columns: "1"
  background:
    color: "#ffffff"
---

<div class="spacetop">

<h1>Defining the Problem</h1>
<br/>

I was a Product Manager at <a href="https://www.maplesoft.com/"> Maplesoft</a> for two softwares, one of which being <a href="https://learn.maplesoft.com/"> Maple Learn</a>. One of my tasks this term was to find a way to define and implement a document-sharing feature into the UI of Maple Learn, and this page describes the implementation portion of this task.

After a meeting with the Senior Product Manager where we reviewed feedback from our most involved users, we defined the problem with two main issues:

  1. <b>Can only share static versions of documents:</b> The existing share button only copied a link of the current version of the document. Any changes after the link was copied would not appear in the document stored under the share link.
  2. <b>Shared copy had no capacity for collaboration:</b> Because the shared copy was static and changes are not reflected within it, synchronous collaboration was not possible within Maple Learn. This was especially important since many of our users were instructors and would greatly benefit from a collaboration feature to use in the classroom.

We were also under a time constraint due to our users' desire for a collaboration feature in Maple Learn, and our primary objective was to ensure their satisfaction.

In summary:

<div class="important-text">
    How do we incorporate a "live" collaboration feature into Maple Learn documents within the shortest time possible?
</div>

