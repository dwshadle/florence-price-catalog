---
layout: page
title: Hilda's Waltz
author: Price, Florence B.
inst: piano-char
permalink: /price-hildas-waltz/
document: price_hildas_waltz.mei
---

## Alternate Title
- None

## Composition Year
- 1927

## Instrumentation
- Solo piano

## Length
- 2-3 min.

## Manuscripts
- MC988b: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/696/" target="_blank">Florence Beatrice Smith Price Papers Second Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete: Box 1A, Folder 3

## Premiere Performance
- Unknown

## Published Editions
- Cooper, John Michael, ed. <a href="https://www.wisemusicclassical.com/work/61376/Seven-Descriptive-Pieces/" target="_blank">*Seven Descriptive Pieces.*</a> New York: G. Schirmer, Inc., 2021.

## Recordings
- <a href="https://www.albanyrecords.com/mm5/merchant.mvc?Screen=PROD&Product_Code=TROY1910-12" target="_black">*Bach to Black: Suites for Piano, Vol. II.*</a> Rochelle Sennet, piano. Albany Records TROY1910-12, 2022.

## Thematic Incipit
AAA
<div>
  <div id="Doug" class="panel" style="border: 1px solid lightblue; min-height: 200px;"></div>
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
  const app = new Verovio.App(document.getElementById("Doug"), options);

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
