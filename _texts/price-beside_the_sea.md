---
layout: page
title: Beside the Sea
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-beside-the-sea/
document: price_beside_the_sea.mei
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
- Paul Laurence Dunbar (1872&ndash;1906)
- Dunbar, Paul Laurence. (*Lyrics of Lowly Life*.)[https://books.google.com/books?id=0sFNAAAAMAAJ] New York: Dodd, Mead, and Company, 1896.
     * OCLC: <a href="https://search.worldcat.org/title/1165245" target="_blank">1165245</a>

## Manuscripts
- MC988a: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/1522" target="_blank">Florence Beatrice Smith Price Papers Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (undated): Box 12, Folder 3[^fn1]
- MS Coll. 199: <a href="https://www.library.upenn.edu/detail/collection/marian-anderson-collection" target="_blank">Marian Anderson Collection of Music Manuscripts</a>, Kislak Center for Special Collections, Van Pelt Library, University of Pennsylvania
    * Score, complete (undated): Box 59, Folder 1397[^fn2]

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
[^fn1] This score has the dedication, "To Florence L. Price" (Price's older daughter, Florence Louise).
[^fn2] This score has the dedication, in pencil, "To M.A." (Marian Anderson)