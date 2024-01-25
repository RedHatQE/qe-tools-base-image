# A python-based image with QE tools

### This repo is used by the MSI-QE to build a tools image.  

The image includes the following CLI tools:
- [rosa](https://mirror.openshift.com/pub/openshift-v4/clients/rosa/latest/rosa-linux.tar.gz)
- [oc and kubectl](https://mirror.openshift.com/pub/openshift-v4/x86_64/clients/ocp/stable/openshift-client-linux.tar.gz)
- [cm](https://api.github.com/repos/stolostron/cm-cli/releases/latest)
- [regctl](https://github.com/regclient/regclient/releases/latest/download/regctl-linux-amd64 )

The image installs [poetry](https://python-poetry.org/) and sets the following configuration:
- virtualenvs.in-project true
- installer.max-workers 10
