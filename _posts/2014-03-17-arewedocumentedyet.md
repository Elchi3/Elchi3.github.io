---
layout: post
title: "Are we documented yet?"
date: 2014-03-17 15:00:00
categories: Mozilla
mozplanet: true
---

<a href="http://arewedocumentedyet.com">No, we aren't (yet)</a>.

Every wiki and documentation site fights against a big problem: Content outdates
pretty fast as the software or the technologies evolve. This is more than true
for MDN.

When we switched to the rapid release model, the way we document on MDN changed
as well. A process for having release notes every six weeks has been set
up by Jean-Yves Perrier (teoli) and our old tools like the 
"<a href="http://beta.elchi3.de/doctracker/">DocTracker</a>",
which gets us dev-doc-needed bugs per release, were helpful.
However, writing detailed documentation for all these changes in six weeks,
is no longer achievable. There are a lot of more changes in six weeks today than
in six weeks two years ago.

In the old days, "<em>yes, we are documented yet!</em>", meant that the dev-doc-needed bug
counter was near to zero for a given release.

I thought about building new tools that could answer how are doing today. Fortunately
<a href="https://github.com/mozilla/kuma">Kuma and KumaScript</a>
are open source and hackable, so that I was able to build new tools directly into MDN.

<h2 id="doc_status_pages">Introducing documentation status pages</h2>
So, how can we measure if <em>we are documented yet</em>, today?

The MDN documentation team switched to concentrate on content topics rather than
to document everything belonging to a release. Several 
<a href="https://developer.mozilla.org/en-US/docs/Project:MDN/Contributing/Topic_drivers">Topic Drivers</a>
started to maintain specific parts of MDN.

If you look at a content section on MDN, you can definitely identify more "health
indicators" than just the dev-doc-needed bug list. To make the state of the 
documentation visible, we started to build 
<a href="https://developer.mozilla.org/en-US/docs/MDN/Doc_status">documentation status pages</a>
for sections on MDN.

Let's take the <a href="https://developer.mozilla.org/en-US/docs/MDN/Doc_status/JavaScript">
JavaScript documentation status</a> as an example to see what we currently measure.

<img src="/assets/img/js-doc-status.png" alt="JavaScript doc status summary">

Quality indicators:

* <strong>No tags</strong>: Every page should have a tag so that our search displays
 pages based on that information. For most sections there is also a tagging standard.
* <strong>Needs* tags</strong>: Did you know that you can add a <em>Needs</em> tag
 to every MDN page to indicate that something is missing? E.g. NeedsExample or NeedsBrowserCompat?
 Pages tagged like this will appear here.
* <strong>Editorial and technical reviews</strong>: You might have seen banners
 on several MDN articles asking for review. These pages are now listed here to 
 get addressed at some point!
* <strong>Outdated pages</strong>: If the last edit date of a page is more than a year
 ago or older than a specific date we chose, a page should be considered as 
 outdated and will need a check.
* <strong>Dev-doc-needed and documentation requests</strong>: Sure, let's not
 forget about one of the main sources of information: Bugs!
* (...) This is the current set of "health indicators", but we 
 might find more in the future and expand this list. Let me know if you have ideas!


<h2>Open to do list</h2>
Besides the automatically created quality indication list, there is also room for 
sharing what else is needed in the content section. For example, for JavaScript, we need to 
<a href="http://florianscholz.com/2014/01/javascript-documentation-clean-up-and-mdn-redesign-history/">
clean up our documentation for ECMAScript 6</a> and some tutorials and guides are missing, too.
That information should be available in the open and shared with people interested
in writing on MDN. So, if you are asking <em>what you can do for MDN</em>,
you should find answers there!
 
<h2 id="localization_status">Introducing localization status pages</h2>

When localizing MDN, we are speaking of 
<a href="https://developer.mozilla.org/en-US/docs/all">11,000 pages</a>. This is
a huge task and not all docs are worth translating. So, with the idea of
content sections, we are also looking into making smaller lists of pages in need of
localization.

To keep track of the localization work, a localizer needs to know if a translation 
is available and whether it is up to date with the English source. So, for each 
documentation status page there is also a localization status page.

Here is an example that lists the 
<a href="https://developer.mozilla.org/ja/docs/MDN/Doc_status/JavaScript">translation status of the JavaScript section for Japanese</a>:
<img src="/assets/img/ja-js-status.png" alt="Japanese localization status for JavaScript">
Also have a look of the translation overview pages, e.g. 
<a href="https://developer.mozilla.org/ja/docs/MDN/Doc_status/Overview">all sections for Japanese</a>.

<h2 id="help">Help us!</h2>

With these status pages for both, English documentation and the translations, a lot
of work becomes visible. If you have expertise in one or more of the topic sections,
please have a look and help us with documenting. If you are a localizer and would
like to have a status page for your language, feel free to add one or contact us
to help you.

In general you can find us on irc.mozilla.org in #mdn.<br/>
You can also reach me at fscholz@moco or Jean-Yves at jperrier@moco.

The first iteration of these tools is now finished. The different documentation
status pages we have right now, are monitoring around 40% of all MDN pages. We
are looking into increasing that number.

Let's document the Open Web!

<h2 id="doc-status-api">PS: Pretty graphs using the doc status API</h2>
How about a nice page like <a href="http://www.arewefastyet.com/">arewefastyet.com</a> 
or <a href="https://areweslimyet.com/">areweslimyet.com</a>? I have built a 
documentation status API. Anyone wants to collect data and make that happen? :-)
For instance, a JSON for the JavaScript documentation status, can be found 
<a href="https://developer.mozilla.org/en-US/docs/MDN/Doc_status/JavaScript?raw&macros&section=json">here</a>.

