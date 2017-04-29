# ghp_docs
Github Pages document root

###### Soft-linked files

Create soft links to these files in the Github Pages root directory.

    _documentation.html     -> ./_layouts/documentation.html
    _documentation.yaml     -> ./_data/documentation.yaml
    _group_index.html       -> ./_includes/group_index.html

Execute the following commands in their specified directories.

* In `./_layouts/`

    ln -s ../docs/_documentation.html documentation.html

* In `./_data/`

    ln -s ../docs/_index.yaml documentation.yaml
    
* In `./_includes/`

    ln -s ../docs/_group_index.html group_index.html
