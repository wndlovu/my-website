---
title: easyrbi
summary: an R package for retrieving USGS streamflow data and calculating Richards-Baker Flashiness Index.
tags:
  - R package
date: '2022-05-06T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: easyrbi hexsticker
  focal_point: Smart

links:
- name: GitHub
  url: https://github.com/amutaya/easyrbi
  icon_pack: fab
  icon: github
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

The [`easyrbi`](https://github.com/amutaya/easyrbi) R package consists of functions that retrieve streamflow data (pCode = 00060) from the [USGS website](https://waterservices.usgs.gov/rest/Site-Test-Tool.html), by using tools in the `dataRetrieval` package. Another set of functions can be used to calculate the Richards-Baker Flashiness Index (RBI) trends over time for any given gauge stations. The package also contains functions to download time series land use data [USGS Gages II](https://www.sciencebase.gov/catalog/item/59692a64e4b0d1f9f05fbd39) collected between 1931-01-01 and 2014-12-31. Some of the functions included in the package:

