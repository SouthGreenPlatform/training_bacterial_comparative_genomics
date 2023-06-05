# Welcome on the training Microbial Comparative Genomics github repository of the Southgreen Bioinformatics Platform

The course itself lives https://southgreenplatform.github.io/training_bacterial_comparative_genomics/, where you can find all the relevant information.

## For collaborators teachers and developers

This part is for collaborators-teachers and developers.

### Modify content

When you are in the repository, add and/or modify your markdown tutorials in the docs directory.
The arborescence of the website menu is to setup in the `mkdocs.yml` file

### Mkdocs

To generate the static web site.

#### Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).  
For full documentation about the [material mkdocs theme](https://squidfunk.github.io/mkdocs-material/).

#### Installation

##### Manual

As prerequisite you need python >=3.8 and pip.  

Install Mkdocs:

`pip install mkdocs`

For the theme:  
`pip install mkdocs-material`

For the extensions:  
`pip install pymdown-extensions`

For the plugins:  
`pip install mkdocs-minify-plugin`  
`pip install mkdocs-macros-plugin`

##### Conda

Clone the repository and move in it.  
Then install all dependencies using conda and the `conda_env.yml` shipped with this repo:

```
conda env create -f conda_env.yml
```

Activate the environment and you are good:

```
conda activate education
```

#### Testing and building the website


* `mkdocs serve` - Start the live-reloading docs server, to test the site locally (http://127.0.0.1:8000/).
* `mkdocs gh-deploy` - Deploys the site on github pages.

* `mkdocs build` - Build the documentation site.
* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs -h` - Print help message and exit.

### Thanks
Thanks to i-Trop IRD platform for support on docker VM creation and data storage.

Special thanks to IFB for support and availability of VM on Biosphere !
