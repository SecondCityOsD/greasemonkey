Greasemonkey is a user script manager for Firefox.
User scripts are small browser extensions that let you customize your
web browsing experience.


This is a fork of Greasemonkey for UXP-based browsers (Pale moon, Basilisk, etc...), contains code from janekptacijarabaci's version of Greasemonkey (https://github.com/janekptacijarabaci/greasemonkey/) while expanding it with newer features and enhancements from the upstream version of Greasemonkey (https://github.com/greasemonkey/greasemonkey).

The main goals behind rewriting Greasemonkey for UXP-based browsers are:
-	Migrate all missing features from the latest WebExtension version of Greasemonkey to janekptacijarabaci's version of Greasemonkey
-	Ensure the UXP version retains all functionalities while gaining the new capabilities introduced in the upstream version.
-	Leverage the full power of UXP’s XUL and XPCOM capabilities to maintain and even enhance the add-on’s functionalities.
-	Ensure that the addon remains as powerful as it is, without nerfing or downgrading any existing features.
-	Ensure full compatibility with the UXP platform (Pale Moon and other UXP-based browsers) without introducing breaking changes.
-	Prioritize stability by maintaining backward compatibility with existing scripts and configurations.
-	Introduce clear comments and documentation to make the code easier to read, organize, and to maintain (Fixing janekptacijarabaci's lack of documentation in his source code)
-	Retain the original user experience, keeping the UI and functionality familiar to existing users while integrating new features.
-	Adapt WebExtension APIs to XUL/XPCOM where necessary to preserve the add-on’s native feel.
-	Ensure that user scripts written for previous versions of Greasemonkey (UXP version) continue to work as expected (It'll support GM3 and GM4).
