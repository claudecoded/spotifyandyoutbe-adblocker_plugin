# Contributing to iOS AdBlock Guide

Thank you for wanting to improve this project! Community contributions are what keep these blocklists alive and effective against new ad servers.

## How to Help

### 1. Reporting New Ads (Issues)
If you encounter an ad on YouTube or Spotify while using our filters:
* Check if the ad happens consistently.
* Open a new **Issue** on GitHub.
* Provide details: Your iOS version, the app version, and your DNS provider (e.g., NextDNS).

### 2. Updating Blocklists (Pull Requests)
If you found the specific domain causing the ad and want to add it to the filters:
1. Fork this repository.
2. Create a new branch for your changes (`git checkout -b update-filters`).
3. Add the new domains to the appropriate file inside the `/filters` folder.
4. Keep the file organized and add a brief comment explaining the domain if possible.
5. Commit your changes (`git commit -m 'Add new YouTube ad domain'`).
6. Push to your branch and open a **Pull Request**.

## Rules
* Do **not** add domains that completely break core app functionalities (like login or music streaming).
* Do **not** upload or link to copyrighted `.ipa` installation files directly.
