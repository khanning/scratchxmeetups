---
layout: default
title: Extension List
navigation_weight: 1
permalink: /
---

{% assign microbit-img = "/assets/microbit.png" | relative_url %}
{% include extension.ext
  name="micro:bit" img=microbit-img
  docs="https://llk.github.io/microbit-extension/"
  url="http://scratchx.org/?url=https://llk.github.io/microbit-extension/microbit_extension.js#scratch"
%}

{% assign cp-img = "/assets/circuitplayground.gif" | relative_url %}
{% include extension.ext
  name="Circuit Playground" img=cp-img
  docs="https://docs.google.com/document/d/1kHzcQESAlNYQ3doXQbRvta0kVhvRsAFUTvnSDIqOkGM"
  url="http://scratchx.org/?url=https://khanning.github.io/circuit-playground-scratch/circuitplayground_hid_extension.js"
%}

{% assign spotify-img = "/assets/spotify.png" | relative_url %}
{% include extension.ext
  name="Spotify" img=spotify-img
  docs="https://ericrosenbaum.github.io/spotify-extension/"
  url="http://scratchx.org/?url=https://ericrosenbaum.github.io/spotify-extension/extension.js#scratch"
%}
