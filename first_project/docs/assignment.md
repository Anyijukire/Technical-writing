TECHNICAL DOCUMENTATION TOOLS IN MKDOCS

Bit.ai. Bit.ai is new-age documentation and knowledge management tool that provides a common workplace for technical writers to collaborate, document, track and share their knowledge, brainstorm ideas, store digital assets, and innovate together. Unlike standard Notepad, MS Word, and Google Docs, Bit documents are interactive. This means, whether your team is creating technical documentation, training manuals, technical specs sheet, best practices, product catalogs, etc., they can easily add code blocks, training videos, and presentations directly into a Bit document within seconds.

Adobe FrameMaker Adobe FrameMaker is a sophisticated document processor that suites large industrial standard documentation. It can be used to generate structured documents with an XML framework that’s 100% Darwin Information Typing Architecture (DITA) compliant. FrameMaker is a DITA-friendly technical writing tool with the built-in ability to print a PDF and a great alternative to editors like MS Word. Additionally, documents created with FrameMaker span over 200+ pages with pre-defined templates in several industrial standard formats – such as financial statements and legal agreements. You can also generate automatic hyperlinks, a list of figures, a table of contents, and a list of tables in just a few clicks.

ProProfs Knowledge Base This tool is beautifully used to meet the demands of businesses all over the globe, it helps you create a company-wide knowledge platform, more like a manual, that can be easily accessed via multiple devices, including mobile phones, tablets, and laptops. ProProfs offer compelling features, such as MS Word-like editor, Google-like search functionality, workflows, customization options, and more, merged to provide you an ultra-modern experience. It even facilitates minute tasks like adding text to multiple pages at a go, adding your firm’s logo, creating toggle content.

Snagit They are used for screenshots with various attributes like- frames, arrows, circles, etc. These elements help readers to understand images in a simple and faster way!

MarkdownPad MarkdownPad is one of the most popular Markdown document editors used by technical writers. It provides a lot of customizations like fonts, color schemes, sizes, and layouts. It even has a built-in CSS editor and supports your custom CSS stylesheets.

Whatfix. This technical writing tool allows you to create compelling guides and help articles, presented in the form of real-time interactive walkthrough elements.

THEMES IN MKDOCS

1.Custom theme. Used to create cohesive branding.Furthermore, a distinct design can also help your site stand out from competitors.

2.Basic theme. This determines the colours, borders, shadows, size, and shape of individual elements on the screen.

3.MkDocs Windmill. It helps retains the state of the menu of pages and folders across page transitions, by keeping navigation to an iframe. It also implements a versatile search, featuring term highlighting, and both a quick dropdown and a full-page option that allows the user to come back to search results

4.MkDocs Alabster. It consist of; 1.extra.logo. Relative path to a logo image, which will appear in the upper left corner above the name of the project.

2.extra.logo_name. Set to true to insert your site's project name under the logo image as text. Useful if your logo doesn't include the project name itself. Defaults to false.

3.extra.logo_title. Logo's title attribute has a Default: your site_name. 4.extra.include_toc. Boolean, whether to include TOC in sidebar navigation or not. Default: false.

5.extra.extra_nav_links. 6.extra.show_powered_by. Show “Powered by” message, mentioning MkDocs and this theme. Default: true.

5.MkDocs Material. It provides extensible keyboard navigation and semantic markup including role attributes and landmarks. Modern architecture — Material for MkDocs's underlying codebase is built on top of TypeScript, RxJS, and SCSS, bringing excellent possibilities for theme extension and customization.

MKDOCS SYNTAX.

1.File layout. Your documentation source should be written as regular Markdown files,and placed in the documentation directory. By default, this directory will be named docs and will exist at the top level of your project, alongside the mkdocs.yml configuration file.

2.Index pages When a directory is requested, by default, most web servers will return an index file contained within that directory if one exists. For that reason, the homepage in all of the examples above has been named index.md, which MkDocs will render to index.html when building the site.

3.Configure Pages and Navigation The nav configuration setting in your mkdocs.yml file defines which pages are included in the global site navigation menu as well as the structure of that menu. If not provided, the navigation will be automatically created by discovering all the Markdown files in the documentation directory.

4.Writing with Markdown MkDocs pages must be authored in Markdown, a lightweight markup language which results in easy-to-read, easy-to-write plain text documents that can be converted to valid HTML documents in a predictable manner.

5.Internal links MkDocs allows you to interlink your documentation by using regular Markdown links.

6.Linking to images and media. As well as the Markdown source files, you can also include other file types in your documentation, which will be copied across when generating your documentation site.

py import this print("Please document syntax highlighting in mkdocs")