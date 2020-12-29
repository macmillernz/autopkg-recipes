# autopkg-recipes

Recipe repo used for AutoPkg and AutoPkgR.
AutoPkg: https://github.com/autopkg/autopkg
AutoPkgR: https://github.com/lindegroup/autopkgr
JSS Importer: https://github.com/jssimporter/JSSImporter

## Setup

### Install and import repo

Browse to https://github.com/lindegroup/autopkgr/releases/ and download the latest release.
For ue on macOS Big Sur, the version must be 1.5.5 or higher.

Launch AutoPkgr and on the 'Installer' tab, install AutoPkg, Git and JSS Importer

On the Recipes & Repos tab. Manually add this repos URL and click add.

### JSS Importer

See setup instructions here https://github.com/jssimporter/JSSImporter/wiki/Installation-and-Setup

### Dependancies

Version Splitter

### Best practice

Best practice is to include the below chown array to ensure only root can modify.
If possible, include any pre or post install scripts in the package.
If required, include any launch agents/daemons or privileged helpers in the package.