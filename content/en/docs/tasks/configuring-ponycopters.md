---
title: icloud
description: >
  A short lead description about this content page. It can be **bold** or _italic_ and can be split over multiple paragraphs.
date: 2017-01-05
weight: 2
---

get yourself imac vm

https://github.com/notAperson535/OneClick-macOS-Simple-KVM

using MONTEREY...

fix its apple id capabilities

https://youtu.be/vBRrCYZEjtI?si=RDTK5v9-Kv-FtFDv


Apple symbol in the far-left corner of the menu bar at the top of the screen, then click System Preferences.... Click the Apple ID preference pane. Select iCloud in the sidebar, then click the checkbox next to Optimize Mac Storage at the bottom of the window to enable/disable it.


then go to Photos app and go to preferences and set as
System Photo Library. then the iCloud setting tab becomes
available to you. DO NOT optimize storage, then just
use [osxphotos](https://github.com/RhetTbull/osxphotos)

```bash
brew install exiftool
cd ~/Desktop
mkdir backup
osxphotos export backup --exiftool --download-missing --touch-file --person-keyword --export-by-date --verbose
```