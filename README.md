<p align="center">
  <img src="assets/images/banner.png" alt="digdigdig — Stop copy and paste. Just feel." width="720" />
</p>

<h1 align="center">DIGDIGDIG</h1>

<p align="center">
  Find a track on one platform. Keep digging on another.
</p>


digdigdig adds search links to tracks on supported music sites. Choose a destination and open its search results in a new tab, without copying and pasting track details.

<p align="center">
  <a href="https://chromewebstore.google.com/detail/digdigdig/dhjfcmhjhjbhbmgchpfiaplenpinpmdg">
    <img src="https://img.shields.io/badge/Add_to_Chrome-E52320?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Add digdigdig to Chrome" />
  </a>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/digdigdig/dhjfcmhjhjbhbmgchpfiaplenpinpmdg">
    <img src="assets/images/promo.png" alt="Explore Beatport, YouTube, Bandcamp, and Soundeo with digdigdig" width="440" />
  </a>
</p>

## How it works

1. Open a track list on Beatport or Soundeo, or a YouTube video with a Music card.
2. Find the digdigdig search links below a recognized track.
3. Pick a destination to open search results in a new tab.

Use the extension popup to turn digdigdig on or off for the current site and choose which search destinations appear.

## Supported sites

| Site | Track source | Search destination |
| --- | :---: | :---: |
| Beatport | ✓ | ✓ |
| Soundeo | ✓ | ✓ |
| YouTube | Music cards | ✓ |
| Bandcamp | — | ✓ |

Links appear when digdigdig can recognize complete track details.

## Privacy

No account, analytics, or cookies. digdigdig reads track details on supported pages to build search links and saves site preferences with Chrome sync storage. When you click a search link, the destination site receives the search words in its URL.

Read the [privacy policy](https://kimjihyun00.github.io/digdigdig-page/privacy.html) or visit the [project page](https://kimjihyun00.github.io/digdigdig-page/).

## Project structure

This is a static site with no build step. GitHub Pages serves the HTML files directly from the repository root.

```text
index.html             Landing page
privacy.html           Privacy policy
updates.html           Release notes
assets/css/site.css    Shared styles
assets/fonts/          Local Roboto fonts
assets/images/         Page and README images
```

Keep page links relative so the site works from the GitHub Pages project path. Add release notes to [updates.html](updates.html).

## Contact

Ideas or feedback? Email [cozihyun@gmail.com](mailto:cozihyun@gmail.com).

<p align="center"><strong>KEEP DIGGING.</strong></p>
