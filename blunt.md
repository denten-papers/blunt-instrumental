---
title: "Blunt Instrumentalism"
author: Dennis Tenen

---

I am on the side of the makers. I believe that the humanities can be a place
not just to think about things, but to do things. Doing, when done right, can
expand the scope of our critical activity, it can prepare our students for work
in the world, and finally, (and this despite the protestations of some) doing
can enact meaningful change in our universities, our libraries, and our
communities.[^1] I write, then, being inspired by the work of Matt Ratto
(Critical Making Lab, University of Toronto), Garnet Hertz (Concept Lab, UC
Irvine), Jeffrey Schnapp (metaLab, Harvard University), and many others who
routinely engage with material culture as a matter of scholarly practice.
Besides talking and writing papers, the students in my courses create models,
curate exhibitions, file patents, convene conferences, write grant
applications, send letters to the senate, build, sculpt, and code.

Understood in the context of the university at large, the Digital Humanities
(DH) movement can---and must, as I will argue here---be seen as part of the
"computational turn" altering the course of all major disciplines: see
computational biology, computational linguistics, computational social science,
computational chemistry, and so on. In general agreement with Geoffrey
Rockwell, Stephen Ramsey,[^2] and William J. Turkel[^3] I believe programming
to be an important methodological apparatus for the advancement of the
humanities: a set of tools and methods that can extend and supplement the
traditional research activities of a historian, a literary scholar, or a
philosopher.

But in this essay, I would like to temper some of the enthusiasm behind blunt
instrumentalism (of a certain kind) in the DH community, this with the hopes of
focusing our efforts and to mitigate a measure of criticism directed against
the discipline.[^4] I make a case here against the prevalent and often
fetishized concern with making tools: software, apps, and web services. A
related thesis, but one that is more difficult to articulate succinctly, is
aimed at the confusion between tools and methods---a confusion both subtle and
pervasive in the practices of the emerging humanities.

I will take it as a matter of shared knowledge and intuition that the first
wave of DH was defined, to a large extent, by tools and tool making.[^5] A
cursory look at the list of recent NEH Digital Humanities Start-Up grantees
shows that the majority of the funded projects involve a tool-making
component.[^6] Serving as an interface (literally) between the discipline and
the public, tools have the allure bringing the humanities out of the ivory
tower and into the world, moving from the merely theoretical to the applied,
the creative, and the agile. For those frustrated with the solipsistic excesses
of high theory, with its contentious distinctions and large personalities,
tool-making offered an activity that is collaborative, inclusive, and
interdisciplinary, not by words alone but also in action.

But the warm glow of several bright success stories which illuminates the
pragmatics of the struggle for ever-diminishing resources can also obscure a
field littered with the corpses of abandonware. For every Zotero there are
dozens of obscure projects, representing hundreds of hours spent writing grants
and developing software. Even in failure (by conventional standards) these
projects are an important part of progress and innovation.[^7] Much can be
learned from them. One of the most important lessons for me is that the
university is a uniquely terrible place to develop software. I offer the
following from an incomplete list as to the reasons why:

1. Software is easy (cheap and fun) to build relative to the difficulty
(expense and drudgery) of maintenance. "90% of coding is debugging. The other
10% is writing bugs."[^8] The adage comes naturally to most program managers
and software engineers, but not to faculty, administrators, or graduate
students. Our teaching, our support structures, and our attention spans are
finite rather than cyclical: articles are published, interest wanes, funding
dries up, students graduate. Software remains: a living and breathing thing. It
needs constant care and much more of it as code matures. Standards change,
dependencies break, platforms decay, customers need support. The case for the
humanities as a laboratory for innovation is strong, but I doubt that anyone is
prepared to make "critical customer support" a part of our teaching or research
experience. Departments, labs, libraries, and institutes are not well equipped
to deal with the long-term vagrancies of maintaining software.

2. If you build it, they might not come at all. Startups know that beyond the
initial excitement of a product launch (and the accompanying media buzz), the
challenge of any new app or web service is acquiring and retaining users, no
matter how "disruptive" or "innovative" the technology. Just having a useful,
or even a disruptively paradigm-shifting tool does not guarantee that anyone
will use it. I have been working with a brilliant French developer on the next
generation of distributed translation service called *traduwiki.com* for
several years now. Despite his skills and dedication to the project, the
website has not gained significant traction among translators or language
students. No amount of innovative engineering or web design can guarantee
participation.

3. Tools make us lazy. Tools make us lazy because they obscure methodology. The
*nltk.cluster* module bundled in Python's *NLTK* library[^9] contains an
implementation of something called "k-means clustering."[^10] The algorithm is
numerical, unsupervised, non-deterministic and iterative.[^11] To use it well
we need to have a way of estimating a number of expected clusters (that's the
*k* variable). The algorithm produces non-hierarchical results and being
non-deterministic, the clusters will vary with each iteration. Both the E-M and
the GAA clusterers, also included in the module, could be better suited for the
task at hand (in some hypothetical example). These remarks would be impossible
to glean from the software package itself, without reading the cited
methodological literature. Even at the Python library level, where code is
transparent, the methodology remains obscured by the implementation.
Intellectually, one would be remiss to draw insight from the tool without
understanding the underlying methodological complexity.

Despite being incredibly useful for research, software analytical packages like
*Gephi*, *Sci2*, or *Paper Machines*  further obscure the methodology, wrapping
the language-specific implementation of the algorithm in a layer of
application-specific idiosyncrasies. Without deep understanding of the
underlying methods, one can never be sure whether the observed results are real
(in some sense of the word) or merely unintended artifacts of the nested
implementation. Black-box technology used in such a way cannot withstand
critical scrutiny.

4. Out-of-the-box tools are easy to learn and use, but they are a bad
investment of time in the long term. Methodologies improve over time.  Tools
proliferate and decline in quality relative to the researcher's experience.
Reviewing the academic literature on k-means clustering at its lowest "raw"
level initially could be a tedious and labor-intensive affair. Not being a
statistician, I cannot always follow the math. But, in looking at a number of
articles in several related fields I am able to understand the uses and the
limitations of the algorithm. This knowledge is independent of implementation.
If tomorrow's research community moves from Python to Haskell (for example), the
applied methods will transfer with the language.

Learning the methodology properly is initially expensive, but is, ultimately, a
more lasting and more portable investment of time. Learning to code is not for
everybody. Using *NLTK* to parse and *D3.js* to visualize data is certainly
more difficult than using *wordle.com* to do the same on some rudimentary
level. But making wordle-like shortcuts to knowledge also promotes lazy
research, quickly obsolescent and difficult to share. It encourages our
students and our colleagues to skip methodology and go straight to the results.
By contrast, speaking R or Python enables us to speak to a wide audience, to
share methods, to receive support from and to share findings with a diverse
community of practitioners. My worry is that without addressing these concerns
we are in danger of becoming a bubble industry: expansionary and expensive, but
ultimately vacuous and prone to bursting.

To avoid such fate, we need to first look to sustainable models of software
development. That means taking seriously the "data management plan" part of
that grant---a plan which could include spin-offs, start-ups, non-profits, and
other unconventional (for the humanities) modes of scholarly production. These
could expand the experimental and exploratory activities of a lab beyond the
university's limited (and already overburdened) administrative structures.

Second, the emphasis of innovation should be on nurturing communities rather on
building tools. Hacking stuff is good, but better yet we need to hack our
cultures and our institutions. A new publishing platform, for example, does
little to solve the problems with the current publishing regime. The difficulty
lies in convincing our peers to read and to write differently. It is in the way
we cite, in our program requirements, and in the way train librarians and
graduate students. Building communities means striking a delicate balance
between disruption and continuance. Much can be learned from the success of the
open source and free culture movements in this regard.[^12] Take for example
the story of *Wikipedia* and *MediaWiki*. *MediaWiki*, the software platform
powering *Wikipedia*, was neither the first, nor the most technically
interesting wiki software package. But in the hands of Wikipedians, it became
something capable of transforming the contemporary information landscape.
Wikipedia struck the right balance between traditional forms of
knowledge-making (the encyclopedia) and innovative editorial structures
(commons-based peer production).[^13] I am therefore inspired by *Wikipedia*
the community, not *MediaWiki* the tool.

Finally, the emphasis on community-building leads us to standards and best
practices. Rather than more tools, we need initiatives that promote
methodological and not just instrumental innovation: humanities-based
alternatives to associations like the *Society for Political Methodology and
the International Association of Legal Methodology*; journals like
*Sociological Methods & Research*, *Journal of Mixed Methods Research*,
*International Journal of Qualitative Methods*; prizes and funding
opportunities like the *Political Methodology Career Achievement and Emerging
Scholars Awards*, or the *Program for Promoting Methodological Innovation in
Humanities and Social Sciences* run by the Japan Society for the Promotion of
Science. To sharpen our tools we must return to methodology: to formulate
common questions, to take it more seriously in our training, and to give it
more room in our debates and publications.

DH cannot survive alone, in isolation from similar movements in other fields.
The concern with data processing and computation, the availability of large
datasets, and cheap processing power have brought a number of disciplines
closer to each other, in a way that elicits much intellectual excitement. But
to actually make fireworks together, we need to operate the same incendiary
equipment. That is to say that finding strings within the human genome could
have some interesting applications to mining the *Gutenberg Project* and the
other way around. Biologists, linguists, economists, and sociologists
increasingly integrate their methodologies, as evidenced by a vigorous
cross-disciplinary publishing record. The computational turn sweeping all forms
of knowledge is enabled by common toolsets, by collective methodological
assumptions, and through shared standards of academic exposition (clarity,
concision, and reproducibility).[^14] DH is primed to join that conversation,
but only if its conceptual apparatus does not evolve along the old binary
categories, which lead to isolation and irrelevance. Working as a digital
humanist or a new media scholar means taking on extra responsibilities: to do
well by theory when doing theory, to be expert historians when building
archives, to make things that last when making things, and to do good science
when doing science.

[^1]: See: Fish, Stanley. *Save the World on Your Own Time*. Oxford
    University Press, USA, 2008.

[^2]: Ramsay, Stephen, and Geoffrey Rockwell. “Developing Things: Notes
    toward an Epistemology of Building in the Digital Humanities.” In
    *Debates in the Digital Humanities*, ed. Matthew Gold. Minneapolis:
    Univ Of Minnesota Press, 2012.

[^3]: See for example: Elliott, D, R MacDougall, and W.J Turkel. “New
    Old Things: Fabrication, Physical Computing, and Experiment in
    Historical Practice.” *Canadian Journal of Communication* 37, no. 1
    (2012): 121–128.

[^4]: For our favorite (and most persistent) interlocutor see Fish,
    Stanley. “Mind Your P’s and B’s: The Digital Humanities and
    Interpretation.” *The New York Times Opinionator*. Accessed December
    14, 2012.
    http://opinionator.blogs.nytimes.com/2012/01/23/mind-your-ps-and-bs-the-digital-humanities-and-interpretation/.

[^5]: See Unsworth, John. “Scholarly Primitives: What Methods Do
    Humanities Researchers Have in Common, and How Might Our Tools
    Reflect This?” King’s College, London, 2000 as part of part of a
    symposium on Humanities Computing: Formal Methods, Experimental
    Practice.
    http://people.lis.illinois.edu/\~unsworth//Kings.5-00/primitives.html.

[^6]: http://www.neh.gov/divisions/odh/grant-news/videos-2012-digital-humanities-start-grantees

[^7]: William Pannapacker has written eloquently on the topic in the
    Chronicle of Higher Education. See “Pannapacker From MLA: The
    Success of ‘Failure’” *The Chronicle of Higher Education*. From the
    Archives: Brainstorm, January 7, 2011.
    http://chronicle.com/blogs/brainstorm/pannapacker-from-mla-failure-is-the-new-normal/30864.

[^8]: The quote is commonly attributed to Bram Cohen, the creator of
    BitTorrent, posted on tweeter.com in 2011. There are however
    numerous earlier instances of the exact quote, itself a variation of
    Sturgeon's Law coined by Theodore Sturgeon (the American science
    fiction writer) in a 1957 article for *Venture* magazine and cited
    as such in the Oxford English Dictionary.

[^9]: Bird, Steven, Ewan Klein, and Edward Loper. *Natural language
    processing with Python*. Cambridge [Mass.]: O’Reilly, 2009.

[^10]: MacQueen, J. “Some Methods for Classification and Analysis of
    Multivariate Observations.” In *Proc. Fifth Berkeley Sympos. Math.
    Statist. and Probability* (Berkeley, Calif., 1965/66), Vol. I:
    Statistics, pp. 281–297. Berkeley, Calif.: Univ. California Press,
    1967. http://www.ams.org/mathscinet-getitem?mr=0214227.

[^11]: Na, Shi, Liu Xumin, and Guan Yong. “Research on K-means
    Clustering Algorithm: An Improved K-means Clustering Algorithm.” In
    2*010 Third International Symposium on Intelligent Information
    Technology and Security Informatics* (IITSI), 63 –67, 2010.

[^12]: See for example Weber, Steven. *The Success of Open Source*.
    Harvard University Press, 2005.

[^13]: A point made by Benjamin Mako Hill in his *Almost Wikipedia: What
    eight early online collaborative encyclopedia projects reveal about
    the mechanisms of collective action*, summarized in a recent talk at
    the Berkman Center for Internet and Society, abstract and
    transcripts available at
    http://cyber.law.harvard.edu/events/luncheon/2011/10/makohill.
    Another good summary by Garber, Megan. “The Contribution Conundrum:
    Why Did Wikipedia Succeed While Other Encyclopedias Failed?” Nieman
    Journalism Lab. Accessed December 22, 2012.
    http://www.niemanlab.org/2011/10/the-contribution-conundrum-why-did-wikipedia-succeed-while-other-encyclopedias-failed/.

[^14]: Witness the communities aroudn arxiv.org and PLOS ONE.
