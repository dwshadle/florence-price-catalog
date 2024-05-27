---
layout: page
title: Sympathy
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-sympathy/
document: price_sympathy.mei
---

## Alternate Title
- None

## Composition Year
- 

## Instrumentation
- 

## Length
- 

## Lyricist and Source
- Paul Laurence Dunbar (1872&ndash;1906)
- [*Lyrics of the Hearthside*.](https://books.google.com/books?id=OX8tAAAAMAAJ) New York: Dodd, Mead, and Company, 1899.
    * OCLC: <a href="https://search.worldcat.org/title/764434" target="_blank">764434</a>

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
