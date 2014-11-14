Overview
========
[![](http://img.shields.io/badge/version-1.0-brightgreen.svg)](https://edustack.org)
[![License](http://img.shields.io/badge/license-GPLV2-brightgreen.svg)](http://opensource.org/licenses/GPL-2.0)
[![](http://img.shields.io/badge/powerd%20by-eduStack-brightgreen.svg)](https://edustack.org)

This directory stores a default theme for an eduStack edX instance.


Theme Authoring
===============
To customize your theme:
- Fork this repository.
- Clone it into the theme directory next to your edx-platform directory and rename the theme directory to your new theme's name.
- Upload your own image assets.
- Edit the .scss file in static/sass/ and rename the file with your theme's name.
- Edit the lms.envs.json file in edx-platform and set 'USE_CUSTOM_THEME' to true, and 'THEME_NAME' to your theme's name.


