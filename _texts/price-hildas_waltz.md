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
<script src="http://www.verovio.org/javascript/latest/verovio-toolkit-wasm.js" defer></script>
    <script>
      document.addEventListener("DOMContentLoaded", (event) => {
          verovio.module.onRuntimeInitialized = async _ => {
            let tk = new verovio.toolkit();
            console.log("Verovio has loaded!");

            fetch("{{site.baseurl}}/assets/mei/{{page.document}}")
              .then( (response) => response.text() )
              .then( (meiXML) => {
                let svg = tk.renderData(meiXML, {});
                document.getElementById("incipit1").innerHTML = svg;
              });
          }
      });
    </script>
<div id="incipit1"></div>

## Bibliography
1. Brown, Rae Linda. <a href="https://www.worldcat.org/title/1122800180" target="_blank">*The Heart of a Woman: The Life and Music of Florence B. Price*</a>. Music in American Life. Urbana: University of Illinois Press, 2020.
{:.bibliography}
