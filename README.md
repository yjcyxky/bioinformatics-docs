<h2 align="center">Docs for Bioinformatics</h2>

## Installation

```
git clone https://github.com/yjcyxky/bioinformatics-docs.git

cd bioinformatics-docs

virtualenv -p python3 .env
source .env/bin/activate

pip3 install -r requirements.txt
```

## Launch Docs Website

```
mkdocs serve
```

## Modify Docs

Modify the markdown files in the `docs` folder. If you want to modify the table of contents, please modify the `mkdocs.yml` file. 

You can follow the [MkDocs](https://squidfunk.github.io/mkdocs-material/) documentation to learn more.

## Publish Docs Website

After you push your changes to the main branch, the docs website will be automatically published to [https://bioinformatics.3steps.cn](https://bioinformatics.3steps.cn).

```
git add *
git commit -m "<Your Message>"
git push origin main
```