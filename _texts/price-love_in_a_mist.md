---
layout: page
title: Love-In-A-Mist
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-love-in-a-mist/
document: price_love_in_a_mist.mei
---

## Alternate Title
- 

## Composition Year
- 

## Instrumentation
- 

## Length
- 

## Lyricist and Source
- Mary Rolofson Gamble (dates unknown)

## Manuscripts
- 

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
