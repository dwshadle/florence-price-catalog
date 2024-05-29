---
layout: page
title: Feet O' Jesus
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-feet-o-jesus/
document: price_feet_o_jesus.mei
---

## Alternate Title
- 

## Composition Year
- 1944

## Instrumentation
- 

## Length
- 

## Lyricist and Source
- Langston Hughes (1901&ndash;1967)
- [*Fine Clothes to the Jew*.](https://books.google.com/books?id=5qXPAAAAMAAJ) New York: Alfred A. Knopf, 1927.
    * OCLC: <a href="https://search.worldcat.org/title/35834822" target="_blank">35834822<a/>

## Manuscripts
- MS Coll. 199: <a href="https://www.library.upenn.edu/detail/collection/marian-anderson-collection" target="_blank">Marian Anderson Collection of Music Manuscripts</a>, Kislak Center for Special Collections, Van Pelt Library, University of Pennsylvania
    * Bound score, complete (undated): <a href="https://franklin.library.upenn.edu/catalog/FRANKLIN_9923566753503681" target="_blank">Box 61, Folder 1432</a>[^fn1]

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

---
## Notes
[^fn1]: This score is bound with "We Have Tomorrow" and "Hold Fast to Dreams."
