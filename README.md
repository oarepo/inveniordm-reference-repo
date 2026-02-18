# InvenioRDM reference repository

This repository is a reference for the latest invenio-app-rdm build.
It's resolved dependencies inside the uv.lock are used to create dev
versions of the oarepo package.

For production builds of the oarepo package we use the uv.lock inside
zenodo/zenodo-rdm as the source of tested dependencies.

We do not use maintrunk of the repository - always use the rdm-xy branch,
where xy is the version of invenio-app-rdm we want to use. For example
for invenio-app-rdm 14.0.0 we use the rdm-14 branch.