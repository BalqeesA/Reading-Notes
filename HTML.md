

HTML5 is introducing a new set of
elements that help define the structure of
a page.
They are covered here (rather than with the other HTML
elements you met earlier in the book) because you'll find
it easier to understand how they can be used now that you
have seen how CSS can control the layout a page. These
new elements are going to play an important part in creating
layouts going forward

The <header> and <footer>
elements can be used for:
● The main header or footer that appears at the top or bottom of every page on the
site.
● A header or footer for an individual <article> or <section> within the page.

The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.

The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

The <aside> element has two purposes, depending on whether it is inside an <article> element or not. When the <aside> element is used inside an <article> element, it should contain information that is related to the article but not essential to its overall meaning. For example, a pullquote or glossary might be
considered as an aside to the article it relates to. When the <aside> element is used outside of an <article> element, it acts as a container for content that is  related to the entire page. For example, it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.

The <section> element groups related content together, and typically each section would have its own heading

The purpose of the <hgroup> lement is to group together a set of one or more <h1> through  <h6> elements so that they are treated as one single heading. For example, the <hgroup> element could be used to contain both a title inside an <h2>
element and a subtitle within an <h3> element

You already met the <figure> element in Chapter 5 when we looked at images. It can be used to contain any content that is referenced from the main flow of an article (not just images). It is important to note that the article should still make sense if the content of the <figure> element were moved (to another part of the page, or even to a different page altogether). For this reason, it should only be used when the content simply references the element (and not for something that is absolutely integral to the flow of a page).

