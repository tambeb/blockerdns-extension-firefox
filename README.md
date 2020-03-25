# Overview
![blockerDNS](https://blockerdns.com/logo_github_repo.png "blockerDNS")

[blockerDNS](https://blockerdns.com/) blocks ads and trackers at the DNS level, the benefit being that you don't need to install any apps or extensions. But for cases where you may not want to, or be allowed to, change your DNS settings, the Firefox extension offers the same level of blocking along with the same _lack_ of logging or data collection.

## Demo
You can install the latest published version from the [Firefox Add-ons store](https://addons.mozilla.org/en-US/firefox/addon/blockerdns-ad-tracker-blocking/).

## Install from Source
If you want to modify the code or play around with it, you can sideload it into Firefox. First download and extract the [ZIP file](https://github.com/tambeb/blockerdns-extension-firefox/archive/master.zip) or clone the repository.
```
git clone https://github.com/tambeb/blockerdns-extension-firefox.git
```
Then go to Firefox's extension settings by typing __about:debugging__ in the address bar, going to __This Firefox__, clicking __Load Temporary Add-on...__ and selecting manifest.json from the extracted or cloned folder.
