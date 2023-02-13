---
layout: page
title: Mississippi River
author: Price, Florence B.
inst: orch
permalink: /price-mississippi-river/
document: price_mississippi_river.mei
---

## Alternate Title
- The Mississippi River
- Mississippi River Suite[^fn1]

## Composition Year
- 1934

## Instrumentation
- 3+pic.2+ca.2+bcl.2+cbn - 4.3.3.1 - timp.4perc - hp - strings

## Length
- 28 min.

## Manuscripts
- MC988: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/1419" target="_blank">Florence Beatrice Smith Price Collection</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (1934): Box 6, Folder 2
- MC988b: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/696/" target="_blank">Florence Beatrice Smith Price Papers Second Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete: Box 3A, Folder 3
    * Score, damaged and incomplete: Box 6B, Folder 36
    * Parts, complete: Box 1D, Folders 36&ndash;49; Box 6A, Folders 2&ndash;3

## Premiere Performance
- Unknown

## Published Editions
- <a href="ttps://www.wisemusicclassical.com/work/58891/The-Mississippi-River-Suite/" target="_blank">*The Mississippi River (Suite).*</a> New York, NY: G. Schirmer, Inc., 2018.

## Recordings
- Florence Price: The Oak, Mississippi River Suite, Symphony No. 3. Apo Hsu, conductor; The Women's Philharmonic. Koch International Classics 3-7518-2 2111, 2007.
- <a href="https://www.naxos.com/CatalogueDetail/?id=8.559897" target="_blank">Florence Beatrice Price: Symphony No. 3 - The Mississippi River - Ethiopia's Shadow in America.</a> John Jeter, conductor; ORF Vienna Radio Symphony Orchestra. Naxos 8.559897, 2021.

## Thematic Incipits
<div>
  <div id="app" class="panel" style="border: 1px solid lightblue; min-height: 200px;"></div>
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

[^fn1]: While the piece does quote pre-existing songs, as in a suite, certain manuscript sources contain the following as a descriptive subtitle: "Symphonic Poem, The river, and the songs of those residing upon its banks."
