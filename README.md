# Awesome LaTeX Tools

> A community-curated list of tools, web platforms and resources for writing, building and publishing documents with LaTeX.

LaTeX is a mature typesetting system with a large ecosystem: editors, engines, build tools, converters, linters, template collections, learning material and active communities. This list collects the useful parts in one place so you can find a tool for your task without searching through forum threads.

Entries are tagged by license model: `OSS` (open source), `Free` (free of charge, not open source), `Freemium` (free tier plus paid plans) and `Proprietary` (paid or closed). Please read the [contribution guidelines](CONTRIBUTING.md) before opening a pull request. Suggestions are welcome, including via a [new issue](https://github.com/PolyMarkup/awesome-latex-tools/issues/new/choose).

## Contents

- [Online Editors & Platforms](#online-editors--platforms) (15)
- [Desktop Editors & IDEs](#desktop-editors--ides) (27)
- [TeX Distributions & Docker Images](#tex-distributions--docker-images) (8)
- [Engines & Build Tools](#engines--build-tools) (17)
- [Modern Alternatives & Companions](#modern-alternatives--companions) (8)
- [Converters](#converters) (7)
- [Math, Equations & OCR](#math-equations--ocr) (14)
- [Tables](#tables) (6)
- [Diagrams, Plots & Graphics](#diagrams-plots--graphics) (22)
- [Linters, Formatters & Checkers](#linters-formatters--checkers) (11)
- [Bibliography](#bibliography) (15)
- [Templates & Document Classes](#templates--document-classes) (21)
- [Packages & CTAN Lookups](#packages--ctan-lookups) (22)
- [Learning Resources](#learning-resources) (17)
- [AI-Assisted Tools](#ai-assisted-tools) (4)
- [Communities & Forums](#communities--forums) (8)
- [Related Lists](#related-lists) (7)
- [Contributing](#contributing)
- [License](#license)

## Online Editors & Platforms

- [Big list of online LaTeX editors (TeX.SE)](https://tex.stackexchange.com/questions/3/compiling-documents-online) - Community-maintained comparison of online LaTeX editors and compilers. `Free`
- [CoCalc](https://cocalc.com) - Collaborative computational platform that includes a LaTeX editor with synchronized PDF preview alongside Jupyter and Linux terminals. `Freemium`
- [Fidus Writer](https://www.fiduswriter.org) - Open-source collaborative academic writing platform with citation management and LaTeX export. `OSS`
- [olcli](https://github.com/aloth/olcli) - Command-line interface to sync, manage and compile Overleaf projects from the terminal. `OSS`
- [Overleaf](https://www.overleaf.com) - Collaborative browser-based LaTeX editor with rich-text mode, Git integration, and a large template gallery. `Freemium`
- [Overleaf Community Edition](https://github.com/overleaf/overleaf) - Self-hostable open-source edition of Overleaf's editor and compiler. `OSS`
- [Overleaf Toolkit](https://github.com/overleaf/toolkit) - Official Docker-based tooling for deploying and managing a self-hosted Overleaf instance. `OSS`
- [Overleaf Workshop](https://github.com/iamhyc/Overleaf-Workshop) - VS Code extension for editing Overleaf projects from within the editor. `OSS`
- [Papeeria](https://papeeria.com) - Online LaTeX editor with Git integration, live preview and real-time collaboration. `Freemium`
- [Prism](https://prism.openai.com) - OpenAI's LaTeX workspace with real-time collaboration and built-in AI assistance. `Free`
- [SwiftLaTeX](https://github.com/SwiftLaTeX/SwiftLaTeX) - WebAssembly build of the XeTeX and pdfTeX engines for compiling LaTeX entirely in the browser. `OSS`
- [TeXLive.net](https://texlive.net) - Minimal online TeX Live compiler by DANTE e.V., used by LearnLaTeX.org and several forums. `Free`
- [TeXlyre](https://github.com/TeXlyre/texlyre) - Local-first LaTeX and Typst web editor with real-time collaboration and offline support. `OSS`
- [TeXPage](https://www.texpage.com) - Online LaTeX editor with real-time collaboration and a template library. `Freemium`
- [Typst Web App](https://typst.app) - Collaborative online editor for Typst, the modern LaTeX alternative. `Freemium`

## Desktop Editors & IDEs

### LaTeX-focused editors

- [BaKoMa TeX](https://www.bakoma-tex.com) - Commercial Windows TeX system with a WYSIWYG-style editing mode. `Proprietary`
- [Gummi](https://github.com/alexandervdm/gummi) - Lightweight LaTeX editor for Linux with live PDF preview as you type. `OSS`
- [Kile](https://kile.sourceforge.io) - KDE LaTeX editor with project management and auto-completion. `OSS`
- [LyX](https://www.lyx.org) - Document processor with a WYSIWYM interface that uses LaTeX for output. `OSS`
- [Oleafly](https://github.com/Oleafly/Oleafly) - Desktop editor for LaTeX, Typst and Markdown with live PDF preview, SyncTeX and bundled engines. `OSS`
- [Texifier](https://www.texifier.com) - LaTeX editor for macOS and iOS with project management and document sync. `Proprietary`
- [Texmaker](https://www.xm1math.net/texmaker/) - Cross-platform LaTeX editor with integrated PDF viewer and structure view. `OSS`
- [TeXnicCenter](https://www.texniccenter.org) - Windows LaTeX editor with project management and build profiles. `OSS`
- [Texpad](https://www.texpad.com) - LaTeX editor for macOS and iOS with live preview and Git support. `Proprietary`
- [Texpile](https://github.com/texpile/texpile) - Offline LaTeX and Typst editor with visual and source editing modes. `OSS`
- [TeXpresso](https://github.com/let-def/texpresso) - Live-rendering TeX previewer that re-typesets incrementally while you edit. `OSS`
- [TeXShop](https://pages.uoregon.edu/koch/texshop/) - macOS LaTeX editor and previewer, bundled with MacTeX. `OSS`
- [TeXstudio](https://www.texstudio.org) - Cross-platform LaTeX IDE with integrated PDF viewer, syntax highlighting and completion. `OSS`
- [TeXworks](https://www.tug.org/texworks/) - Lightweight cross-platform LaTeX editor with integrated PDF viewer, modeled after TeXShop. `OSS`
- [WinEdt](https://www.winedt.com) - Long-standing Windows text editor with extensive LaTeX support. `Proprietary`

### Editor plugins and IDE integrations

- [AUCTeX](https://www.gnu.org/software/auctex/) - Emacs package for writing and formatting TeX files, with preview and multi-file support. `OSS`
- [LaTeX Pro](https://jetplugins.dev/latex-pro/) - Commercial JetBrains IDE plugin with project-aware diagnostics, SyncTeX preview and bibliography tools. `Proprietary`
- [LaTeX Utilities](https://github.com/tecosaur/LaTeX-Utilities) - VS Code add-on for LaTeX Workshop with live math preview, word count and paste helpers. `OSS`
- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - Visual Studio Code extension with build recipes, PDF viewer, SyncTeX and IntelliSense. `OSS`
- [latex-devcontainer](https://github.com/a-nau/latex-devcontainer) - Dev container setup for compiling LaTeX in VS Code without a local TeX installation. `OSS`
- [LaTeXTools](https://github.com/SublimeText/LaTeXTools) - Sublime Text plugin for building, viewing and completing LaTeX documents. `OSS`
- [RefTeX](https://www.gnu.org/software/auctex/reftex.html) - Emacs package for managing labels, references, citations and indices. `OSS`
- [TeXiFy IDEA](https://github.com/Hannah-Sten/TeXiFy-IDEA) - LaTeX plugin for IntelliJ IDEA and other JetBrains IDEs. `OSS`
- [VimTeX](https://github.com/lervag/vimtex) - Vim and Neovim filetype plugin with compilation, completion, motions and text objects for LaTeX. `OSS`

### Language servers

- [Digestif](https://github.com/astoff/digestif) - Language server for LaTeX, ConTeXt and Texinfo written in Lua. `OSS`
- [LTeX+](https://github.com/ltex-plus/ltex-ls-plus) - Language server that checks grammar and spelling in LaTeX and Markdown via LanguageTool. `OSS`
- [TexLab](https://github.com/latex-lsp/texlab) - Language server for LaTeX and BibTeX with completion, navigation, rename and forward search. `OSS`

## TeX Distributions & Docker Images

### Distributions

- [MacTeX](https://www.tug.org/mactex/) - TeX Live distribution for macOS with additional Mac applications such as TeXShop. `OSS`
- [MiKTeX](https://miktex.org) - TeX distribution for Windows, macOS and Linux that installs packages on demand. `OSS`
- [proTeXt](https://www.tug.org/protext/) - Windows distribution based on MiKTeX with TeXstudio and installation guidance. `OSS`
- [TeX Live](https://www.tug.org/texlive/) - Comprehensive TeX distribution for GNU/Linux, macOS and Windows, updated annually. `OSS`
- [TinyTeX](https://yihui.org/tinytex/) - Lightweight, portable TeX Live-based distribution that installs packages on demand. `OSS`
- [tlmgr](https://www.tug.org/texlive/tlmgr.html) - TeX Live's package manager for installing, updating and inspecting packages. `OSS`

### Docker images

- [dante-ev/docker-texlive](https://github.com/dante-ev/docker-texlive) - Docker image with a full TeX Live plus Perl, Python and common tools preinstalled. `OSS`
- [Island of TeX TeX Live images](https://gitlab.com/islandoftex/images/texlive) - Maintained Docker images of TeX Live for local use and CI. `OSS`

## Engines & Build Tools

### Engines

- [ConTeXt](https://wiki.contextgarden.net) - TeX-based typesetting system with integrated layout and style control, usually run with LuaTeX. `OSS`
- [LaTeX Project](https://www.latex-project.org) - Home of the LaTeX kernel, news, documentation and issue tracker. `OSS`
- [LuaTeX](https://www.luatex.org) - Unicode engine with embedded Lua scripting; successor to pdfTeX. `OSS`
- [pdfTeX](https://www.tug.org/applications/pdftex/) - TeX engine that produces PDF output directly; the traditional default for LaTeX. `OSS`
- [SILE](https://sile-typesetter.org) - Lua-based typesetting engine inspired by TeX with modern Unicode and layout support. `OSS`
- [Tectonic](https://tectonic-typesetting.github.io) - Self-contained, XeTeX-based engine that fetches packages on demand and runs the right number of passes. `OSS`
- [XeTeX](https://tug.org/xetex/) - Unicode-aware engine with OpenType and system font support. `OSS`

### Build tools

- [Arara](https://github.com/islandoftex/arara) - Build tool driven by directives written in the document itself. `OSS`
- [arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner) - Cleans LaTeX sources (comments, unused files, image sizes) before arXiv submission. `OSS`
- [latexdiff](https://ctan.org/pkg/latexdiff) - Marks up differences between two LaTeX files, useful for revision tracking. `OSS`
- [latexmk](https://ctan.org/pkg/latexmk) - Perl script that automates running LaTeX, BibTeX/Biber and friends the necessary number of times. `OSS`
- [latexpand](https://gitlab.com/latexpand/latexpand) - Flattens a multi-file LaTeX project into a single file. `OSS`
- [latexrun](https://github.com/aclements/latexrun) - Run-LaTeX wrapper that handles reruns and filters the output down to the relevant messages. `OSS`

### CI and GitHub Actions

- [dante-ev/latex-action](https://github.com/dante-ev/latex-action) - DANTE e.V.'s GitHub Action for compiling LaTeX with a full TeX Live image. `OSS`
- [latex-action](https://github.com/xu-cheng/latex-action) - GitHub Action that compiles LaTeX documents with a configurable engine. `OSS`
- [setup-texlive-action](https://github.com/TeX-Live/setup-texlive-action) - Official GitHub Action that installs TeX Live on runners. `OSS`
- [texlive-action](https://github.com/xu-cheng/texlive-action) - GitHub Action for running arbitrary commands inside a TeX Live container. `OSS`

## Modern Alternatives & Companions

- [Asciidoctor PDF](https://github.com/asciidoctor/asciidoctor-pdf) - Converts AsciiDoc directly to PDF without going through LaTeX. `OSS`
- [Morph](https://github.com/PolyMarkup/morph) - Universal markup converter for Markdown, AsciiDoc, reStructuredText, Typst and LaTeX. `OSS`
- [MyST Markdown](https://mystmd.org) - Markdown-based authoring tools for scientific documents with LaTeX and Typst export. `OSS`
- [Quarto](https://quarto.org) - Scientific publishing system that renders Markdown and Jupyter/knitr documents to PDF via LaTeX or Typst, HTML and more. `OSS`
- [Tinymist](https://github.com/Myriad-Dreamin/tinymist) - Language server, formatter and previewer for Typst. `OSS`
- [Typst](https://typst.app) - Markup-based typesetting system with a fast compiler; web app is freemium. `Freemium`
- [Typst compiler](https://github.com/typst/typst) - Open-source Typst compiler and command-line tool. `OSS`
- [Typst Universe](https://typst.app/universe/) - Official directory of community Typst packages and templates. `Free`

## Converters

- [ar5iv](https://ar5iv.labs.arxiv.org) - HTML5 versions of arXiv papers generated from their LaTeX sources using LaTeXML. `Free`
- [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) - Pandoc LaTeX template for producing clean PDFs and handouts from Markdown. `OSS`
- [LaTeX.js](https://latex.js.org) - JavaScript library that translates LaTeX to HTML for use in the browser. `OSS`
- [LaTeXML](https://math.nist.gov/~BMiller/LaTeXML/) - Converts LaTeX to XML, HTML and EPUB; used by arXiv's HTML versions. `OSS`
- [MiTeX](https://github.com/mitex-rs/mitex) - Lets you use LaTeX math and commands inside Typst documents. `OSS`
- [Pandoc](https://pandoc.org) - Universal document converter supporting LaTeX, Markdown, Word, HTML and many other formats. `OSS`
- [TeX4ht](https://tug.org/tex4ht/) - Converts TeX and LaTeX documents to HTML, XML and other formats. `OSS`

## Math, Equations & OCR

### Equation editors and OCR

- [CodeCogs LaTeX Editor](https://editor.codecogs.com) - Online equation editor that renders LaTeX to images and embeddable links. `Free`
- [Detexify](https://detexify.kirelabs.org) - Draw a symbol and find the matching LaTeX command. `OSS`
- [KLatexFormula](https://klatexformula.sourceforge.io) - Desktop application that renders LaTeX formulas to images for use in other documents. `OSS`
- [LaTeX Equation Editor (Lagrida)](https://latexeditor.lagrida.com) - Online equation editor with live preview and a symbol palette. `Free`
- [LaTeXiT](https://www.chachatelier.fr/latexit/) - macOS application that turns LaTeX equations into PDF images you can drag into other apps. `OSS`
- [MathLive](https://github.com/arnog/mathlive) - Web component for editing math with a virtual keyboard and LaTeX input/output. `OSS`
- [Mathpix](https://mathpix.com) - OCR that converts images and PDFs of equations, tables and text into LaTeX. `Freemium`
- [pix2tex (LaTeX-OCR)](https://github.com/lukas-blecher/LaTeX-OCR) - Open-source vision-transformer model that converts equation images to LaTeX. `OSS`
- [SimpleTex](https://simpletex.cn/ai/latex_ocr) - Web-based formula recognition that converts images to LaTeX. `Freemium`

### Web math rendering

- [KaTeX](https://katex.org) - Fast math typesetting library for the web. `OSS`
- [MathJax](https://www.mathjax.org) - JavaScript display engine for LaTeX, MathML and AsciiMath in all browsers. `OSS`
- [Temml](https://temml.org) - Converts LaTeX math to native MathML for browsers. `OSS`

### Symbol references

- [Comprehensive LaTeX Symbol List](https://ctan.org/pkg/comprehensive) - Reference of thousands of symbols available in LaTeX. `OSS`
- [Short Math Guide for LaTeX](https://ctan.org/pkg/short-math-guide) - AMS quick reference for typesetting mathematics with amsmath. `Free`

## Tables

- [booktabs](https://ctan.org/pkg/booktabs) - Package for publication-quality table rules and spacing. `OSS`
- [Excel2LaTeX](https://ctan.org/pkg/excel2latex) - Excel add-in that converts selected cells to LaTeX tabular code. `OSS`
- [LaTeX Table Editor](https://www.latex-tables.com) - Online table editor with import from spreadsheets and LaTeX/CSV export. `Freemium`
- [pgfplotstable](https://ctan.org/pkg/pgfplotstable) - Package that typesets numeric tables from CSV and other data files with rounding and formatting. `OSS`
- [Tables Generator](https://www.tablesgenerator.com/latex_tables) - Online WYSIWYG table editor that generates LaTeX, Markdown and HTML. `Free`
- [tabularray](https://ctan.org/pkg/tabularray) - Modern table package with a key-value interface for complex layouts. `OSS`

## Diagrams, Plots & Graphics

### TikZ and PGF

- [CircuiTikZ](https://github.com/circuitikz/circuitikz) - LaTeX package for drawing electrical and electronic circuits. `OSS`
- [PGFPlots](https://ctan.org/pkg/pgfplots) - Package for publication-quality 2D and 3D plots built on TikZ. `OSS`
- [PGFPlots.net](https://pgfplots.net) - Gallery of PGFPlots examples. `Free`
- [PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet) - LaTeX templates for drawing neural network diagrams. `OSS`
- [TeXample.net](https://texample.net) - Gallery of TikZ examples with downloadable source code. `Free`
- [TikZ & PGF manual](https://tikz.dev) - Online edition of the PGF/TikZ manual. `Free`
- [TikZ & PGF on CTAN](https://ctan.org/pkg/pgf) - Portable graphics format with the TikZ front end for programmatic figures. `OSS`
- [tikz-feynman](https://github.com/JP-Ellis/tikz-feynman) - LaTeX package for drawing Feynman diagrams with TikZ. `OSS`
- [TikZ.net](https://tikz.net) - TikZ gallery with a focus on physics and full source code for each figure. `Free`

### Visual editors and converters

- [Asymptote](https://asymptote.sourceforge.io) - Vector graphics language with LaTeX integration for technical drawing. `OSS`
- [CircuiTikZ Designer](https://github.com/Circuit2TikZ/CircuiTikZ-Designer) - GUI for drawing circuits that exports CircuiTikZ code. `OSS`
- [DeTikZify](https://github.com/potamides/DeTikZify) - Research model that converts sketches and figures into TikZ programs. `OSS`
- [GeoGebra](https://www.geogebra.org) - Interactive geometry and math software that can export TikZ/PGF code. `Free`
- [IPE](https://ipe.otfried.org) - Vector drawing editor that typesets labels with LaTeX. `OSS`
- [LaTeXDraw](https://latexdraw.com) - Tutorials and resources for drawing in LaTeX, plus the vector drawing tool of the same name. `Free`
- [Mathcha](https://www.mathcha.io) - Online WYSIWYG editor for math and diagrams with TikZ and LaTeX export. `Freemium`
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz) - Converts MATLAB and Octave figures to TikZ/PGFPlots. `OSS`
- [quiver](https://q.uiver.app) - Web editor for commutative diagrams that exports tikz-cd code. `OSS`
- [svg2tikz](https://github.com/xyz2tex/svg2tikz) - Inkscape extension and CLI that convert SVG paths to TikZ/PGF. `OSS`
- [tikzcd-editor](https://github.com/yishn/tikzcd-editor) - Visual editor for tikz-cd commutative diagrams. `OSS`
- [TikZiT](https://tikzit.github.io) - GUI for drawing graphs and string diagrams as TikZ. `OSS`
- [tikzplotlib](https://github.com/nschloe/tikzplotlib) - Exports Matplotlib figures as TikZ/PGFPlots. `OSS`

## Linters, Formatters & Checkers

### Linters

- [blacktex](https://github.com/texworld/blacktex) - Command-line tool that fixes common LaTeX anti-patterns. `OSS`
- [ChkTeX](https://www.nongnu.org/chktex/) - Linter that reports typographic and syntactic errors in LaTeX documents. `OSS`
- [lacheck](https://ctan.org/pkg/lacheck) - Simple consistency checker for LaTeX documents. `OSS`
- [LanguageTool](https://languagetool.org) - Grammar and style checker with open-source core and editor integrations. `Freemium`
- [TeXtidote](https://github.com/sylvainhalle/textidote) - Spelling, grammar and style checker for LaTeX documents. `OSS`
- [Vale](https://github.com/errata-ai/vale) - Configurable prose linter that can process LaTeX through external converters. `OSS`

### Formatters

- [bibtex-tidy](https://github.com/FlamingTempura/bibtex-tidy) - Cleans and formats BibTeX files. `OSS`
- [latexindent](https://ctan.org/pkg/latexindent) - Perl script that indents and reformats LaTeX, configurable through YAML. `OSS`
- [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt) - Fast LaTeX formatter written in Rust. `OSS`
- [texcount](https://ctan.org/pkg/texcount) - Word counting script that understands LaTeX structure. `OSS`
- [texfot](https://ctan.org/pkg/texfot) - Filters TeX output so that only important warnings and errors are shown. `OSS`

## Bibliography

### Reference managers

- [Better BibTeX for Zotero](https://github.com/retorquere/zotero-better-bibtex) - Zotero plugin with stable citation keys and automatic .bib export. `OSS`
- [BibDesk](https://bibdesk.sourceforge.io) - macOS bibliography manager for BibTeX files. `OSS`
- [JabRef](https://www.jabref.org) - Cross-platform reference manager that uses BibTeX and BibLaTeX as its native format. `OSS`
- [Mendeley](https://www.mendeley.com) - Reference manager and PDF organizer that can export BibTeX. `Freemium`
- [Papis](https://github.com/papis/papis) - Command-line document and bibliography manager with a plugin system. `OSS`
- [Zotero](https://www.zotero.org) - Free reference manager that collects, organizes and exports citations including BibTeX. `OSS`

### Formats and engines

- [Biber](https://ctan.org/pkg/biber) - Backend processor for biblatex with sorting and Unicode support. `OSS`
- [biblatex](https://ctan.org/pkg/biblatex) - Flexible, Unicode-aware bibliography package with Biber as the backend. `OSS`
- [BibTeX](https://ctan.org/pkg/bibtex) - The classic bibliography processor and format for LaTeX. `OSS`
- [Citation Style Language](https://citationstyles.org) - Open XML-based format and style repository used by Zotero and Pandoc. `OSS`

### Lookups and cleanup

- [betterbib](https://github.com/texworld/betterbib) - Command-line tools for improving and syncing BibTeX files. `OSS`
- [DBLP](https://dblp.org) - Computer science bibliography with one-click BibTeX export. `Free`
- [doi2bib](https://www.doi2bib.org) - Converts a DOI, arXiv ID or PMID into a BibTeX entry. `Free`
- [rebiber](https://github.com/yuchenlin/rebiber) - Updates arXiv-based BibTeX entries with the official published versions. `OSS`
- [ZoteroBib](https://zbib.org) - Free web tool to build bibliographies and export BibTeX without an account. `Free`

## Templates & Document Classes

### Template galleries

- [LaTeX Templates](https://www.latextemplates.com) - Curated collection of templates for papers, theses, CVs, posters and presentations. `Free`
- [Overleaf Gallery](https://www.overleaf.com/latex/templates) - Large searchable collection of journal, thesis, CV and presentation templates. `Free`
- [Typst Universe templates](https://typst.app/universe/search/?kind=templates) - Official directory of community Typst templates. `Free`
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - Catalogue of community Beamer themes with previews. `Free`

### Document classes and templates

- [acmart](https://ctan.org/pkg/acmart) - Official class for ACM publications. `OSS`
- [arxiv-style](https://github.com/kourgeorge/arxiv-style) - Preprint template based on the NIPS style for arXiv submissions. `OSS`
- [Awesome-CV](https://github.com/posquit0/Awesome-CV) - LaTeX template for CVs and cover letters. `OSS`
- [Beamer](https://ctan.org/pkg/beamer) - The standard LaTeX class for presentations. `OSS`
- [classicthesis](https://ctan.org/pkg/classicthesis) - Typographic style for theses based on The Elements of Typographic Style. `OSS`
- [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) - Elegant LaTeX template for books and notes. `OSS`
- [IEEEtran](https://ctan.org/pkg/ieeetran) - Official class for IEEE Transactions and conference papers. `OSS`
- [kaobook](https://github.com/fmarotta/kaobook) - Book class with a large margin for notes and figures. `OSS`
- [KOMA-Script](https://ctan.org/pkg/koma-script) - Versatile classes and packages for European typography. `OSS`
- [latexcv](https://github.com/jankapunkt/latexcv) - Collection of CV and résumé templates in LaTeX. `OSS`
- [memoir](https://ctan.org/pkg/memoir) - Flexible class for books, reports and articles with built-in customization. `OSS`
- [metropolis](https://github.com/matze/mtheme) - Modern, minimalist Beamer theme. `OSS`
- [moderncv](https://ctan.org/pkg/moderncv) - Class for curricula vitae and cover letters with several styles. `OSS`
- [NOVAthesis](https://github.com/joaomlourenco/novathesis) - Template for dissertations adaptable to many universities. `OSS`
- [REVTeX](https://journals.aps.org/revtex) - LaTeX document preparation system for American Physical Society and AIP journals. `OSS`
- [tikzposter](https://ctan.org/pkg/tikzposter) - Class for creating scientific posters with TikZ. `OSS`
- [Tufte-LaTeX](https://github.com/Tufte-LaTeX/tufte-latex) - Document classes inspired by Edward Tufte's handouts and books. `OSS`

## Packages & CTAN Lookups

### Package archives and lookup

- [CTAN](https://ctan.org) - Comprehensive TeX Archive Network, the central repository for packages and documentation. `OSS`
- [CTAN Topics](https://ctan.org/topics/highscore) - Browse CTAN packages by subject. `Free`
- [LaTeX Font Catalogue](https://tug.org/FontCatalogue/) - Visual catalogue of fonts that can be used with LaTeX. `Free`
- [TeX Live documentation index](https://www.tug.org/texlive/Contents/live/doc.html) - Browsable index of documentation for packages and tools shipped with TeX Live. `Free`
- [TeX.world](https://tex.world) - Showcase and directory of TeX-related websites. `Free`
- [texdoc.org](https://texdoc.org) - Web interface to the texdoc utility for finding package documentation. `Free`

### Essential packages

- [algorithm2e](https://ctan.org/pkg/algorithm2e) - Environment for typesetting algorithms. `OSS`
- [amsmath](https://ctan.org/pkg/amsmath) - AMS mathematical typesetting enhancements. `OSS`
- [babel](https://ctan.org/pkg/babel) - Multilingual support and hyphenation. `OSS`
- [cleveref](https://ctan.org/pkg/cleveref) - Smart cross-references that infer the reference type. `OSS`
- [fontspec](https://ctan.org/pkg/fontspec) - Font selection for XeLaTeX and LuaLaTeX. `OSS`
- [geometry](https://ctan.org/pkg/geometry) - Flexible page layout and margins. `OSS`
- [glossaries](https://ctan.org/pkg/glossaries) - Glossaries, lists of symbols and acronyms. `OSS`
- [hyperref](https://ctan.org/pkg/hyperref) - Hyperlinks, PDF bookmarks and metadata. `OSS`
- [listings](https://ctan.org/pkg/listings) - Source code listings without external dependencies. `OSS`
- [mathtools](https://ctan.org/pkg/mathtools) - Extensions and fixes for amsmath. `OSS`
- [mhchem](https://ctan.org/pkg/mhchem) - Typesetting of chemical formulae and equations. `OSS`
- [microtype](https://ctan.org/pkg/microtype) - Subtle micro-typographic improvements such as protrusion and font expansion. `OSS`
- [minted](https://ctan.org/pkg/minted) - Syntax-highlighted source code using Pygments. `OSS`
- [siunitx](https://ctan.org/pkg/siunitx) - Typesetting of SI units and numbers. `OSS`
- [tcolorbox](https://ctan.org/pkg/tcolorbox) - Colored and framed text boxes with extensive customization. `OSS`
- [todonotes](https://ctan.org/pkg/todonotes) - Marks to-do notes in the margin or inline. `OSS`

## Learning Resources

### Tutorials and interactive

- [Dickimaw LaTeX resources](https://www.dickimaw-books.com/latexresources.html) - Overview of LaTeX books, tutorials and resources. `Free`
- [Gilles Castel: lecture notes with LaTeX and Vim](https://castel.dev/post/lecture-notes-1/) - Widely referenced write-up of a fast LaTeX note-taking workflow with Vim and UltiSnips. `Free`
- [LaTeX Cookbook](https://latex-cookbook.net) - Gallery of recipes and examples accompanying the LaTeX Cookbook. `Free`
- [LaTeX for Complete Novices](https://www.dickimaw-books.com/latex/novices/) - Beginner-friendly book by Nicola Talbot, free to read online. `Free`
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX) - Community-written, extensive LaTeX manual. `Free`
- [LearnLaTeX.org](https://www.learnlatex.org) - Browser-based interactive introduction to LaTeX with runnable examples. `OSS`
- [Overleaf Learn](https://www.overleaf.com/learn) - Extensive free tutorials and documentation on LaTeX topics. `Free`
- [TeXnique](https://texnique.xyz) - Typing game that tests how fast you can reproduce rendered formulas in LaTeX. `Free`

### Documentation and FAQs

- [LaTeX Project documentation](https://www.latex-project.org/help/documentation/) - Official guides, including the LaTeX2e for authors and class writers documentation. `Free`
- [LaTeX2e unofficial reference manual](https://latexref.xyz) - Community reference manual for LaTeX2e commands. `Free`
- [TeX by Topic](https://ctan.org/pkg/texbytopic) - Free book on the TeX language and its primitives by Victor Eijkhout. `Free`
- [TeX FAQ](https://texfaq.org) - International TeX FAQ, maintained on GitHub. `Free`
- [The Not So Short Introduction to LaTeX2e](https://ctan.org/pkg/lshort-english) - Classic free introduction to LaTeX. `Free`
- [TUGboat](https://tug.org/TUGboat/) - TeX Users Group journal with articles on typesetting and tool development. `Free`
- [Typst Documentation](https://typst.app/docs/) - Official tutorial and reference for Typst, useful when comparing with LaTeX. `Free`
- [Visual FAQ](https://ctan.org/pkg/visualfaq) - Typesetting issues illustrated with links to TeX FAQ answers. `Free`

### Cheat sheets

- [LaTeX Cheat Sheet (Winston Chang)](https://wch.github.io/latexsheet/) - Compact two-page reference of common commands. `Free`

## AI-Assisted Tools

AI features also appear elsewhere: see [Overleaf](#online-editors--platforms) and the OCR tools under [Math, Equations & OCR](#math-equations--ocr).

- [Nougat](https://github.com/facebookresearch/nougat) - Neural OCR model that converts scanned academic documents into a markup language. `OSS`
- [Overleaf AI Assist](https://www.overleaf.com/about/ai-features) - Overleaf's AI features for writing help and LaTeX error explanations. `Freemium`
- [Overleaf MCP](https://github.com/yangzichao/mcp-server-overleaf) - Local integration for AI assistants to edit and compile shared LaTeX projects in Overleaf with conflict checks before publishing. `OSS`
- [PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) - Translates scientific PDFs with formulas and layout preserved, using LLM or MT back ends. `OSS`
- [Writefull](https://www.writefull.com) - AI writing assistant for academic text with an Overleaf integration. `Freemium`

## Communities & Forums

### Q&A and forums

- [LaTeX.org Forum](https://latex.org) - International LaTeX forum. `Free`
- [r/LaTeX](https://www.reddit.com/r/LaTeX/) - Subreddit for LaTeX questions, showcases and discussion. `Free`
- [TeX Stack Exchange](https://tex.stackexchange.com) - Q&A site for TeX, LaTeX and related systems. `Free`
- [TeX.social](https://tex.social) - Aggregator and Mastodon instance for the TeX community. `Free`
- [TeXnique.fr](https://texnique.fr) - French-language TeX Q&A site. `Free`
- [TeXwelt.de](https://texwelt.de) - German-language TeX Q&A site. `Free`

### Organizations

- [DANTE e.V.](https://www.dante.de) - German-speaking TeX user group. `Free`
- [TeX Users Group (TUG)](https://tug.org) - International organization of TeX users with mailing lists and publications. `Free`

## Related Lists

- [awesome-LaTeX (egeerardyn)](https://github.com/egeerardyn/awesome-LaTeX) - Long-running general-purpose curated list of LaTeX resources. `Free`
- [awesome-latex-drawing](https://github.com/xinychen/awesome-latex-drawing) - Curated examples of academic drawing with LaTeX. `OSS`
- [awesome-markdown](https://github.com/BubuAnabelas/awesome-markdown) - Curated list of Markdown tools and resources. `Free`
- [awesome-scientific-writing](https://github.com/writing-resources/awesome-scientific-writing) - Tools and resources for scientific writing beyond LaTeX. `Free`
- [awesome-tikz](https://github.com/xiaohanyu/awesome-tikz) - Curated list of TikZ documentation, libraries and resources. `Free`
- [awesome-typst](https://github.com/qjcg/awesome-typst) - Curated links for Typst. `Free`
- [hantang/latex-templates](https://github.com/hantang/latex-templates) - Collection of LaTeX thesis and dissertation templates. `OSS`

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for inclusion criteria, the entry format and the pull request process.

## License

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE).
