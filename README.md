# StayAun extension update channel

This repository is not a project. It is the update channel for **StayAun**, a
personal browser extension, and everything in it is written by a release script.

- `updates.json` — a Gecko [add-on update manifest](https://extensionworkshop.com/documentation/manage/updating-your-extension/).
  Firefox and Zen fetch it on their own timer to find out whether a newer build exists.
- `stayaun-<version>.xpi` — the published builds. Each release adds one; older ones
  stay so that an install can catch up from any version.

The extension's source is not published here.

## If you found this by accident

The xpi is **unsigned**. Firefox release and Zen with default settings will refuse
to install it, and that is correct — nothing here has been reviewed by Mozilla.
It is built for two machines belonging to one person and reports browsing time to
a server on a private network that you cannot reach.

There is nothing here to install and no reason to try.
