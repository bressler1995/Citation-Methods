## Citation Methods

Just a repository for testing different implementations of bibliography / citation on GitHub.

### Completely GitHub Based

Methods that leverage GitHub's native functionality.

- [All](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based)
- [Footnotes (No central bib file)](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based/Footnotes)
- [Anchors](https://github.com/bressler1995/Citation-Methods/tree/GitHub-Based/Anchors)

### External Environments

Methods that leverage web technologies in an environment outside of GitHub.com or GitHub pages.  

We'll not prioritize these as much since GitHub native ways are going to work better with existing content. Tests for these may materialize later.

- <a href="https://www.andrewheiss.com/blog/2023/01/09/syllabus-csl-pandoc/" target="_blank">Pandoc</a>
  - Pandoc flavored markdown (not supported on GitHub)
  - Multiple 
  - But an interesting solution because Pandoc is also a conversion tool.  Couldn't it convert Pandoc Markdown to GitHub Markdown and carry over the link refs?
  - Many supported bibliography <a href="https://pandoc.org/chunkedhtml-demo/3.1-general-options.html" target="_blank">formats</a>
- Jekyll
  - Ruby based gems like [this one](https://github.com/inukshuk/jekyll-scholar).
    - Bib and Bibtex support
- MDX
  - Built on React, so a component based reference system can be implemented
- <a href="https://jupyterbook.org/en/stable/content/citations.html" target="_blank">JupyterBook</a>
  - Uses extensions to support Bibtext