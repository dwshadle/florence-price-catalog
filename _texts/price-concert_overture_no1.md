---
layout: page
title: Concert Overture No. 1
author: Price, Florence B.
inst: orch
permalink: /price-concert-overture-no1/
document: price_concert_overture_no1.mei
---

## Alternate Title
- Concert Overture on a Negro Spiritual[^fn1]
- Concert Overture on "Sinner, Please Don't Let This Harvest Pass"

## Composition Year
- 1937

## Instrumentation
- 3.2.2.2 - 4.3.3.1 - timp.4perc - strings

## Length
- 15 min.

## Manuscripts
- MC988a: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/1522" target="_blank">Florence Beatrice Smith Price Papers Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Piano reduction, incomplete (undated): Box 10, Folder 7
- MC988b: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/696/" target="_blank">Florence Beatrice Smith Price Papers Second Addendum</a>, Special Collections, Mullins Library, University of Arkansas
    * Scores, complete (November 11&ndash;December 5, 1937): 3B, Folder 17; 4B, Folder 14; 5C, Folder 33
- MC2618: <a href="https://uark.as.atlas-sys.com/repositories/2/resources/2618" target="_blank">Florence Price Collection</a>, Special Collections, Mullins Library, University of Arkansas
    * Score, complete (1937): Box 1, Folder 6

## Premiere Performance
- June 16, 1939; Federal Music Project Building (632 N. Dearborn St.), Chicago; American Concert Orchestra; Ralph Cissne, conductor.

## Published Editions
- <a href="https://www.wisemusicclassical.com/work/58908/Concert-Overture-No-1/" target="_blank">*Concert Overture No. 1.*</a> New York, NY: G. Schirmer, Inc., 2018.

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

---

## Notes
[^fn1]: The piece appeared with this title on the June 16, 1939 program.
