# 3dfun-prompt — KV Freight Hero

A scroll-driven freight hero built using **one standalone `index.html` file** with HTML, CSS and vanilla JavaScript. No framework, package manager or build step.

## Run

Open `index.html` in a modern browser. An internet connection is required to load the supplied video assets.

## Features

- One sticky scroll viewport for container-handling video, services typography and card strip.
- Paused video scrubbing mapped to scroll position; scrolling backward reverses the motion.
- Five services with blue-to-white text reveals.
- Responsive portrait and mobile framing.
- Speed readout and deterministic `?rec=1` recorder hook (`window.__recTime(video, seconds)`).

The vehicle animation comes exclusively from the supplied remote footage, not HTML or SVG animation.