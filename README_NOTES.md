# Notes

Published to - https://python-docs1.readthedocs.io/

Src: [Click here](https://docs.readthedocs.com/platform/stable/tutorial/index.html#preparing-your-repository-on-github)

Read the Docs tutorial, containing following files:

- `.readthedocs.yaml`: Read the Docs configuration file. Required.

- `README.rst`: Description of the repository.

- `pyproject.toml`: Python project metadata that makes it installable. Useful for automatic documentation generation from sources.

- `lumache.py`: Source code of the fictional Python library.

- `docs/`: Directory holding all the fictional Python library documentation in reStructuredText
  - the Sphinx configuration `docs/source/conf.py` and
  - the **root document `docs/source/index.rst`.**

# What is reStructuredText? be concise. (ChatGPT)

reStructuredText (reST) is a lightweight markup language used for writing plain text documents with simple syntax. It is commonly used for documentation in Python projects, such as README files and Sphinx-based documentation. It supports features like headings, lists, hyperlinks, code blocks, and directives to generate formatted output like HTML, PDF, or LaTeX.
