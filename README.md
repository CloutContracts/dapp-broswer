[<img src="https://raw.githubusercontent.com/CloutContracts/dapp-browser/master/assets/images/logo.png" width="150" height="whatever">](https://cloutcontracts.net/dapp-browser/)

*We originally wanted to fork [home.metamask.io](home.metamask.io), then transitioned into [app.co](app.co) once we had subdirectory problems before switching over to [Mediumish](https://github.com/wowthemesnet/mediumish-theme-jekyll) and trying to transfer the NFT's Collectives theme files for our DAPP store.*

### >> HOW TO MAKE A PULL REQUEST <<
1. Fork the repo
2. Open the [`config.yml`](https://github.com/CloutContracts/dapp-browser/blob/master/_config.yml) file and add yourself as an author following the same format. Add an avatar at `assets/images/[YOURUNIQUEAUTHORUSERNAME.jpg]` and add the image to your `avatar:` config in the config file.
3. Before making a post for your DApp, go back to `assets/images` and upload an image numbered after the DApp #. This means that if there are already 5 DApps (posts on the site), you will name the image `6.jpg` and upload to `assets/images`.
4. Create a new post under `/_posts` for your DApp. Put the date and title of the DApp in the filename. Use the standard post template:

```
---
layout: post
title:  "DApp Name"
author: YourUserName
categories: [announcements]
image: assets/images/#.jpg

---
```
5. When all is said and done, submit a PR and if approved and merged, you are free to delete the fork. If you need to add updates in the future, you would need to submit a new PR where you change the date in the post and add the changes you want.
