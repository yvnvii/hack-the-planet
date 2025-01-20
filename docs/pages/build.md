---
---


# Course website dev notes


## Building this website

Clone the repo, which will also clone the revealjs submodule within.
```bash
git clone ...
```

Install mkdocs-material into your current environment.
```bash
conda install mkdocs-material -c conda-forge
```

Move into the repo directory and build locally with mkdocs
```bash
mkdocs serve
```


## Editing the site

Currently the old class structure is still present in the `old-docs` directory. Parts of this
can be updated and moved to the new `docs/` directory to be integrated into the new site. 

