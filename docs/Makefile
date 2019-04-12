site_install:
    pip install mkdocs==1.0.4
    pip install mkdocs-material==4.1.1

site_link:
    ln -sf $(CURDIR)/index.md

site_preview: site_link
    mkdocs serve

site_deploy: site_link
    mkdocs gh-deploy --clean