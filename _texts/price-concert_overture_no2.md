---
layout: page
title: Concert Overture No. 2
author: Price, Florence B.
inst: orch
permalink: /price-concert-overture-no2/
document: price_concert_overture_no2.mei
---

## Alternate Title
- None

## Composition Year
- 1943

## Instrumentation
- 3+pic.2+ca.2+bcl.2 - 4.3.3.1 - timp.3perc - hp - str 

## Length
- 15 min.

## Manuscripts
- MC988a: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/1522" target="_blank">Florence Beatrice Smith Price Papers Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (January 11, 1943; February 20, 1943): Box 10, Folder 8

## Premiere Performance
- Unknown

## Published Editions
- <a href="https://www.schott-music.com/en/concert-overture-no-2-no375700.html" target="_blank">*Concert Overture No. 2.*</a> Mainz: Schott, 2018.

## Recordings
- <a href="https://www.naxos.com/CatalogueDetail/?id=8.559920" target="_blank">*Price: Songs of the Oak - Concert Overtures Nos. 1&ndash;2.*</a> Württembergische Philharmonie Reutlingen; John Jeter, conductor. Naxos 8.559920, 2022.

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
