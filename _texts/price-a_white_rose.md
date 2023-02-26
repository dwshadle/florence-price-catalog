---
layout: page
title: A White Rose
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-a-white-rose/
document: price_a_white_rose.mei
---

## Alternate Title
- N/A

## Composition Year
- 1932 or after

## Instrumentation
- Piano and high voice

## Length
- 1 min 30 sec

## Lyricist and Source
- John Boyle O'Reilly (1844&ndash;1890)
- <a href="https://www.google.com/books/edition/In_Bohemia/EWY1AAAAMAAJ" target="_blank">*In Bohemia.*</a> Boston: Pilot Pub. Co., 1886.
    * OCLC: <a href="https://www.worldcat.org/title/228698445" target="_blank">228698445</a>
- Henney, Nella Braddy, ed. *The Standard Book of British and American Verse.* Garden City, NY: Garden City Pub. Co., 1932.
    * OCLC: <a href="https://www.worldcat.org/title/651422298" target="_blank">651422298</a>

## Manuscripts
- MS Coll. 199: <a href="https://www.library.upenn.edu/detail/collection/marian-anderson-collection" target="_blank">Marian Anderson Collection of Music Manuscripts</a>, Kislak Center for Special Collections, Van Pelt Library, University of Pennsylvania
    * Score (undated): <a href="https://franklin.library.upenn.edu/catalog/FRANKLIN_9923566943503681" target="_blank">Box 61, Folder 1440</a>[^fn1]

## Premiere Performance
- Unknown

## Published Editions
- Heard, Richard, ed. <a href="https://www.classicalvocalrep.com/products/44-Art-Songs-and-Spirituals-by-Florence-B-Price-for-Medium-High-Voice-and-Piano-Richard-Heard-205398.html" target="_blank">*44 Art Songs and Spirituals by Florence Price.*</a> Fayetteville, AR: ClarNan Editions, 2015.
    * OCLC: <a href="https://www.worldcat.org/title/902815587" target="_blank">902815587</a>

## Recordings
- <a href="https://www.acisproductions.com/agaveandreginaldlmobley" target="_blank">*American Originals: A New World, A New Canon.*</a> Reginald L. Mobley, countertenor; Agave; Acis APL 20445, 2021.
    * OCLC: <a href="https://www.worldcat.org/title/1287098335" target="_blank">1287098335</a>

## Thematic Incipit
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

-----

## Notes
[^fn1]: This manuscript lists *The Standard Book of British and American Verse* (1932) as Price's source.
