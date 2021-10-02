Technical documentation tool available are: 1.Bit.ai - It is new-age documentation and knowledge management tool that provides a common workplace for technical writers to collaborate, document, track and share their knowledge, brainstorm ideas, store digital assets, and innovate together. Bit documents are interactive. It has a sleek, minimal, and distraction-free editor making it great for technical writing.

Adobe FrameMaker- It suites large industrial standard documentation. FrameMaker is a DITA-friendly technical writing tool with the built-in ability to print a PDF and a great alternative to editors like MS Word. documents created with FrameMaker span over 200+ pages with pre-defined templates in several industrial standard formats – such as financial statements and legal agreements. You can also generate automatic hyperlinks, a list of figures, a table of contents, and a list of tables in just a few clicks.
3.ProProfs knowledge Base - It is an excellent technical writing tool that provides amazing features and smart settings to help you create technical documents that reflect perfection. ProProfs offer compelling features, such as MS Word-like editor, Google-like search functionality, workflows, customization options, and more, merged to provide you an ultra-modern experience. It even facilitates minute tasks like adding text to multiple pages at a go, adding your firm’s logo, creating toggle content, etc.

4.Snagit - It offers a collection of beautiful pre-made elements along with the functionality of taking screenshots. It ensures consistency and professionalism.

5.Markdown- It provides a lot of customizations like fonts, color schemes, sizes, and layouts. It even has a built-in CSS editor and supports your custom CSS stylesheets. Users can quickly convert their written text documents into HTML or even export them as PDFs. With quick HTML previews, users can easily see what their documents

6.Whatfix - This technical writing tool allows you to create compelling guides and help articles, presented in the form of real-time interactive walkthrough elements. Whatfix automatically adapts the help guide based on the device you use. And the same help content can be accessed in other formats – as a video, slideshow, or PDF.

Themes in Mkdocs: 1.Cinder- It is a clean, responsive theme for static documentation sites that are generated with MkDocs.It's built on the Bootstrap framework and includes pre-packaged syntax highlighting (highlight. js), icons ( FontAwesome), and a smashingly legible type scheme to get your message out to your users.

2.Cluster -It is an open-source tool designed to manage cloud native infrastructures with simple declarative manifests - infrastructure templates.

3.docSkimmer -It is a skimmable minimal theme for static documentation sites built using MkDocs.

4.Material - Material for MkDocs is built on top of TypeScript, RxJS and SASS, and uses a lean, custom build process to put everything together.

5.ReadTheDocsDropdown - 6.Windmill - It focuses on clean usable navigation for large documentation projects. It retains the state of the menu of pages and folders across page transitions, by keeping navigation to an iframe. It has a dark theme called Windmill Dark -

7.Windmill Dark - 8.Custom Mill - Convenient navigation for larger documentation projects. Retains state of the navigation menu across page transitions. Deep nesting of documentation folders.

9.Bootstrap- 10.Bootstrap386

11.Psinder - It is a clean, responsive PowerShell-inspired MkDocs static documentation site generator theme -forked with love from Chris Simpkins' Cinder. It's built on the Bootstrap framework and includes pre-packaged syntax highlighting (highlight.js), icons ( FontAwesome), and a theme based on PSReadLine's default colors for a PowerShell console-themed documentation site.

12.Bootstrap4 13.GitBook Theme - 14.Ivory Theme

Mkdocs syntax Your project homepage should be named index.md Some of the file extensions for your Markdown source files include : markdown, mdown,mkdn, mkd,md. These files are rendered in the built site regardless of the settings. Files and docs with names which begin with a dot for example .index.md are ignored by Mkdocs. You can create multi-page documentation by creating several markdown files ,for example: docs/ index.md about.md license.md The file layout you use determine the URLS that will be generated for the different pages, for example: / /about/ /license/ You can include your markdown files in nested directories ,for example: docs/ index.md user-guide/getting-started.md Source files inside nested directories will cause pages to be generated with nested URLS ,for example: / /user-guide/getting-started/ Any files that are not identified as Markdown files,are copied by Mkdocs to the built site unaltered. Mkdocs renders the homepage named index.md to index.html when the site is being built. MkDocs will allow you to name your index pages as README.md instead of index.md. In that way, when users are browsing your source code, the repository host can display the index page of that directory as it is a README file. However, when MkDocs renders your site, the file will be renamed to index.html so that the server will serve it as a proper index file. The nav configuration setting in your mkdocs.yml file defines which pages are included in the global site navigation menu as well as the structure of that menu. A navigation looks like this: nav: - 'index.md' - 'about.md'