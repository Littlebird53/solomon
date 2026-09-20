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



- Breadcrumbs:
- Cornell Marginalia:
- Omnisearch:
- Dataview
- Charts View
- Charted Roots: allow genealogy-style tree display, charted movements on maps, and timeline creation. VERY cool and VERY useful for lots of different activities.; a simpler version is Grafily which only draws trees.
- Share Note
- Maps / Leaflet / Map View: see partial comparison [here](https://esm7.github.io/obsidian-map-view/vs-obsidian-maps.html).
- Citations
- Templater
- Tag Wrangler

#### Other Relevant
- Possible to upload ADVANCE logo in every vault, see [here](https://tfthacker.com/experiment-vault-logo).
- Speech Kit: allows natural, speech-to-text
- Handwriting:
- Story Line: could be rigged for super creative maps, graphs, views between learning activities, objectives, resources, etc. -- FOR SYLLABUS BUILDER
- Folder Nodes: makes each folder a "node" with the other files represented graphically inside it as projects, albums, etc. Can view spatially or linearly (like a MOC). An option for organizing content conceptually, mind-map like, while also allowing different groupings. Since this is neither perfectly sequential (task-oriented) or conceptual (mind map), it might be best used for curriculum, rather than course or concept mapping.
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
- Tracker: creates visual graphs/charts from queries across your vault -- great for visualizing occurrences of learning objectives, type of activities, course/reading distributions, etc.
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
- Vault Badge:
- Variable Links: allows linking to an unspecified object which is defined only once, e.g. like LaTex's /ref{John2020}
- Imagine / Gallery Hub / Image Layouts / : 
- Supercharged Links: format links differently based on the metadata of the notes. Could be used to supplement formatting differences of the names with emojis without complicating file names but wouldn't appear in the navigation bar... -- Pretty sure Ilya Shabanov uses this.
- Commander: allows modifying commands, setting macros, etc. within the hamburger and other default menus of Obsidian
- Multi Properties: allows editing properties across entire folders, etc. Bulk edit.
- Front Matter Title: allows setting a display name that does not change the underlying file name. Could be useful for auto-named but not disambiguated files, duplicated versions separated by ID#, timestamp, or other computer-oriented metadata
- Neighboring Files: allows easy arrow key and other navigation to move up, down, earlier, later, or other movements within the folder. Could be useful for sequential files in courses, chapters of pdfs, compare/contrast, or grading assignments. Could be wrapped into a button at the bottom of each page that says "Go to next page"
- Grid Explorer: allows searching and scrolling notes, images, pdfs, and other files in a full grid, or grid-preview list. Could make a library book shelf but would need to compare with card view in Bases. -- I guess it doesn't need to be the results of a query and might display non-notes if I have pdfs without sidecar notes... Book covers, learning activity options, persons/organizations for research topics...
- Influx: add context, and smart default and customizable sorting of backlinks
- Colored Bases Properties:
- Badges: sort of combo emoji+label things that look like colored tags I guess. Has been replaced by "Inline Callouts" -- Add to list of all formatting options to sort out their uses. 
- Wikilink Types: allows editing YAML relationships like those used in Breadcrumbs from the link by following it with @ and choosing from a list of kinds of links/relationships, e.g. supersedes, contradicts, supports, alternative, etc.
- Juggl: extends local graph towards a canvas view, allowing edge types, images, CSS formatting control and other features. Represents graph in text form in a note. Not exactly sure where the line between graph and canvas is here, but perhaps local graph is basically canvas where the contents is the result of a Base. -- This could allow the course graph to update automatically just by having the instructor link new documents to another aspect of the course (a week/class meeting note would be easy, but other major topics could work too)
- Typewrite Mode: combines a bunch of writing focus tools: Hemingway mode, typewriter scroll, active line highlight, minimal toolbar, etc. -- Could be useful for our admin side or instructor authoring, possibly for students who find digital writing difficult.
- Consistent Attachment & Links / Better Markdown Links / Advanced Rename and Delete Handler / Custom Attachment Location: prevents links to attachments from breaking inside Obsidian and outside it, automatically names and places attachment files in a folder next to the note and moves them as the note is moved. Some features of Consistent Attachment & Links were phased out and replaced with other plugins. ==(This author maintains a bunch of different Obsidian tools [here](https://github.com/mnaoumov/obsidian-resources))==
- Obsidian Auto Link Title: pulls webpage title using the link and displays instead of link text
- Obsidian Link Embed: not sure what this does that iframe cannot. Also this approach seems to be limited to the use limits of free APIs. See also: Obsidian Rich Links for a less robust option that still provides some preview info, and Auto Card Link for a VERY similar option.
- Image Captions: allows formattable captions for images alongside alignment or resizing, plus supports links, auto-naming from file name with regex modifications/exclusions. -- Might be easiest to import captions as file names and do this.
- Pretty Properties: allows adding banner images, color-coding properties, setting date color based on today's date or relative measure (deadline), supports quick search for properties, hiding properties, progress bar
- Dynamic Views: allows more flexibility in Bases card view, with variable length/width, text preview, wrap titles, property preview, change how images display/interact with text (thumbnail, background, etc), allow card shuffle randomizer, clickable check-box from Bases view, 
- Notebook Navigator: allows pinning files in folders, hide/reveal notes in subfolders, preview other files in folder or by shared tag in an additional side pane, allows keyboard navigation of sidebars, allow drag/drop changing properties as if they are folders, navigation side bar is also BOOLEAN operator search query (ctrl + click to combine searches), set sort order by folder, allows creating "group headers" within a folder to organize & allows expand/collapse which can display sum word-counts, folder notes (MOC) can display in sidebar, includes calendar, folder/note icons and colors, copy/paste folder style to tags, extensive customizable views in nav sidebar, allows "vault profiles" which are pseudo-vaults inside a vault,  -- Separate file and folder panes allows easier moving files into folders. Could add linked learning objects to a search option in the first pane, allowing easy toolbar (non-note) navigation between related assignments. You could make the course a series of nested folders for each week, which could be viewed as an unified scroll of files from beginning to end, with a visible status color that tracks progress and (?) auto-open the first incomplete file? Sidebar folder notes could easily auto-display cheat-sheets/guides
- TTRPG Tools - Maps: make an image a zoomable map and add pointers, markers, etc. -- Could create an artificial geography for ministry fields and map topics, schools of thought, etc. on it to aid navigation. Could also create a map for the parts of a class like a journey, or depart the free movement and just plot markers on a pyramid or other more directional graph like a simple road or branching tree. -- Can I just upload a canvas background image and embed notes themselves? Does canvas auto resize or is it always unbounded in ways that limit this? -- Windrose MD is a much more involved map designer using hex/cell structure, overlays, pre-set images, fog, terrain, multiple levels of design, etc. Probably overkill for us, but good to keep in mind.
- Image Layouts: allows masonry, multi-column, and other ways of displaying images (within a note?) including links, captions, text overlay, etc. -- 
- Iconoir Icons: allows inserting and modifying various icons in callouts, headers, tables, text, etc.
- Colored Tags
- Tags Overview: creates a new sidebar menu that allows sorting, filtering, searching across tags and properties -- this feature is baked inside Notebook Navigator but would be super helpful for letting people find things without having to write a new query in Bases for everything and without anticipating all of the searches they might want
- Tag Folder: self-explanatory but need to think more deeply about the purpose. This could allow effectively locating the same note in many different places, which could be handy. A primary location could be determined by type, with lots of other locations are useful/relevant. The actual location in a fake folder creates multiple paths to spatial location, but duplicates functionality already present in search with tags as they are. Bc spatial locations might be easier for people, this could be worth while.
- Portals: allows pinning folder trees or tags to a quick-access sidebar with color, icon, order and other formatting. -- could be useful to make certain MOC or directory files easy to find. Could create different profiles for students, instructors, etc.
- Flexplorer: adds pinning, hiding, custom sort, and drag-and-drop movement within folders -- this is a feature from Longform that I want, but in a much simpler approach.
- Multi Properties: bulk edit properties
- File Tree Alternative: separates folders/files in different panes like Evernote & Notebook Navigator
- Bases CMS: combine Dynamic Views & Multi-Properties into a CMS spin on Bases. see Vault CMS earlier.
- NosyGraph: build graphs in canvas from properties, LinkType notes, and Bases. Supports typed edges, expandable links, groups, etc. Still in BETA. -- Could easily provide another way of navigating resources without any additional configuration from existing Bases and can display nuanced additional information through formatting of colors, border types/shapes, etc. This could better display multiple/complex relationships between assignments, learning objectives, course schedules, etc. than a straight list with items appearing in multiple places each.
- Linksmith Pro: suggest links to notes and headings as you type and find missing links. -- Has a lot of ability to fine-tune suggestions to match needs. Would be very useful for admin side work.
- Better Links: allows modifying links and link display text in a pop-over window like in other editors, rather than having both appear in normal syntax
- Draw Steel Rule Term Linker: builds a glossary for pre-determined words so they always link to the master doc and provide relevant definitions and other info -- is a basic glossary demonstration. Not sure I need this to be limited to certain words though.
- Draw Steel Elements: very advanced TTRPG plugin that supports wizard negotiation functions, tracking party members, fight participants, etc.
- Books and Comics Tracker / Global Book Search / Easy Bookshelf / Book Search + Covers / Book Tracker / Library Shelf / ISBN Bulk Import Bookshelf Builder / Tome / Ebook Library / Shelf / : search ISBN, Google Books, Open Library and download covers, total series/episode reading progress, duplicate detection
- Lorebase: card-view media library with overlaid badges and hover previews, includes nice statistics page, 
- Linked Data Vocabularies: add Library of Congress Subject Headings as metadata!
- SideCard: creates a sidebar card view from tabs (notes, pdf, images) for easy movement between multiple notes with some open in tab view and some in card. Inspired by Heptabase. -- Possibly could make reference cards visible like the Notebook Navigator's folder note, but not sure when we would need multiple and when default multi-tasking/split windows wouldn't work.
- Scholar: downloads pdf from a link and creates a sidecar note with metadata, integrates with Semantic Scholar via API, pairs with PDF++ for annotations
- Researcher Library: 
- RSS Dashboard: could I just use this for notifications? Link the ADVANCE YouTube page or Vimeo? Create a dummy/private blog somewhere that sends posts here?
- OCR AI: turns pdf into markdown! uses Marker or MistralAI, promises to handle formulas, images, auto place material in the folder with a shared name, batch processing
- Yanki: integration with Anki flashcards
- Tome Connector: integrates with Tome server for TTRPG tracking. Creates notes, campaigns, encounters, records, etc. and prints into 1 big pdf file. -- IDRK what Tome is but this is starting to get close to my "Seminary Skyrim" idea as it tracks class, XP, quests, etc.
- Awesome Image / Pixel Perfect Image / Imagine : image management plugins, view all links/embeds of images, insert images in coverless notes, insert inline images among text for a textbook-style view!, image annotation
- Lottie: plays Lottie animations like images, insert .json just like anything else, specify size, renderer, etc. -- How do I even make small animations like this?
- Property Suggester Enhanced: allow creating rules that limit what values a property can take, better guidance for selecting properties -- something like this is what I want for building a course template from some intro questions, e.g. if "
- Datacore: query and render Mk notes 2-10 faster using an index an React based JavaScript API
- Vault in Vault: add password lock to files -- comparable to permissions in Obsidian?
- Simple Reminder: create reminders with dates, ranges, recurring, nag mode, etc.
- Window Title: allows changing the title of windows in Obsidian but not renaming files, saving windows, etc...? Allows setting 1 format for vault and different windows inside that -- I'm not exactly certain what this does but being able to modify the design of windows based on their properties could be super useful as it would let us make custom windows for different types (courses, sources, learning activities, etc.) that would help users feel which mode they were in better
- Wikipedia: pulls the first section of Wikipedia for note titles, could be a decent default description
- Reference Map: seems to separate other links from citations using distinct syntax, displays only citation references in their own graph and verifies via various API options.
- Weave: spaced-repetition flash cards, FSRS6 spacing (?), create test questions, analytics, sync with Anki. Blends 3 plugins: Weave Deck, EPUB reader, and incremental reading. Some features only available for 1-time payment of Pro. Test banks.
- Weave Incremental Reading: allows scheduling and tracking reading -- could be nice for allowing students to build their own reading calendar
- PDF Scholia Scribe: uses a citation format when annotating pdfs with PDF++ rather than the usual link format. Allows annotating Google Docs or MS Word files. -- auto-Turabian footnotes for citations would be cool
- Scholia: imports pdf papers, converts to Markdown (only pre-OCRed files), creates a glossary and defines suspected key terms using AI, highlights key sentences using AI
- Scholar Quest: gamify academic work with XP & levels, milestones, tiered avatars, etc. Prefills level from ORCID iD or wizard completion
- Study Familiar: study gamification that awards the same XP for every ranking of learning, not more for greater levels of mastery which incentives exaggerating. Gain even more XP for downgrading your understanding. Suggests topics based on recency, # of dependent concepts, and more. Built in study sprint timer and review. Assign 3 random "daily quests", 
- Etymology Lookup / Etymology Multilingual: for demo of interaction with external dictionary
- Library Search: places an automatic search result next to each note when opened based on title, aliases, and select metadata; handles transliterated text, can extract ToC from Pdf to allow searching. Allows grouping search results by category/type, can search note titles, headings, callouts, properties, lists, or entire notes (slowest) -- this is like the "related plugins" result at the bottom of Obsidian plugin pages. Could be useful to aid serendipitous discovery of new resources. Could also quickly create finding aids from pdfs for our entire project.
- Advanced Graph View: for vaults with >5k notes, the default graph fails. This allows adding note access frequency, edit recency, link counts, folder, tag, cluster, and other data to shape node size, color, and glow. auto find orphans and dead-ends. Double click a node to see only its n-hop neighborhood (effectively, quick movement between big graph and local graph). Allows pinning notes in the graph for consistent location. Records movement within each AGV session, allowing you to relive your Wiki rabbit hole after the fact.
- European Law Lookup: opens a pop-up search bar with law names and text previews for easy insertion into notes with citation info. -- Not directly relevant, but this functionality is interesting.
- Sprint Familiar: a small wizard guides setting research sprint goals, then adds a timer, and follows up with a review that covers what you learned, links you added, claims you debunked, etc. Produces daily and weekly summaries of sprint results. Draws on epistemic notes approach which groups them by info status/reliability. -- Not sure if this uses AI but it could work manually by asking people to describe it in their own terms.
- Cite Wide: assigns unique hexcodes to every footnote so they can be managed vault-wide in a consistent fashion. -- This would allow separating citations from other links by making all citations be a hex code in a footnote, to allow queries of citations separately from other links that also allows management of single citation formats where just the page number can change. Possibly better than Link Types for citation tracking, but would need to cooperate to incorporate the different relationships of citations (support, contradict, develop, etc.)
- Lookalike: finds related notes by frequency of shared words -- could be useful for suggesting related notes to centers, could also help minimize reduplication for admin
- Narrative Provenance: tracks authorship, copyright, sources, verification status, etc. Based on a larger system for making sure rights are respected and interpretation does not become evidence or fact. -- Is mostly just metadata which we could create on our own.
- Social Network Analysis: performs more detailed analysis on graph view: eigenvector, closeness, PageRank, harmonic, etc.
- Discourse Graph: organizes all notes into types and logical relationships and then creates canvases that illustrate these using customizable graphics, e.g. Claim, Question, Source, Evidence; supports, develops, derivative of, opposes, etc.
- Entity Linker: connects topics in your notes to OpenAlex "concepts", or if none are available, to Wikipedia pages to provide a foundational layer of info and standardization in terms.
- Pseudonymizer Tool: designed for linguistics researchers, converts various file formats into markdown.
- Standing Questions: track open questions across your vault, suggest notes with possible answers
- Patina: scores notes "staleness" using 4 measures and ranks the most important ones for updates -- useful for admin 
- Markwhen: allows creating timelines -- great for Bible and other history
- Timeline: create vertical timelines within notes -- useful for smaller stuff probably, less visual, more text
- Radial Timeline: track chronological progression of many different events simultaneously, designed for tracking acts, scenes, plots, subplots, etc. in novels -- curriculum design? Could probably treat other things as visual status or type rather than concurrent event, but the radial probably does work for at least multiple time factors moving together, otherwise a bar graph or something else would work.
- Visual Feed: collects all images in vault in a single IG-style feed, or masonry Pinterest-style feed -- it seem some people use Obsidian to organize their professional photography images, with local file viewer this could work for IA at Gateway
- Campaignitz: creates interactive timeline for TTRPG - could be super useful for history activities and self-guided courses
- Grape Clusters: modifies graph to draw links within a folder bolder and closer -- wouldn't work for Zettelkasten, but could be useful for other stuff
- Relay: another live collaboration plugin, available for free self-hosting or monthly subscription fee with possible educational discount
- Vault Arcade: allows playing minesweeper, snake, 2048, and blocks in vault, saves high scores
- Release Timeline Base View: vertical timeline display in bases, allow click to open notes -- could actually display course elements if arranged correctly
- Merlay: adds a visual editor to Mermaid diagrams combining the ease-of-use of Canvas/Excalidraw diagrams, with the stable markdown structure of Mermaid diagrams. Also lighter than canvas packages.
- Properties to Graph: allows property-based grouping to graph -- could work where folder-based groups don't because of Zettelkasten
- In-place Diff View: 
- SQLite to Markdown: run SQLite in codeblocks using local SQL database, 
- CSV Table: display csv files as tables in Obsidian
- DataLoom: create Notion-style databases, format column data types, sort, reorder, import CSV, 
- Table to CSV Exporter: export .md tables to .csv
- CSV Editor: 
- Meld Encrypt: password encryption -- possible auto-satisfy based on user account access
- Bases Charts / Charts View: bar, scatter, line, multiple-charts from a single base, import from csv, radar, 
- Life Tracker: chart/data visualization plugin with new data visualization wizard -- could be useful for guided assignment creation. Can also pull goal creation from properties of various notes just like I need for the work hour calculation on syllabus builder.
- Bookshelf Base: book view with cover images, auto-generated spines for no cover books, etc.
- Dataview Serializer: converts dataview stuff into markdown so you can use with Obsidian Publish! 
- Note Village: creates a 2-D village with characters based on tags in your vault and allows them to speak about their expertise using AI, your avatar physically moves between parts of town
- Triggers: run Obsidian commands upon opening different files, folders, views, etc. -- auto change side-bar for each note type (assignments), 
- Sidebar Layouts: allows arranging multiple sidebars simultaneously at different orders, dimensions, etc. Allows moving without closing/reopening to preserve entered data
- Editor Breadcrumbs: displays the current file and header location within a note inside the editor for easy movement, styled like Windows File Explorer
- In-place Diff View: displays suggestions, corrections, edits, etc. as color-coded inside the note itself, with a pop-up to accept/reject changes. -- Useful for translation side, but want to display the master language parallel version too.
- Style Tweaker: no CSS style updates, live preview, 
- Contextual Typography: allows setting different style settings based on note properties so each font and visual feel fits the content of the note -- this might be a useful way to reinforce the different kinds of interactions available within The Solomon Project...
- Cursor Smith: adds various zany effects to the cursor
- Custom Font Loader: easily add different fonts
-  Class Timetable: auto create notes for each class meeting based on property value of class schedule and list each note on the calendar which displays in the sidebar. Opens the folders for a class when you click on it: assignments, class notes, readings, etc. Calendar also allows non-note schedules (like non-note insertions in canvas). 
- Inline Conversions: changes units to your preferred values, reveals original or alternate on hover -- Great for international contexts, but also could be cool for ancient units!
- Library Shelf: create a visual shelf of books without creating a note for each book, uses fenced YAML/JSON block // looks pretty nice and embeds inside notes well, which could be nice for bite-size book reccs for related content.
- Matrix List Planner: allows drag-and-drop editing of list-type properties across multiple notes, unassigned values live in their own space -- could be an interesting way to assign learning objectives and reveal which ones haven't been placed yet, but would need to support duplicate placement
- Trolls Printing Press: turns .md files into printable pdfs using various pre-sets for books, booklets, pamphlets, reference and index cards, brochures, etc. 
- Advanced Exclude: truly hide excluded notes from all areas -- needed for attachment files with sidecar notes?
- Alias Quick Switcher: allows searching aliases in file paths 
- Backlink Cache: speeds up backlink view, can be helpful for plugins that rely on this
- Backlink Full Path: for differentiating notes with the same name in different locations from the Backlink viewer
- Edit Link Alias: windowed option that works in reading view to avoid messing with link syntax, easier for keyboard navigation
- Email to Vault: create an email address to creates notes directly
- Embed HTML:
- External Rename Handler: updates links to external files when renamed outside of Obsidian as long as Obsidian is running during the rename 
- File Bundles: prevent moving related files (embedded images, note, form/submissions, etc.) separately
- Insert Multiple Attachments: allow batch selection of images to be inserted
- Link Picker: find notes to link by navigating folders rather than just fuzzy name searches, can create a command for linking into a common folder (e.g. source, learning objective) -- this could be really nice to make "Link Learning Objective" with guidance separate from "Link to Reading Material"
- Nested Properties: allows editing nested properties in properties viewer, not just YAML -- I didn't even know nested properties were a thing! Could be useful for different kinds of data validation within a single purpose for data, could group/simplify properties from getting too crazy...
- Smart Rename: does not change file names backwards but updates link to not disturb in-sentence links, sets original name as the display value and makes it an alias for the new note title
- Create Obsidian Plugin: wizard tool for modifying existing plugins for custom purposes
- Obsidian Dev Utils: 
- Base Path Updater: allow moving files from folder edits in Bases
- Dependent Properties: update/sync properties from a master doc to all children. E.g. Event links to location and places its location value as a separate property within the event note. -- might need to combine with link/relationship types to limit this, but could be really great so derivatives, responses, or examples all have the same topic, learning objectives, etc. Useful when the property of a linked note contains information that needs to be displayed in another note.
- Notelets (also, JS Engine): allow embedding HTML, CSS, and JavaScript directly in Markdown -- this could embed Loder's learning activities! Need to figure out how to make things editable, saved, logged, shareable, etc.
- Tab Candy: custom new tab landing page with recent files, bookmarks, clock, background, custom quotes, etc. -- I think this is part of what I was thinking a Home page would do...
- Auto Move File: move based on names or properties
- Media Recorder: allow video, audio, and screenshare capture directly in Obsidian for note demonstration and easy storage -- super easy for recording class/assignment instructions, easy for instructors using slides to record videos, 
- Media Extended: inserts timestamps for note from embedded video player, easy screenshot from video into notes, simplified play/pause hotkeys, create clickable timestamp notes for your own videos, -- super useful for aiding video lecture note taking, creating instructional videos, and more (most recent version is close source, previous versions are open-source)
- Chronobars: time-based progress bars, for traditional course completion
- Regen: gamified work balance, lose stamina points slowly, gain it by taking breaks and eating snacks
- Code Space: code editor in Obsidian
- Feed Bases: displays notes with editable text so you can scroll through all your notes and interact with them easily, for to-do's, maybe even a single view of all class activities without having to leave a note, 
- Bases Paginator: limits results on single page, add multiple pages
- Unique Suite: university toolkit with calendar integration, timetable, etc. (in Spanish)
- Custom Folder Links: wikilink to folders without creating folder notes, expands folder in nav sidebar and highlights it
- Story Map: product development and release timeline, project management; create categories of tasks broken down, assigned, described, ordered, etc.
- Dragon Glass: creates campaign and game indices for TTRPG, recognizes other user-created aspects according to various criteria and tracks them as well -- an enrollment index and class index styled like this could work great. All your classes display with some info, then every class meeting/unit with the class index, which could expand to include the activities of each week, drawn from any file placed in that folder
- Conflict Resolver: for sync conflicts
- Awesome Format Bar: like MS Word, 
- Rowbase: Notion-style databases, interactive, kanban, timeline, etc.
- ScrollStream: scroll 2 separate notes in tandem through linked headings -- like LOGOS feature for Bible versions
- Klomimory: language learning flashcard app that tracks attempts, success, etc.
- Repeat: review notes with periodic or spaced repetition
- Come Through: FSRS spaced repetition flashcards with simple syntax
- DND Wiki: autocomplete search tool that pulls formatted text from the DND Wiki page so you can search for level 1-3 fire damage spells for wizards, etc. -- Any source I would want I can probably put straight in Obsidian, but I would like to have a wizard for searching for relevant info. This works because the searcher knowns the terms and specifications they want to look for. Some conditions that might work for us like that would be grammar/parsing/vocab in biblical languages, definitions of specific terms (Church History dictionary with names, ideas, places, etc.), possibly assignment types could work this way, where the instructor searches for learning activity/resources in the midst of doing their own writing...?
- File Folder Status Icons: use traffic-light style emojis for folders based on properties -- not great for users, but could make publish status visible for admin // Probably, some minor alternation between prefixed logo is better and won't require a modification for the published version.
- HTML Gallery: browse all HTML files as a grid of live thumbnails, search by title/content, open notes that link to them! -- GREAT for hosting Loder's learning exercises & I think Geniallys can be saved as HTML too!
- Chapter Diff: compare current note version with previous Git commit side-by-side with highlighting -- needed for translation workflow!
- Wireframy: wire-frame (draft UI design elements) using template shapes, figures, designs, etc. and supports comments
- WordFolio: hover English words for definitions + pronunciation, add to vocab note with spaced repetition -- GREEK/HEBREW
- Ledge: customizable navigation dock (palette menu) that sits on top of every window; create up to 8 depending on the location, shortcuts, commands, auto-hide
- Note Hub: download/import folders of files into your vault from a shared community site
- Mobile-Translate: Google Translation, no API required
- Facet Folders: allows treating properties and tags like folders in a sidebar nav menu just like 1 part of Notebook Navigator
- File Name History: add previous file names to properties
- Foldable Frontmatter Groups: allows folding grouped properties to manage massive proliferation of properties with various plugins -- alternative to nested properties that doesn't require a surface-level property
- Markdown Trip Planner: in a trip code block add a start, stops, and a destination that each contain location, date, and descriptions. Displays in timeline view -- This could easily be the course structure with work hour calculation
- RPG Manager: extensive toolbox for TTRPG, uses HTML UI to guide editing of code block info in user-friendly way, manages nested locations, campaigns, scenes, characters, NPC & monster generation, etc. -- Lots of potential here. 
- TTRPG Tools - Soundboard: 
- Storyteller Suite: manage characters, locations, events, galleries, map, timeline, graph view, etc.
- Nested Ordered Numbering: gives 1.1. not just 1. on indented line
- Explorer Categories: allows formatting folders and notes together in similar ways -- can use for metadata-defined formatting without constraining folder location
- Resume Editor: form-driven document designer intended for non-markdown format -- this could be useful for making completion or recognition certificates (can I auto-fill instances of names/courses/instructors from JOSEPH?). 
- Fingerprint Lock: add fingerprint lock to vault for Mac/Windows, or hardware lock, or fallback password. Allows per-note locking and pulling keys from Web-Auth. -- Possible account permissions proof of concept. -- Technically, we could probably set up 3 different vaults which sync increasing portions of the master vault and just give everyone access to the correct one. This seems more complicated (having 3 mostly same vaults) but could work, and if the end-user vaults are really just selected portions of the Master vault, theoretically it could not increase work.
- Global Proxy: configure network proxies for users in areas with restricted networks
- Sync Engine: claims to be a super optimized syncing option for vaults that is way faster, incremental, indexed, etc.
- Obelisk: suggestion/comment plugin for collaborative editing but stores comments in the frontmatter so they live and move inside a single note
- Note Definitions: a personal dictionary that underlines defined words wherever it finds them and allows mouse-over reading the definition, plus you can add non-definition notes to each definition if there is ambiguity or discussion about things -- this could work for easy to read instructions as an alternative to linking
- Floating TOC: floating, clickable, cursor-aware highlighting table-of-contents; includes various tick-mark style indicators when minimized, 
- Mouse Navigation: hold right click and drag mouse to draw navigation gestures -- sorta like touchpad gestures or Apple mouse, is there a disability effect here?
- Brain Atlas: turns graph view into a 3-D shape, but a brain rather than a map. Allowing assigning tags/folders/properties to a zone of the brain for logical clustering. Also has a 2D version that keeps the clusters. -- also see, Cerebro Mycelium, for a fungus garden themed version that highlights recently edited files.
- Orrery: galaxy-themed 3D colored graph view with stars and nebula background
- Canvas Link to Group: allow linking to a group in a canvas, just like a header link -- This is super interesting idea! It could replace folder linking if I don't use folders and might be easier to navigate spatially than creating a note with vertically embedded options, p

Custom Calendar: can repurpose fantasy TTRPG calendar option to make each year a single note for church history, history of Bible, DSS, etc. courses 

- I should use "display title" workaround for file names to include colons, ?, and other punctuation not allowed in titles.

#### Non-obsidian
- Pengram ([here](https://github.com/penfieldlabs/pengram)): autoextracts logic structure and mindmaps from videos, papers, etc. -- same functionality as NotebookLM
- 

