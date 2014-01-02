---
layout: post
title: "JavaScript documentation clean-up and MDN redesign history"
date: 2014-01-02 18:00:00
categories: Mozilla
comments: true
mozplanet: true
---

<small>(As of December 30, 2013, I am involved with MDN for 4 years.)</small>

Since I have started to work full-time at Mozilla's MDN documentation team in
October, I have mainly focused my day-to-day work on a major clean-up of the
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/">
JavaScript reference documentation</a>. The reference contains hundreds of pages
and was written over the last ~14 years. I focused on
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects">
standard built-in objects</a> for now and haven't finished the complete overhaul
yet. For progess, check out the
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Doc_status">
doc status page</a>, where I started to track this and future efforts in MDN's
JavaScript section.

While going through lots of pages, I have seen ones with pretty good
information but also some survivals from the past: Occasionally you find version
data like "NES3.0", which has nothing to do with entertainment by Nintendo, but
dates back to the Netscape Enterprise Suite / Server. I also noticed that
we had MediaWiki and MindTouch DekiWiki before Kuma, as still some odd markup
is decorating parts of our documentation.

At the same time the MDN teams (both, writers and Kuma developers plus our
volunteers) were busy with a major redesign of the site, which has launched
successfully on December 9. The beta we ran two months before launch helped us
enormously to gather feedback and to improve. For details, have a look at the
<a href="https://hacks.mozilla.org/2013/12/the-mozilla-developer-network-has-a-new-face/">
Mozilla Hacks article about the redesign</a>.

The redesign will help a lot in terms of navigability and the
overall appearance of the documentation. With cleaning up the pages even
further, we want to make sure to get the most of the new design.
There have been efforts in the past about reorganizing parts of the docs
and the site had several designs. I am wondering what has improved
significantly and what we should improve now for continuing being the first address
for (JavaScript) documentation on the web.

Where had contents come from originally? How did MDN grow up? Let's take an
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test">example JS reference page</a>
and have a look at what has happened over the years.


<h3 id="y2000">DevEdge, 2000 - 2005 [<a href="{{ site.url }}/assets/img/mdn-2000.png">Image</a>,
<a href="https://web.archive.org/web/20021202221020/http://devedge.netscape.com/library/manuals/2000/javascript/1.5/reference/regexp.html">archive.org</a>]</h3>
In the early days there was DevEdge. The developer documentation from Netscape
and the origin of todays MDN (JavaScript) documentation.
It had a white and blue design. Our RegExp object test site is documented on a single page
including all properties and methods. The documentation is structured like a
book with a previous / next pagination and chapters. However, no table of
contents of the article itself or other sidebars for navigating through this 'book'
is given. In the content, tables are used to display summaries or key information.
Although the site is using the full width, there is also a good amount of unused
white space between the sections and headlines.

In 2003 a team at Netscape (including <a href="http://www.meyerweb.com">Eric Meyer</a>) overhauled the site to show a
cross-browser, standards-based, accessible and user-controllable website:
<a href="https://web.archive.org/web/20030411081826/http://devedge.netscape.com/viewsource/2003/devedge-redesign/">
Netscape DevEdge Redesigns As Standards Showcase</a>.
The appearance of the content did not change significantly on our RegExp test page,
but look ma, no tables!

On October 12, 2004, the popular developer website was shut down by AOL.


<h3 id="y2005">MDC (MediaWiki), 2005 - 2008 [<a href="{{ site.url }}/assets/img/mdn-2005.png">Image</a>,
<a href="https://web.archive.org/web/20051227012548/http://developer.mozilla.org/en/docs/Core_JavaScript_1.5_Reference:Global_Objects:RegExp:test">archive.org</a>]</h3>

Mitchell Baker and others "<a href="https://blog.lizardwrangler.com/2005/02/23/devmo-and-devedge-updates/">reached
an agreement with AOL that allows us to post, modify, and create new
documents based on the former Netscape DevEdge materials</a>". In other words,
what happened to the Mozilla source in 1998, finally worked for Netscape's
developer documentation as well: It became open source. Deb Richardson joined
the Mozilla Foundation as a Technical Editor and lead the new DevMo project for
community driven developer documentation.

MediaWiki was set up and DevEdge contents got imported (<code>$migration = 1;</code>).
The design is white and blue again. The layout changed to a typical MediaWiki
powered site. For the first time there is a sidebar on the left containing
wiki-specific links and tools.

Content-wise the pages of the JavaScript documentation got split up. The test method
now had its own page. In addition, a table of contents is displayed on top of articles.
With MediaWiki under the hood, it was now possible to use templates and WikiText markup.

The documentation is editable by anyone from now on. For the first time contents were translated
into other languages. A new collaborative element in Mozilla spheres was born and
anyone is welcome to help making it better and to share knowledge.

<a href="http://www.bitstampede.com/">Sheppy</a> joined Mozilla in April 2006.

Large contents of XULPlanet.com got migrated to MDC in 2008 (<code>$migration++</code>).


<h3 id="y2008">MDC (MindTouch Deki), 2008 - 2011 [<a href="{{ site.url }}/assets/img/mdn-2008.png">Image</a>,
<a href="https://web.archive.org/web/20080907192444/http://developer.mozilla.org/en/Core_JavaScript_1.5_Reference/Global_Objects/RegExp/test">archive.org</a>]</h3>
Announced in <a href="http://www.bitstampede.com/2007/11/16/mdc-big-changes-ahead/">November 2007</a>
and live in <a href="http://www.bitstampede.com/2008/08/19/mdc-on-deki-now-alive/">August 2008</a>,
the Mozilla Developer Center switched to MindTouch DekiWiki.

All contents were migrated from WikiText to HTML and DekiWiki templates (<code>$migration++</code>) and a new design
shipped, too. Again white and blue are the dominating colors. On our test page, the toolbox
sidebar on the left is no more. Instead, the table of contents is floating right
to the main article. Tags and file attachments are now part of the page. The wiki
tool links have moved to the top along with the breadcrumb navigation. The content
itself was still almost the same - only minor changes.


<h3 id="y2011">MDN (MindTouch Deki), 2011 - 2012 [<a href="{{ site.url }}/assets/img/mdn-2011.png">Image</a>,
<a href="https://web.archive.org/web/20111109184541/https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/RegExp/test">archive.org</a>]</h3>
Redesign time! No wiki engine change or migration. Just a redesign! The colors changed
to a more dark skin. Header and footer were now black. The main article looks like
it is on a piece of paper and the content was emphasized from the rest of the site.
It seems to me this design was the first one that changed the appearance and the
colors more drastically than any other redesign in the past. Our RegExp test page
got minor content additions and at least does not talk about "NES" anymore.


<h3 id="y2012">MDN (Kuma), 2012 - 2013 [<a href="{{ site.url }}/assets/img/mdn-2012.png">Image</a>,
<a href="https://web.archive.org/web/20121013150508/https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/RegExp/test">archive.org</a>]</h3>
<a href="https://github.com/mozilla/kuma">Kuma</a>. Forked from
<a href="https://github.com/mozilla/kitsune">Kitsune</a> in early 2011 and
<a href="http://www.bitstampede.com/2012/08/03/introduction-to-kuma-templates-and-scripts/">launched on August 3, 2012</a>,
is a Mozilla-built wiki platform based on Django with an own "KumaScript" macro
system which uses Node.js. You have guessed it: All contents were migrated from
DekiWiki to the Kuma platform (<code>$migration++</code>). As you can see on our page, the
design and the content did not change much. I think most people did not even notice the new engine
under the hood (besides the fact, that MDN was now reachable again and did not fail with
one of the DekiWiki errors or performance issues we have been dealing with for months).
One minor thing I like to mention: We added a list of contributors to every page
and I think that was an important step as still lots of people do not know that MDN
is wiki. Just hit edit and kick some ass! It's easy as that! (even our beloved
spammers found out).


<h3 id="y2013">MDN (Kuma), 2013 - present [<a href="{{ site.url }}/assets/img/mdn-2013.png">Image</a>]</h3>
Huh? Blue and white again? Yes! (no M$ conspiracies here, really!)
The recent redesign has been discussed a lot. So, I want to have a closer look at
the JavaScript reference page. We can see several new things
(the first time that contents changed more obviously since DevEdge):

* A sidebar on the left offers links to the properties and methods that belong to object we are looking at.
* Page titles are updated to the correct and full API name.
* Each page now contains a table containing specification information. The content
is <a href="https://bugzilla.mozilla.org/show_bug.cgi?id=867609">no longer focused on JavaScript versions</a>
but instead mentions ECMAScript versions.
* Pages are updated to be no longer Gecko-specific. Browser-specific information lives
under the "Browser Compatibility" section.
* Every page consists <em>at least</em> of the sections Summary, Syntax,
Description, Examples, Specifications and Browser compatibility.
* Tags are added for best results with the new ElasticSearch search engine.
* And finally: Links pointing to redirects and odd markup from the past wiki
engines have been fixed. Lots of house cleaning.


<h3 id="y2014">2014 and onward</h3>
Long journey. Still here?
Do you know the value of <code>$migration</code>? In December, Will Bamberg migrated
the <a href="https://addons.mozilla.org/en-US/developers/docs/sdk/latest/">Addon-SDK</a>,
so there is another <code>$migration++</code>. Maybe I have forgotten about other
projects. Lots of things from the old mozilla.org site probably. The point is:
MDN is huge, it is a source of infinite information, but the quality is variable.
Contents have been added and added through migrations and volunteers.
With improved navigation and the team looking at content structures and information
architecture, much more of these contents become visible.

With our own Kuma platform and a really good redesign, one thing to look at in
2014 and onward, is how to improve our content. Probably similar to the JavaScript
clean-up (which I want to finish in Q1), it would be nice to take this to other areas of
MDN and define what "healthy" docs for a given section look like.
And the information about the state of these docs of course should live somewhere
visible to our community, so that anyone is able to jump in and can help.
Doc status pages might be a first step here. We are probably a Firefox 4 now. Good
things on board and a bigger launch, but room for improvements and iterations upcoming.

Please leave a comment or write to our <a href="https://lists.mozilla.org/listinfo/dev-mdc">mailing list</a>.
I would love to hear some feedback about JavaScript docs, content plans or MDN in general.
