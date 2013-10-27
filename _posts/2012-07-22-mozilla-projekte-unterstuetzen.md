---
layout: post
title: "Mozilla-Projekte unterstützen"
date: 2012-07-22 13:33:37
categories: Mozilla.de
comments: true
---

Es wird immer mal wieder die Frage in den Raum geworfen, wie man denn eigentlich 
bei Mozilla tätig werden kann. Ich möchte im Folgenden versuchen Antwort zu 
geben.

Nach <a title="These bugs are relevant to my interests" 
href="http://www.joshmatthews.net/bugsahoy/">Bugs Ahoy</a> hat Josh Matthews vor
Kurzem <a title="What Can I Do For Mozilla" href="http://whatcanidoformozilla.org/">
What Can I Do For Mozilla</a> gestartet und damit ebenfalls versucht, besser auf
das Mitwirken an Mozilla-Projekten aufmerksam zu machen. Schauen wir uns beide 
Seiten mal kurz an:

»<strong>Bugs Ahoy</strong>« sucht nach Einträgen in der projektübergreifenden 
Bug-Datenbank <a title="Bugzilla" href="https://bugzilla.mozilla.org/">Bugzilla</a>,
die über einen Mentor verfügen. Das sind zur Zeit immerhin über 200 Bugs, bei 
denen man sich auf Rückmeldung durch einen Ansprechpartner in angemessener Zeit 
verlassen kann. Themenbereiche und Kenntnisse lassen sich bei der Suche
einschränken. Es geht bei diesen Bugs hauptsächlich um die Kernprodukte Mozillas
und um Teilbereiche der Gecko-Engine, die den meisten Programmen wie Firefox, 
Thunderbird, SeaMonkey, etc. zu Grunde liegt.

»<strong>What Can I Do For Mozilla</strong>« kommt spielerischer daher: Auch 
hier kann man sich je nach Kenntnissen und Interessen durch die Projekte
klicken. Außerdem sind auch »Nebenprojekte« wie 
<a title="PDF.js" href="https://wiki.mozilla.org/PDF.js">PDF.js</a>, 
<a title="Shumway" href="https://github.com/mozilla/shumway">Shumway</a>, 
<a title="Rust" href="http://www.rust-lang.org/">Rust</a> und einige mehr 
aufgeführt, die ebenfalls von Mozilla unterstützt werden.

<p style="text-align: center;"><strong>Klappern wir also mal ein paar Bereiche
ab: »Wo kann ich wie helfen?«</strong></p>

<h3>Mozilla Codebase</h3>
Eine Einführung in die Mozilla »Codebase«, also alles was mit den Kernprodukten
wie Firefox und der Engine zu tun hat, wird in der 
<a href="https://developer.mozilla.org/en/Introduction">Introduction</a> auf 
<a href="https://developer.mozilla.org">developer.mozilla.org</a> ausführlich 
gegeben. Ist man mit Bugs Ahoy auf etwas aufmerksam geworden, an dem man gerne 
arbeiten möchte, findet man hier die nötigen Schritte. MDN bietet sich als zusätzliche 
<a href="https://developer.mozilla.org/En/Developer_Guide">Informationsquelle 
für Entwickler</a> an. Die Codebase besteht nicht nur aus C++ und C. Es werden 
außerdem JavaScript, Python, Perl, XUL und andere Sprachen verwendet.

<h3>Webentwicklung</h3>
Um Frontend- (HTML, CSS, JS) und Backendentwicklung (Python/Django) der 
zahlreichen Mozilla-Webseiten kümmert sich ein großes Webdev-Team. Die Projekte
finden sich auf <a href="https://github.com/mozilla">Github</a>, dürfen dort 
geforkt und weiterentwickelt werden. Pull Requests welcome!
Außerdem haben die größeren Seiten eine Vielzahl von offenen Tickets, die 
ebenfalls <a href="https://wiki.mozilla.org/Webdev/GetInvolved">von Mentoren 
betreut</a> werden. Es ist eine gute Idee, nachdem man sich ein interessantes 
Ticket gesucht und sich vielleicht schon etwas die Hände im Code dreckig gemacht
hat, im IRC-Channel des Projektes vorbei zu schauen und mit Mentoren/der
Community den Kontakt sucht. Jede Hilfe ist dort sehr willkommen und es wird 
garantiert gerne Starthilfe gegeben!

<h3>User-Support (Sumo)</h3>
Für die Endbenutzer gibt es jeweils Hilfsportale für 
<a href="https://support.mozilla.org/de/home">Firefox</a> und für 
<a href="https://support.mozillamessaging.com/de/home">Thunderbird</a>. Dass es
diese Artikel auf Deutsch gibt, ist freiwilligen Übersetzern zu verdanken. Auch 
hier wird <a href="http://support.mozilla.org/de/localization#untranslated">
Unterstützung gebraucht</a>. Die Support-Community besteht auch aus klassischen 
Foren wie etwa das <a href="http://www.camp-firefox.de/forum/">Firefox-Forum</a>
oder das <a href="http://www.thunderbird-mail.de/forum/">Thunderbird-Forum</a>. 
Weiteren Kontakt mit End-Usern gibt's durch die
<a href="https://support.mozilla.org/de/army-of-awesome">Army of Awesome auf
Twitter</a> und im Supportchannel 
<a href="irc://irc.mozilla.org/firefox.de">#firefox.de</a>, wo Live-Support für 
Firefox-Probleme bereitgestellt wird.

<h3>Dokumentation</h3>
MDN, das <a href="https://developer.mozilla.org">Mozilla Developer Network</a>, 
ist ein gigantisches Wiki, welches auf der einen Seite umfangreiche 
Dokumentation zu Webtechnologien und auf der anderen Seite Informationen zum 
Code von Firefox und Gecko beinhaltet. Wird im ein neues Feature entwickelt, 
wird dieses als "<em>dev-doc-needed"</em> markiert und muss im MDN dokumentiert 
werden. Eine <a href="http://beta.elchi3.de/doctracker">Übersicht offener 
Dokumentationsanfragen </a>zeigt an, was je Release noch im Wiki zu ergänzen ist.
Im <a href="irc://irc.mozilla.org/devmo">#devmo</a> IRC-Channel sind Fragen dazu
willkommen.

<h3>Lokalisierung (L10n)</h3>
Produkte und Webseiten werden in über 80 verschiedene Sprachen übersetzt. Dabei
wird komplett auf die Unterstützung von Freiwilligen aus aller Welt gesetzt. 
Die Webseitenlokalisierung läuft über 
<a href="https://localize.mozilla.org/de/">Mozilla Verbatim</a>. Zur 
Produktübersetzung verweise ich auf einen sehr ausführlichen 
<a href="http://home.kairo.at/blog/2012-03/de_nuetzliche_ressourcen_fuer_mozilla_ue">Blogpost von KaiRo</a>.
Beiden Bereiche sind komplett auf ehrenamtliche Arbeit angewiesen, ansonsten 
würden Produkte und Webseiten nur in englischer Sprache erscheinen. Es werden 
keine Programmierkenntnisse benötigt, um Übersetzungsarbeit leisten zu können.

<h3>Qualitätssicherung (QA)</h3>
Um für Webseiten und Produkte ein hohes Maß an Qualität zu erzielen, ist 
kontinuierliches Testen erforderlich. 
<a href="http://nightly.mozilla.org/">Nightly Builds</a> zu verwenden und 
auftretende Fehler zu melden lässt sich gut nebenbei erledigen. QA ist aber mehr
als das. Auf den Seiten von <a href="https://quality.mozilla.org">quality.mozilla.org</a>
findet man Informationen zu den <a href="https://quality.mozilla.org/teams/">Teams</a>
und wie man dort helfen kann. Es finden regelmäßig Test-Events statt.

<h3>Weitere Projekte</h3>
* Interessiert <a href="https://wiki.mozilla.org/MarketingGuide">Marketing</a> für Mozilla zu betreiben?
* Lust die nächste Generation des <a href="http://mozillaopennews.org/">Journalismus</a>
im offenen Web mitzugestalten?
* <a href="http://www.brandeins.de/magazin/freiraeume/jeder-ist-ein-lehrer.html">Lehrer</a>? 
Interessiert Menschen vom <em>Benutzern</em> des Internets zu <em>Machern</em> des 
Internets zu bewegen? Die <a href="https://wiki.mozilla.org/Webmaker">Mozilla Webmaker</a>-Initiative 
versucht das Verständnis von Webtechnologien zu erhöhen und 
<a href="http://commonspace.wordpress.com/2011/09/12/mozilla-as-teacher/">der Welt
das Programmieren beizubringen</a>
* Start-Up-Idee? Super! <a href="https://webfwd.org/">WebFWD</a> unterstützt neue
Projektideen, die dem offenem Web dienen, Innovationen schaffen wollen und auf 
neue Webtechnologien setzen.

Und vieles mehr ...

<h3>Grow Mozilla</h3>
Wenn noch nicht das Richtige dabei war, hilft vielleicht 
<a href="https://wiki.mozilla.org/Contribute#Functional_Areas">diese Liste</a>. 
Die »Grow Mozilla«-Initiative arbeitet daran, mehr Leute zu begeistern sich zu 
engagieren. Helfen Helfer zu finden wäre also sogar noch eine weitere Möglichkeit
sich einzubringen.

<h3>Kontakt zur deutschen Community</h3>
Fragen? Mittwochs um 21.00 Uhr in 
<a href="irc://irc.mozilla.org/deMeeting">#deMeeting</a> auf
<a href="http://irc.mozilla.org/">irc.mozilla.org</a> treffen sich 
deutschsprachige Freiwillige aus den verschiedenen Mozilla-Projekten. Einfach 
mal vorbei schauen und uns gerne mit Fragen löchern!

<p style="text-align: center;"><a href="http://www.mozilla.org/en-US/contribute/">We believe in you!</a></p>
