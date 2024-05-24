---
layout: page
title: To My Little Son
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-to-my-little-son/
document: price_to_my_little_son.mei
---

## Alternate Title
- 

## Composition Year
- 

## Copyright Information
- February 16, 1959, Florence B. Price, EU565744

## Instrumentation
- 

## Length
- 

## Lyricist and Source
- Julia Johnson Davis

## Manuscripts
- MC988b: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/696/" target="_blank">Florence Beatrice Smith Price Papers Second Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (undated): Box 4A, Folder 15

## Premiere Performance
- 

## Published Editions
- 

## Recordings
- 

## Thematic Incipits
<div>
  <div id="app" class="panel" style="border: 1px solid lightblue; min-height: 300px;"></div>
</div>

<script type="module">
  import 'https://www.verovio.org/javascript/app/verovio-app.js';

  const options = {
      defaultView: 'responsive', // default is 'responsive', alternative is 'document'
      defaultZoom: 3, // 0-7, default is 4
      enableResponsive: true, // default is true
      enableDocument: true, // default is true
  }

  // Create the app - here with an empty option object
  const app = new Verovio.App(document.getElementById("app"), options);

  // Load a file (MEI or MusicXML)
  fetch("{{site.baseurl}}/assets/mei/{{page.document}}")
      .then(function(response) {
          return response.text();
      })
      .then(function(text) {
          app.loadData(text);
      });

</script>

## Bibliography
1. Brown, Rae Linda. <a href="https://www.worldcat.org/title/1122800180" target="_blank">*The Heart of a Woman: The Life and Music of Florence B. Price*</a>. Music in American Life. Urbana: University of Illinois Press, 2020.
{:.bibliography}