# Readme for the /TestCrxPackages/ directory

These are simple extensions published to:
* [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com) - todo: specific product url(s).
* The [Chrome web store] - todo: specific url

These are simple game extensions, designed so that the store doesn't reject them as spam extensions.

They open the game in a popup page when the browser action is clicked.

They are not "demo" extensions; they are actual extensions that are used internally for the end-to-end tests.

Files:
* `ciialmfkbbnfalikdcjgknhhodmpampi.crx` - for x.
* `kgcfnkdjfpnkfhjaphlllemjbmmpdcdg.crx` - for x.

todo: link to testing instructions, condense this Readme.

These are not sample extensions.  These are packages corresponding to actual extensions that have been published to the Chrome Web Store and the Microsoft Edge Add-ons store.

These packages correspond to version 1.0 for the respective extensions. Later, we updated the versions on the stores to version 1.1.

These are used to check extension updates work fine through crowd-sourced manual testing.

The instructions for the manual testers make the test users download and install these packages with version 1.0, and then press the "Update" button to check for updates. If updates work correctly (as expected), the installed extensions get updated to version 1.1.
