---
layout: default
modal-id: 5
date: 2014-07-17
img: lua.png
alt: image-alt
project-date: April 2024
client: Premake5
category: Open Source Development
description: Debug Adpter Server implementation for Lua using lua socket
---


{% raw %}

<p class="repo-banner">
  <a href="https://github.com/lolrobbe2/luadap">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=lolrobbe2&repo=luadap&theme=vision-friendly-dark"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=lolrobbe2&repo=luadap&theme=solarized-light"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img
        src="https://github-readme-stats.vercel.app/api/pin/?username=lolrobbe2&repo=luadap"
        alt="Walter Modem ESP-IDF Repo"
      />
    </picture>
  </a>
</p>

<p class="repo-banner">
  <a href="https://github.com/microsoft/debug-adapter-protocol">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=microsoft&repo=debug-adapter-protocol&theme=vision-friendly-dark"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=microsoft&repo=debug-adapter-protocol&theme=solarized-light"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img
        src="https://github-readme-stats.vercel.app/api/pin/?username=microsoft&repo=ldebug-adapter-protocol"
        alt="Debug Adapter Protocol Repo"
      />
    </picture>
  </a>
</p>
{% endraw %}

While developing a couple features for [Premake5](https://github.com/premake/premake-core) i kept hitting a major hurdle, wich was the fact that there was no modern up-to-date debugger for usage during active development, except [mobdebug](https://github.com/pkulchenko/MobDebug) wich can be considered deprecated as there has been no active development been done.

You also had to use a special IDE for debugging, wich was not really straight forward in usage.

So i went looking for a solution that would be the most far reaching, wich was DAP(Debug Adapter Protocol) originaly developed by Mcirosoft for Visual Studio Code. With This knowledge in hand i started with the implementation!

