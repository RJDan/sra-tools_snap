<!--<h1 align="center">
  <img src="https://avatars1.githubusercontent.com/u/29598503?v=3&s=256" alt="plink">
  <br />
  plink
</h1>-->

<p align="center"><b>This is the snap for plink</b>, <i>“Comprehensive update to Shaun Purcell's PLINK.”</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://snapcraft.io/plink1.90p">
  <img alt="enpass" src="https://snapcraft.io/plink1.90p/badge.svg" />
</a>
<a href="https://snapcraft.io/plink1.90p">
  <img alt="enpass" src="https://snapcraft.io/plink1.90p/trending.svg?name=0" />
</a>
</p>
-->

<!-- Uncomment and modify this when you have a screenshot
![plink1.90p](screenshot.png?raw=true "plink1.90p")
-->

<!--<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>-->

## Install

```    sudo snap install rjd-sra-tools ```


## Set up
The snap requires some local configuration.

To rename the functions to the more familiar names, you need to run the following:

To get access to removable media, you need to run this:

```
            sudo snap connect rjd-sra-tools:removable-media
```

```
            sudo snap alias rjd-sra-tools.<function> <function>
```
Replace <function> with the name of the function you want to rename.
For example:
```
            sudo snap alias rjd-sra-tools.fastq-dump fastq-dump 
```

<!-- Uncomment and modify this when your snap is available on the store
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/plink1.90p)
-->

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Remaining tasks
<!-- Uncomment and modify this when you have a screenshot
![plink1.90p](screenshot.png?raw=true "plink1.90p")
-->

  - [x] Get prefetch functional

