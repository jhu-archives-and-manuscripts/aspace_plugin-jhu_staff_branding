# JHU Staff Mode Branding

## Summary
This plugin applies branding and other site-wide UI customizations to ArchivesSpace staff mode.


## Activate the plugin
- Install the plugin:
  - Clone this repository into the *plugins/jhu_staff_branding* directory; or
  - Unzip the release zip into the *plugins/jhu_staff_branding* directory.

- Enable the plugin:
  - In *config/config.rb*, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['jhu_staff_branding']

- Restart ArchivesSpace
