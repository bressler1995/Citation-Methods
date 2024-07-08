## Citation Methods

Just a repository for testing different implementations of bibliography / citation on GitHub.

### Completely GitHub Based

Methods that leverage GitHub's native functionality.

- [All](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based)
- [Footnotes](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based/Footnotes)
- [Anchors](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based/Anchors)
- GitHub actions
  - There really wasn't any prebuilt options other than schema checkers for citation.cff files, and LaTeX compilers (LaTeX to PDF converters)
  - Technically a custom GitHub action could be written

### External Environments

Methods that leverage web technologies in an environment outside of GitHub.com, or are able to make use of GitHub pages.  

We'll not prioritize these as much since GitHub native ways are going to work better with existing content. Tests for these may materialize later.

- <a href="https://www.andrewheiss.com/blog/2023/01/09/syllabus-csl-pandoc/" target="_blank">Pandoc</a>
  - Pandoc flavored markdown (not supported natively on GitHub)
  - An interesting solution because Pandoc is also a conversion tool with support for many formats.  It could convert multiple formats to GitHub Markdown such as Pandoc flavored markdown, LaTeX, BibTeX
  - Many supported bibliography <a href="https://pandoc.org/chunkedhtml-demo/3.1-general-options.html" target="_blank">formats</a>
- Jekyll
  - Ruby based gems like [this one](https://github.com/inukshuk/jekyll-scholar).
    - Bib and BibTeX support
- MDX
  - Built for JS component frameworks like React, so a component based reference system can easily be implemented without too much setup
  - Can use anchor based method from GitHub based list
  - For example &lt;Citation ref='someref'/&gt;
- <a href="https://jupyterbook.org/en/stable/content/citations.html" target="_blank">JupyterBook</a>
  - Uses extensions to support BibTeX
- RMarkdown
  - Uses BibTeX
  - <a href="https://bookdown.org/yihui/rmarkdown-cookbook/bibliography.html">Documentation</a>
- LaTeX
  - Is its own Markup document format
  - Includes support for bibliography formats, aka BibTeX and BibLaTeX
  - Run in specific environments but some js trickery could be used to get it to run on the web
  - Pandoc can convert LaTeX into Markdown