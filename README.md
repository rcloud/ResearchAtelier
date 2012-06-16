ResearchAtelier
===============
This is an open source project to develop an application for research and writing on IOS devices.  

The rough specifications are:

* Nonlinear project based data model. When I say nonlinear think scrivener. The data model must be able to accomodate both writing documents and sources(pdf, webarchive, etc)
*  The ability to quickly dump data into the project, tag it, group it, and search it.
* quick transition from writing view to research mode. I have seen some implementations of this. A split view in a single window does not seem to work very well on a small screen even on an iPad. Rather I like the implementation in "Notes Plus" where one simply swipes with two fingers to the left to bring up the browser/pdf viewer. However a popover displaying a webview can be considered
* tabbed document view in both the browser and the writing view.
* full screen mode, but have the ability to pin toolbars and navigation if desired
* from the web view, 1 button click to dump currently visible website into a bin as a webarchive
* from the web view, popover with bookmarks synced from pinboard, etc.
* in writing view, incorporation of a Stacks paradigm, think daedalus touch, but add a view where one is able to see the full layout of the pages
* WikiLinks, and the ability to link a page of a pdf into a text document a la DevonThink.
* The default home web page is a mashup page of search engines, data engines, scientific sources, and other discovery resources, but allow the sources to be user configurable.
* when visiting, e.g. google scholar, be able to quickly import a source, with its bibliographic content automatically inserted. very good implementation of this is Sente
* an assortment of visual themes and fonts. ideally allowing the user to add their own fonts(inkpad does this, not sure of other apps that do)
* the level of annotation supported in the pdf view I am still considering. In my opinion nobody has gotten it right yet. Sente, Mendeley, Papers all have nonstandard annotations, highlights and notes. PDF Expert, iAnnotate and their ilk have standard Adobe compatible annotations, yet they require the full size of the document to be uploaded on sync rather than the delta changes.
* quick capture of text blocks and images from web pages or pdfs, however I don't think these could be added to an NSTextView at this time. So more thought has to go into how to incorporate it. Webviews are a possibility. 