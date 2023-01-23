# MkDocs based arc42 Architecture Template

The purpose of this repostitory is to provide a markdown based template for setting up git hosted software architecture documentations ("documentation as code")

For layout, the [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) plugin is used.

For architecture documentation, a single page template from [arc42](https://arc42.org) is used. The content of the pre defined template in `index.md` has to be adjusted based on the personal preferences.

More information and examples about the arc42 template can be found on the [official homepage](https://docs.arc42.org/home/).

## Getting started
To use this template, you need a python3 installation and setting up a virtual environment: 
````
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
````

To review and check formats, you can start the mkdocs engine using following command: 
````
mkdocs serve
````

More information about the material plugin can be found [here](https://squidfunk.github.io/mkdocs-material/).

More information about the mkdocs engine can be found [here](https://www.mkdocs.org/).

## Mermaid support
It is possible to specify mermaid diagrams and also include them in the preview window of vscode using the [mermaid extension](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)

On mkdocs side, the mermaid plugin is already added by default. 

## draw.io support (also known as diagrams.net)
It is possible to include png pictures and edit them in vscode using .drawio.png file formats and the [draw.io extension](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)

## Deploy to Github Pages
If you want to deploy your mkdocs on github pages in order to provide access to everyone, you can simply do this following [the official documentation](https://www.mkdocs.org/user-guide/deploying-your-docs/#github-pages)
