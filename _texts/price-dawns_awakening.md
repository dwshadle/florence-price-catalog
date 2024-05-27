---
layout: page
title: Dawn's Awakening
author: Price, Florence B.
inst: pno-voice-orig
permalink: /price-dawns-awakening/
document: price_dawns_awakening.mei
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
- James Joseph Burke (1836[?]&ndash;1928)[^fn1]

## Manuscripts
- MS Coll. 199: <a href="https://www.library.upenn.edu/detail/collection/marian-anderson-collection" target="_blank">Marian Anderson Collection of Music Manuscripts</a>, Kislak Center for Special Collections, Van Pelt Library, University of Pennsylvania
    * Bound score (undated facsimile): Box 59, Folder 1399[^fn2] 

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

--

## Notes
[^fn1]: Certain recent sources list Burke's dates of life as 1836&ndash;1928, suggesting that he was Capt. James Burke, described in the *Staten Island Advance* (April 24, 1924) as a "prolific writer of verse." Burke's [gravestone](https://www.findagrave.com/memorial/88433800/james-burke) gives his birth year as 1835. Obituaries listed him variously as 91, 92, and 93 years old when he died in April 1928.
[^fn2]: This score contains the dedication, "Dedicated to Marian Anderson" in blue pen.
