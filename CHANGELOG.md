### MMM-Assistant Change Log

All notable changes to this project will be documented in this file.

**Q**: *Why keep a changelog?*  
**A**: [BECAUSE](http://keepachangelog.com/en/1.0.0/)

**Q**: *How?*  
**A**: By carefully describing what was: *added, fixed*, and *changed*.

---


#### [1.0.3] - 2018-03-31

- Fixed #35 for new GA SDK v0.2.2
- Updated response icons in README
- Updated universal Snowboy models and moved to ./resources/u-models/
- Added response icons for amazon/alexa to ./images directory
- Added Python and Bash scripts to generate Snowboy personal voice models
- Changed google-auth.js scripts location to ./scripts and code
- Changed location of all private files into ./assets + updated relevant code
- Renamed private assets files:  (fixes #42)
    secret.json       --> google-client-secret.json  
    <downloaded>.json --> google-private-key.json  
    tokens.json       --> google-access-tokens.json


#### [1.0.2] - 2018-03-27

Have updated Assistant to use npm:
- google-assistant SDK version 0.2.2.
- @google-cloud/speech  1.3.0
etc.

- Added CHANGELOG
- Added LICENSE
- Added .gitignore
- Added ./docs directory + relevant GitHub content
- Added ./images directory for pictures
- Added ./assets directory for private config,authorization,token files
- Added ./scripts directory for Google & Alexa authrization/token scripts
- Added language support as available in the new GA SDK
- Added French translation
- Changed node_helper.js & MMM-Assistant.js to use GA SDK 22
- Updated README.md with latest instructions
- Updated package.json with updated dependencies and module tags


#### [1.0.1] - 2018-03-XX

- First new commits
- No previous changelog available 
