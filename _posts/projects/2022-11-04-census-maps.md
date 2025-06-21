---
layout: project
title:  "Census Maps"
year: 2022
categories: project infographics ux code
img: assets/img/census-maps-prev.jpg
images:
- url: census-maps-01.jpg
  caption: "Final version of Census Maps. ONS"
- url: https://www.youtube.com/embed/9l_c5vsoLFI
  caption: "A demo of how the product works. Ahmad Barclay/ONS"
  aspect: 0.4625
- url: census-maps-05.jpg
  caption: "Prototype for Census Maps using 2011 census data ([view](https://onsvisual.github.io/census-maps/)). Ahmad Barclay/ONS"
- url: census-maps-07.jpg
  caption: "Quad-tree grid used for data loading and responsive layer switching. Ahmad Barclay/ONS"
- url: census-maps-06.jpg
  caption: "Prototype for dot density mapping ([view](https://bothness.github.io/census-dots/)). Ahmad Barclay/ONS"
- url: [census-maps-02.jpg, census-maps-03.jpg]
  caption: "LGB+ map print designs derived from Census Maps ([view](https://www.etsy.com/uk/listing/1373487158/lgbt-census-map-newcastle-print-gay)). Mawgo Design/ONS"
---
[Census maps](https://www.ons.gov.uk/census/maps){: target="_blank"} is an interactive tool for exploring Census 2021 data across England and Wales down to a neighbourhood (or "output area") level that I worked on with the Office for National Statistics (ONS).

I was responsible for developing the initial designs and working prototypes for the project, and for solving many of the technical and user interface (UI) challenges involved in displaying small area data for over 180,000 geographic areas in a fast, performant and intuitive way.

Among other things, I devised a quadtree data structure, which allowed the data to be served as flat files from a CDN, and for an appropriate level of geography to be displayed based on the population density in an area.