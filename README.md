# Buoy Parts Book

Every part in the Ø200 mm printed sphere probe — what it is, how it is wired,
and why it is done that way rather than the obvious way.

**Read it → https://ildarcheg.github.io/buoy-parts-book/**

## What this is

A plain-English reading of the design documents for **meteo**: solar-assisted,
ESP32-based weather probes that batch hourly readings and forward them over the
Iridium satellite network. Three are built for the 2026/27 austral season — two
land stations beside reference series on King George Island, and one expendable
buoy released mid-Drake Passage.

The page describes **SEA**, the drifter, which carries everything the design
has; what the two land stations do differently is the first table on the page.

It is a school co-build project.

## About this repository

This repo holds **one published page and nothing else**. It is a mirror, not a
source: `index.html` is generated from the working repository, where every
figure on the page has an owning document that argues it. Corrections belong
there — an edit made directly here is overwritten by the next publish.

The page is self-contained: no JavaScript, no images, no analytics, no
cookies. It fetches web fonts from Google Fonts and falls back to system fonts
offline. Save the file and it still works.

## Status

The design is not finished, and the page says so where it matters. It marks
what is owned, what is on order and what is still to buy, and it ends on the
open gaps. Several joints on the hull have never been pressure-tested; the page
names them rather than glossing them.
