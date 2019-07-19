# Description

Insert description of Sphinx.

Sphinx documentation: http://www.sphinx-doc.org/en/master/index.html

# Install Sphinx

```shell
pip install -U Sphinx
```

# Setting up the documentation sources
This procedure should be run once in the beginning of the project.
```shell
sphinx-quickstart
```

# Running the build

Build html files
```shell
# Move to the directory of the sphinx project
cd sphinx/project/directory
# Build project in HTML
sphinx-build -b html sourcedir builddir
# Build project in HTML (alternative if you used sphinx-quickstart)
make html
```

# Restructured Text (rst)

References: 

http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html

https://devguide.python.org/documenting/
