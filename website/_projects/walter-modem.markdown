---
layout: default
modal-id: 4
date: 2014-07-17
img: quickspot.png
alt: image-alt
project-date: April 2014
client: DPTechnics
category: Embedded Development
description: walter modem.
---


{% raw %}

<div class="centered-bordered-image">
  <img src="img/portfolio/walter.png" alt="walter modem" />
</div>

<iframe width="560" height="315" style="margin-left: auto; margin-right: auto; max-width: 100%;" src="https://www.youtube-nocookie.com/embed/pIWgezAzBlw?autoplay=1" title="Walter, the ESP32-S3 based multi-radio (LTE-M, NB-IoT, WiFi, BLE, GNSS) celular IoT modem module" frameborder="0" allow="accelerometer;clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

<p class="repo-banner">
  <a href="https://github.com/QuickSpot/walter-esp-idf">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=QuickSpot&repo=walter-esp-idf&theme=vision-friendly-dark"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=QuickSpot&repo=walter-esp-idf&theme=solarized-light"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img
        src="https://github-readme-stats.vercel.app/api/pin/?username=QuickSpot&repo=walter-esp-idf"
        alt="Walter Modem ESP-IDF Repo"
      />
    </picture>
  </a>
</p>
{% endraw %}

The walter modem is a tiny but powerfull SOM(System On Module) containing a [SQNSGM02S celluar IOT modem](https://sequans.com/products/monarch-2-gm02s/).
I had the privilege of also working on the walter modem libaries for both [Arduino](https://github.com/QuickSpot/walter-arduino) and [ESP-IDF](https://github.com/QuickSpot/walter-esp-idf) wich facilitate the modem offloading.
With the lessons learned from the Walter Modem libary there is now an ongoing development effort for a V2 called [Kastaar Modem](https://github.com/lolrobbe2/KastaarModem)