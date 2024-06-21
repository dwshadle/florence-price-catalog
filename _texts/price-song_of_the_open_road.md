---
layout: page
title: Song of the Open Road (from Four Encore Songs)
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-song-of-the-open-road/
document: price_song_of_the_open_road.mei
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
- Ogden Nash (1902&ndash;1971)
- "Song of the Open Road." *New Yorker* (October 15, 1932): 18.

## Manuscripts
- MC 988a: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/1522" target="_blank">Florence Beatrice Smith Price Papers Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Box 12, Folder 19
- MC988b: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/696/" target="_blank">Florence Beatrice Smith Price Papers Second Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (undated): Box 4A, Folder 15; Box 6B, Folder 42

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
