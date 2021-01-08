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

##Steps for building html document 

Before you proceed, make sure to add a "Makefile" in the docs directory. The name of file is also Makefile. [Code][code]

Setting up:

```bash
cd docs
virtualenv .
source ./bin/activate
pip install 'sphinx==1.7.9'
```
For Windows users:

```bash
cd docs
virtualenv .
activate
conda install sphinx
```
You can read the [Sphinx Documentation][docu] for other ways to download sphinx. Here **conda install sphinx** is used.


Building the docs using **make**:

```bash
# In the docs directory
make html
```


## Contributing

Contributions are welcome from the community! Changes are accepted through pull requests.

Consult the wiki to learn how you can set things up and contribute to the documentation. 


[code]: https://hastebin.com/lapehanusu.makefile
[docu]: https://www.sphinx-doc.org/en/master/usage/installation.html#install-pypi
