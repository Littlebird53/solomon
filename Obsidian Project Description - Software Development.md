---
publish: "true"
---

# General Description in Plain Language
I need something that will accomplish several different external functions all possible with a very similar database structure. The use cases are: (1) a curated collection of educational resources suitable for general student and instructor research, (2) a guided syllabus designer which coaches the user to construct a syllabus by selecting resources from a variety of categories according to a predetermined process and a set of appropriately tagged learning objects, and (3) a system for managing program documentation (operations manual, software documentation) and educational resources that supports multiple versions of the same core documents which differ based on intended context and language.

I believe an Obsidian vault can accommodate all of these needed features with the appropriate modifications.

# Function-Specific Descriptions
## Library Portal
#### Problems 
ADVANCE Students can access the GS Library (library.gs.edu) but there are a few pain points around:
1. **Account Access,** 
	- Creating accounts for ADVANCE students/instructors is not automated, 
	- requires email addresses, 
	- automated account logout is frequent and 
	- does not transfer across the various connections within the library system.
2. **Locating Resources, 
	- The library site search is not unified
	- easy-to-use, 
	- or translatable. 
	- Metadata fields are generally pre-determined and 
	- cannot be modified in bulk for specific purposes.
3. **and the Static Nature of the Collection.** 
	- Customized ADVANCE syllabi, videos, teaching resources, and other files cannot be uploaded to the library collection,
	- existing, irrelevant collection items cannot be removed/hidden,
	- the collection only includes formally published works, and
	- physical holdings are almost entirely irrelevant and unable to be easily hidden, and
	- static files require maintaining a separate database of editable versions which are modified, exported, and uploaded separately
#### Solutions Desired
I want an online repository that is:
- a collection curated by ADVANCE for ADVANCE students,
	- the power to edit/add/remove any individual resources must lie with ADVANCE admin staff
	- collections that serve subsections of ADVANCE students should be easily located by those students, without cluttering the interface for others
	- Center leaders must be able to (1) upload their own resources for use within their center immediately, 
	- (2) elect to submit resources for broader ADVANCE use, 
	- (3) create & edit collections of resources for use among their students and in their courses
- capable of displaying all kinds of records, 
	- pdf, markdown, .docx, images, charts, graphs, audio recordings, video, embedded forms/sites, and other links
	- respect varying copyright permissions and access
- which is frictionless, intuitive, stable, and accessible for all students
	- seamless bi-directional integration with JOSEPH accounts
	- user-interface that supports help text and animations
	- includes a unified search feature
	- uses teaching-centered metadata for easy student & instructor navigation
	- extensive linking to provide natural, integrated movement between relevant resources
	- browser access (no download required)
	- view/edit permissions controlled by account type (guest, student, instructor, etc.)
	- provides spatial & visual aids to collection exploration
	- online viewer & convenient download options for offline access
	- student/instructor account preferences should influence resource visibility by default, without requiring filters to be set on each search, upon each login
- and increases resource management effectiveness 500x.
	- metadata import/export
	- specific and hierarchical linking for pushing edits and identifying dependencies
	- data-rich admin environment for troubleshooting, reporting, and optimization
	- native file editing without recourse to a backup master file residing outside the system
	- full resource linter support
	- extensive version control and project forking through Git

- student comments/feedback?
## Syllabus Builder
#### Problems
1. Current syllabi templates only represent 1 modality for teaching a course
	- templates are built around in-person course meetings 1x/week, 3 hours, for 15 weeks
	- our centers teaching in a variety of schedules and modalities including:
		- shorter/longer semesters, 
		- more, shorter weekly meetings, 
		- weekend or intensive course meetings, 
		- in-person/online/hybrid, 
		- instructor-led lecture, discussion, facilitation, independent study, field mentorship,
		- varying levels of academic expectation
		- and technological access/ability
2. Current syllabi template translation is exponentially labor intensive
3. Nomenclature, formatting, learning objectives, and citations are not consistent, nor collected in a single location for convenient and regular maintenance
4. Syllabi approval is handled entirely manually, despite largely being a formulaic process
5. Syllabi content for students is not easily separated from instructions provided to instructors to guide their course design
6. Course schedules are standalone documents, requiring arduous navigation between mandatory course elements, especially multimedia ones
7. Modifications to syllabi go through the same approval process annually
8. Individual syllabi modifications are not tracked in any systematic way, preventing detailed analysis of teaching patterns across the program
#### Solutions Desired
We need a syllabus designer tool which:
- guides instructors through the modular construction of their syllabus
	- allows instructors to chose from various templates for each course based on their specific instructional, cultural, and linguistic context
	- clearly communicates different course schedule options
	- assembles and modifies individual sub-elements, rather than a complete syllabus
	- presents suggested learning activity options at key points throughout the course in accordance with available data about instructor, center, and student preferences
	- allows complete course customization by instructor, or template use
	- calculates the work hours of included assignments as modifications are made and
	- visually presents a workhour profile of each course
- incorporating and contributing to pre-approved and customizable course elements,
	- identifies whether specified required criteria match or require manual review
	- saves previous course designs by instructors as templates
	- allows submission of learning activity descriptions by instructors for broader use
	- allows sharing approved, customized syllabi templates among center staff
- which simultaneously results in an integrated, student-ready document
	- produces a cloud-based, linked document, as well as downloadable, discreet files
	- allows easy calendar integration for students and instructors based on final course design
		- creates ical files for due dates?
		- creates a Google calendar and invites them to add it?
		- enables automatic template reminders from the system with basic assignment metadata
- and a rich source of teaching data for academic oversight & evaluation
	- can systematically analyze syllabi design to provide key data for administrative oversight and program direction
	-  centralizes standardized elements for unified modification

- student comments/feedback?

## Documentation Manager
Most of the problems faced and the solutions desired at this point have already been address, but extending previous solutions beyond the teaching process also improves the operations/administration side of ADVANCE.
#### Problems
We are facing issues with
1. **translation,** 
	- Translation of forms, operational documents, syllabi (as previously mentioned), and teaching resources does not scale.
2. **ease of use,**
	- Operational documents, training resources, demo videos, etc. are not easily integrated into JOSEPH and the other functions of ADVANCE, leading to more emails/calls directly to the ADVANCE office than necessary.
3. **labor-intensive maintenance, and**
	- updating all links, prices, policies, and other changes is labor-intensive and often leads to missed changes, confusion, and broken links. Process is also needlessly repetitive.
4. **big picture program documentation.**
	- the internal manual for running ADVANCE is far from complete but has become significantly more complex
	- internal job manuals are notoriously out-of-date because they are out-of-sight, out-of-mind, and never integrated with workflows/changes. We need to fix the problem and the underlying causes.
	- the specifics of JOSEPH and other systems need to be documented in a better format for future ADVANCE or IT staff, in a post-Bryce & Daniel world
#### Solutions Desired
We need a system that
- connects all translations to a master document in the most localized/precise manner possible (sentence? at least, paragraph)
- auto-translation of changes in master doc to be published immediately following pushed English changes
- flagging auto-translated text for review by translator roles, generally current users (center staff) selected for upgraded permissions
- collates different selections of material from a main, overarching document into another, audience or task-specific one
- links FAQ/support info to the locations needed to support use directly and conveniently
- specifies a system-wide glossary of help text within certain folders/groups/types of content
- search help-base through multiple question aliases, keywords, etc.
- integrates images, code snippets and links with visual support to grasp dense concepts and important ideas, critical warnings, etc.
- a notification system which requests documentation update following relevant updates to the code base (like [ReadtheDocs](https://app.readthedocs.org/dashboard/), Docusaurus, etc.)
- how-to access limited by account type (guest, student, instructor, admin) without requiring the creation and management of separate documents
- 

# Draft Database Structure
I think all of the metadata required, file formats, links, notes, etc. can be handled in an Obsidian vault. This will provide




# Contract Matters
- price
- schedule
- tech-support


# Related Software
## Possibly Helpful
#### Translation Stuff
- [Weblate](https://weblate.org/en/): manages translations and integrates with ReadtheDocs, free for libre projects
- ReadtheDocs: flags need for documentation update with repo commits, also free for libre projects. Info on localization [here](https://docs.readthedocs.com/platform/stable/localization.html)
- [Sphinx](https://www.sphinx-doc.org/en/master/usage/advanced/intl.html): ReadtheDocs builds on this, or Docusaurus, MKDocs, etc. 
- [Obsidian to Sphinx](https://github.com/MacqGit/sphinx-obsidian): helps convert between the two, if needed
- [dj-polyglot](https://www.reddit.com/r/django/comments/1kc1vyd/i_opensourced_a_po_file_management_system_for/): open-source .po file management system for django. Links may all be broken??
- [Okrand](https://github.com/boxed/okrand): another django translation option.
- [Django Translation Manager](https://pypi.org/project/django-translation-manager/): as stated.
- [Django CMS](https://www.django-cms.org/en/blog/2026/03/31/automating-translations-with-django-cms-and-deepl/): a headless, content-management system (CMS) that supports other translation plugins.
- [Default Django page on translation](https://docs.djangoproject.com/en/6.0/topics/i18n/translation/):
#### Obsidian Plugins
- [ZettelFlow](https://community.obsidian.md/plugins/zettelflow): a huge collection of features including an interactive workflow coach VERY similar to what I want for syllabus builder. Allows "derived projects" which may support features like LongForm, in-folder organization. Vault health dashboards that calculate orphans, connectivity, weekly progress reports, tracks "knowledge-debt", MOC builder (doesn't do everything some want, but I'm not sure right now which we need), 3-D knowledge map, evidence map that sorts relationships by for/against, etc.
- [Astro Theme](https://github.com/aitorllj93/astro-theme-spaceship): for making vault a static website, using Astro & TailwindCSS
- [Track Changes](https://community.obsidian.md/plugins/track-changes): for accepting/rejecting suggestions directly in markdown
- [Longform](https://community.obsidian.md/plugins/longform): for arranging other notes within a larger project via tabs and in manually set order (not alphanumeric, etc.). Could allow for arranging the different activities of a class across different tabs for units, weeks, etc. 
- [Apex Dashboard](https://community.obsidian.md/plugins/apex-dashboard): could collect different classes in a single view, plus writing projects/assignments, calendar with due dates, and includes a Pomodoro timer and other relevant tools. Could probably also design a custom banner using a stable URL with different images, but ADVANCE or instructor gets to set the text in the image for announcements
- [Screen.Garden](https://screen.garden/): a collaborative tool built to make Obsidian compete with Google Docs. Shutting down Sept. 01, 2026 and open-sourcing all the code. They cite some frustration dealing with Obsidian code which might be worth looking at, but the collaborative functionality would be super important to look at. They say currently the code requires AWS hosting but that could be changed.
- [Vault CMS](https://vaultcms.org/): makes Obsidian into a Content Management System for Astro-built websites. Includes the Bases CMS plugin which allows bulk edit of properties used for publishing, draft, etc.
- [Quizzable](https://community.obsidian.md/plugins/quizzable): allows interactive quizzes to be created and played in Obsidian. May send results somewhere else using an API. Def needs a nicer way to edit/make quizzes but could have some useful stuff.
- [CBT-Exam](https://community.obsidian.md/plugins/cbt-exam): creates interactive, timed quizes with smart review, score history, flagged for review, and other features.
- [LearnKit](https://community.obsidian.md/plugins/learnkit): a variety of features for study, spaced-review, flashcards, tests, workflows, etc. Also uses optional AI-chatbot assistant.
- [Unseen Changes Dot](https://community.obsidian.md/plugins/unseen-changes-dot): adds colored dot to files that were updated since last opened. Would demonstrate how to flag changes since last view and could be leveraged for tracking translation changes. -- Might also be nice if I could flag changed paragraphs in documentation files for center staff.
- 
#### Biblical Language Tools
- ???: Whatever necessary to make mouse-over Greek/Hebrew parsing work.
- [Torah Verse Inserter](https://community.obsidian.md/plugins/torah-verse-inserter): inserts BH text with nikkud, allows search via Hebrew text or Latinized version, supports on-screen BH keyboard. Uses "Miqra according to the Masorah" text, from Aleppo Codex via Sefaria. Translations from Sefaria.
- [Blur](https://community.obsidian.md/plugins/blur): to hide text and reveal it on mouse-over.
- [YouVersion Linker](https://community.obsidian.md/plugins/youversion-linker): one example of automatically linking or quoting verses from a set source.
- [Diacritics-Free Search](https://github.com/spenhos/obsidian-diacritics-free-search): useful for allowing different searches with Hebrew/Greek text
- [Bible Search](https://community.obsidian.md/plugins/bible-search): public domain Bible text readable, cross-references, Bible maps, church history family tree, some Greek/Hebrew support (details unknown), 
- [The Scripture Injecter](https://community.obsidian.md/plugins/the-scripture-injector): Inserts Bible text as callout, supports ESV if you request your own API key (5000 requests/day)
- [RTL Support](https://community.obsidian.md/plugins/obsidian-rtl): sets individual documents to LTR/RTL.
- [Wordbook Layout](https://community.obsidian.md/plugins/wordbook-layout): not entirely sure but for vocab lists
- [Makarios Studio](https://community.obsidian.md/plugins/makarios-studio): smart book mapper, auto-complete verse references, side-by-side Bible versions, 
#### In Use 
(just don't interfere with these, might be able to incorporate)
- Breadcrumbs:
- Cornell Marginalia:
- Omnisearch:
- Dataview
- Charts View
- Charted Roots
- Share Note
- Maps / Leaflet / Map View: see partial comparison [here](https://esm7.github.io/obsidian-map-view/vs-obsidian-maps.html).
- Citations
- Templater
- Tag Wrangler
- Possible to upload ADVANCE logo in every vault, see [here](https://tfthacker.com/experiment-vault-logo).
- Speech Kit: allows natural, speech-to-text
- Handwriting:
- Story Line: could be rigged for super creative maps, graphs, views between learning activities, objectives, resources, etc. -- FOR SYLLABUS BUILDER
- Single File Section Cards: allows viewing each header of a document in a spatial, card, view with edit and rearrange power. Can make kanban boards within a single note, rather than as separate things. -- This could come in handy for other projects where we don't have to create separate notes, but I expect separate files is good most of the time.
- Lazy Loader: delays plugin loading to make the main program load quicker
- Mermaid Tools / Kroki / : markdown diagram tools, not sure which is best. Don't seem to offer easy editing (w/o accessing source code) which would be great for centers. Static (pdf, svg, etc.) and component export would be great.
- Slideshow: 
- Flash Cards: 
- Excalibrain: mindmap tool using links from notes, replaces Breadcrumbs
- Callout Tracker: collect matching type callouts in a single list while preserving their location throughout the note, e.g. for discussion questions, research topics, definitions, big ideas, etc. // Super helpful!
- Mix Folders and Files: allow sorting equally by name.
- : document conversion tools
- Note Toolbar: customizable toolbar within notes for easy shortcuts and clickable options. A more robust set of clickable, visual options would make editing graphs, tables, slides, etc. easier for centers. Context-aware.
- Periodic Calendar: could be used for journals for TFE
- Tabs: allow displaying note material in tabs for examples, more content without scrolling, hide/reveal options, tab alternation between different queries/bases like a switch or for comparison
- Find Unlinked Files: for identifying unlinked, broken links, orphans, etc.
- CosmoGraph 3D: replaces the unbounded canvas of OEM Graph view with a planet shape which limits total surface area. Groups notes by folders (wouldn't work for Zettelkasten). Creates arbitrary but permanent geographic features on the planet to aid spatial memorization -- need to replace this with something else but the idea is huge!
- Waypoint: automatically create/update a Map-of-Content (MOC) based on folders, adds folders to graph view, but allows treating folders differently by specification. Waypoints all things to appear in folders or as-if in folders they don't actually live in. -- THIS would actually work for Zettelkasten. Also, folders nest unlike tags and properties (type/subtype)
- JustFTables / Structural Tables / Advanced Tables: allows merging cells in tables
- Creases: allows designated collapses outside of heading levels and auto-collapsing on command
- Hover Editor: allows preview-editing
- Dragger: allow drag/drop paragraphs, blocks, etc.
- Tracker: creates visual graphs/charts from queries across your vault -- great for visualizing occurences of learning objectives, type of activities, course/reading distributions, etc.
- Metaedit: allow bulk editing properties, selection from list, hide certain properties, 
- Update modified date: self-explanatory
- Vault Changelog: self-explanatory
- Time Things: records time spent editing each doc
- Pomodoro Timer:
- Full Calendar Remastered: syncs with Google Calendar and CalDAV, also pulls from journals and daily notes, ICS files, and more. 
- Yearly Glance: annual calendar view for events only. -- Could be helpful for office planning.
- Goto Position: creates a short-cut for top or bottom of page. -- Useful for docs with navigation/structure at the top, or when jumping to backlinks maybe?
- Authorship Tracker: 
- Wizard: inserts text/choices directly into the note, which is directly editable after the wizard is completed. -- SYLLABUS BUILDER!
- Knowledge Regression: allows specifying tests for the vault that must pass or an error is thrown. Can identify broken links, orphans, etc.
- Fold Properties by Default: 
- Markdown Chat Blocks: for creating artificial conversations, make speaker tracking clear, simulated dialogues, responses, etc.
- Living Mindmap / Canvas From Headings: turns headers into editable mindmaps 
- Ribbon Groups: allows grouping ribbon buttons, adding colors, labels, etc.
- Colorful Folders:
- Pandoc Plugin: 
- Omni Book Reader: optimized epub reader environment, could replace default embedded pdf viewer to remember reading position, table of contents, page/scroll reading, bookmarks, notes attached to highlights
- Paper PDF Translator: AI-assisted format-aware translation for academic papers
- Virtual Footer: put results of dataview/bases at the bottom or other window of notes
- 

