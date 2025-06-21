---
layout: project
title:  "Build a Custom Area Profile"
year: 2022
categories: project infographics ux code
img: assets/img/bacap-prev.jpg
images:
- url: bacap-01.jpg
  caption: "Map-based interface for drawing and selecting geographic areas. ONS"
- url: bacap-02.jpg
  caption: "Interface for selecting census data and comparison areas. ONS"
- url: https://www.youtube.com/embed/UfytjJfha-o
  caption: "A demo of how the product works. Ahmad Barclay/ONS"
  aspect: 0.5594
- url: bacap-03.jpg
  caption: "\"Draw your own geography\" prototype using 2011 census data ([view](https://bothness.github.io/geo-draw/)). Ahmad Barclay/ONS"
---
[Build a custom area profile](https://www.ons.gov.uk/visualisations/customprofiles/){: target="_blank"} is a tool that I led the design and development for at the Office for National Statistics (ONS). It allows users to create their own data profile for any area in England and Wales using Census 2021 data, including a custom area drawn on a map.

The main challenges on the project were to build an intuitive and performant interface for selecting and drawing areas on a map, for merging the selected geographic boundaries and area codes, and to efficiently request data from an existing API (Nomis) in a way that would be performant for hundreds of concurrent users.