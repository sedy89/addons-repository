## v1.5.2
- switched to amd64 base 

## v1.5.1
downgrade ubuntu image 

## v1.5.0
removed mmconnect
added mongodb lock file remove command

## v1.4.9
- patched transform.js regardign utc timestamp issue https://github.com/nightscout/minimed-connect-to-nightscout/issues/30

## v1.4.8
- switched to CGM dev branch for latest changes
- added de_normalize flag to config
- added mmconnect verbose flag to config

## v1.4.7
- fixed version of docker image to fix home assistant uninstall

## v1.4.6
- added mmconnect countrycode environment variable to config

## v1.4.5
- dockerimage update

## v1.4.4
- Update Nightscout from 14.2.2 to 14.2.5
- Update base images
- Update dependencies
- Remove unsupported architectures (armv7 and i386)
- added mmconnect env variables to config yaml

## v1.2.0
- Update Nightscout from 14.0.4 to 14.2.2
- Update base images
- Update dependencies
- Remove unsupported architectures (armv7 and i386)

# v1.1.1
- Better README
- Added DOCS.md file
- Added markdown lint step in the test action
- Added more possible values to auth_default_roles
- Hardcoded the Nightscout version to v14.0.4

# v1.1.0
- Added the option to set AUTH_DEFAULT_ROLES in the add-on configuration
