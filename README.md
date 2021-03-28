# creator-documentation

Welcome to the official documentation repository for Oppia where documentation is built. This repository is connected to the Read the Docs platform which hosts Oppia’s user guide.

## About Read the Docs

Read the Docs is an open source hosting platform for Sphinx-generated documentation. 

_Sphinx_ is a documentation generator and Sphinx documents are written in  a markup language called _reStructuredText_ (reST for short).

From a high-level perspective, the workflow for writing documentation in Sphinx looks like this:

1. Write the documentation in plain text files using reST.
2. Build the documentation (HTML output) using Sphinx on the command line.
3. Push docs to Oppia’s **creator-documentation** repository (or submit a pull request).
4. Read the Docs automatically builds and updates documentation from the repository.

## Steps for building html document 

Setting up:

You can read the [Sphinx Documentation][docu] for other ways to download sphinx. One way is **conda install sphinx**.

In the terminal run:

```bash
conda install sphinx
```
Then run:

```bash
#In the creator-documentation directory
sphinx-build -b html docs docs\_build
```
Here, docs is the `sourcedir` and docs/_build is the `builddir` where all the html files will appear.

If you get:
 ```bash
 ModuleNotFoundError: No module named 'sphinx_rtd_theme'
 ```
Then simply run in the terminal:
```bash
pip install sphinx-rtd-theme
```
Re-run the command **sphinx-build -b html docs docs\_build**.
This will be the last message:
```bash
The HTML pages are in docs\_build.
```

## Contributing

Contributions are welcome from the community! Changes are accepted through pull requests.

Consult the wiki to learn how you can set things up and contribute to the documentation. 

[docu]: https://www.sphinx-doc.org/en/master/usage/installation.html#install-pypi