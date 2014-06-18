Overview
========
This directory stores a default theme for an eduStack edX instance.



Theme Authoring
===============
To customize your theme:
- Fork this repository.
- Clone it into the theme directory next to your edx-platform directory and rename the theme directory to your new theme's name.
- Upload your own image assets.
- Edit the .scss file in static/sass/ and rename the file with your theme's name.
- Edit the lms.envs.json file in edx-platform and set 'USE_CUSTOM_THEME' to true, and 'THEME_NAME' to your theme's name.


License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE](LICENSE) for more info.