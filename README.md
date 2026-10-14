# Peter’s Chair — independent 3D study

A self-contained English / Danish viewer and documented timeline inspired by Hans J. Wegner’s CH410 Peter’s Chair design.

This is an **unofficial educational approximation**, independently modelled from overall dimensions and two-dimensional reference material. It is not affiliated with or endorsed by Carl Hansen & Søn or another furniture manufacturer.

## Model provenance and limitations

Four parts — left side, right side, seat, and backrest — were newly constructed in Blender from numerical profiles. No manufacturer CAD or existing mesh geometry was imported. The embedded synthetic wood textures and fallback rendering were made for this model.

The model includes rear seat pegs and matching side-panel holes. Peg diameter 16 mm, projection approximately 24.5 mm, and hole diameter 17 mm are estimates from a [two-dimensional assembly drawing, page 2, step 1](https://admincms.carlhansen.com/globalassets/products/loungechairs/kk47000/ch410-assembling-instruction.pdf#page=2).

Nominal overall dimensions are **420 × 300 × 470 mm**, with a **250 mm seat height**. Internal dimensions, curves, thicknesses, openings, and joints are estimates. This visual study is not a fabrication plan, verified assembly guide, structural assessment, or safety assessment.

Independent modelling does not establish rights clearance, public-domain status, or permission to manufacture or commercially reproduce the original chair design. **No blanket open-source license is granted to the model or the referenced design.** Source publications and trademarks remain subject to their respective rights.

## Viewer

Open the [GitHub Pages viewer](https://hsylife.github.io/ch410-peters-chair/) or download `index.html` and open it in a browser with JavaScript and WebGL enabled.

- Switch between English and Danish with EN / DA.
- Drag to rotate, scroll to zoom, or Shift-drag to pan.
- Use the direction buttons, zoom controls, reset, or auto-rotation.
- The separated-parts view is illustrative and is not an assembly guide.
- Follow the timeline button for design and production evidence.

The HTML embeds its model, textures, fallback rendering, and viewer code. Viewing works offline; external source links require internet access. There are no external script, font, or model downloads.

## Timeline sources

The timeline distinguishes design dates, auction object datings, publication dates, and factory ownership events. Their order does not imply continuous production or a succession of chair manufacturers. Unknown production boundaries remain unknown.

- [Carl Hansen & Søn — CH410](https://www.carlhansen.com/en/en/collection/childrens-furniture/ch410)
- [Carl Hansen & Søn — 2018 catalogue, pp. 188–189](https://blog.bruno-wickart.ch/wp-content/uploads/2018/03/CHS_Catalogue2018_UK.pdf)
- [Scandinavian Design — Wegner chronology](https://scandinaviandesign.com/personalities/hans-j-wegner/)
- [Bunkamura — exhibition checklist, pp. 1 and 3](https://www.bunkamura.co.jp/museum/exhibition/25_wegner/topics/images/img_10478/202512230944421.pdf#page=3)
- [Quittenbaum — auction 163C, lot 465](https://www.quittenbaum.de/media/Kataloge/163C_EN.pdf)
- [Bukowskis — lot 1144431](https://www.bukowskis.com/sv/auctions/E403/lots/1144431-hans-j-wegner-peter-s-chair-table-and-shelf-fdb-mobler-danmark-1940-tal)
- [Vardemuseerne — Tarm factory history, p. 163](https://vardemuseerne.dk/wp-content/uploads/2024/12/opdatering-2017-lav-Tarm-Stole-og-Moebelfabrik-i-over-100-aar-Christian-Lind-Thomsen.pdf#page=13)
- [Living Architecture 8 — printed p. 106](https://www.usmodernist.org/LIVARCH/LIVARCH-8.pdf#page=108)
- [Living Architecture 8 — printed p. 109](https://www.usmodernist.org/LIVARCH/LIVARCH-8.pdf#page=111)

The source research is recorded in the supplied viewer, including evidence limits and a source-check date of 14 October 2026.

## Publication and validation

GitHub Pages serves `main` from the repository root. `.nojekyll` keeps the deployment a plain static site.

The published `index.html` is the supplied `Peters_Chair_Independent_Viewer_EN_DA_v6.html`, with these expected values:

- Size: 4,334,963 bytes
- SHA-256: `931787e742853de9904bce60706204c264e043571d8b48cdc305bfec3ea7b299`

Validation covers JavaScript syntax, English / Danish translation consistency, timeline source mappings, embedded GLB decoding, geometry and texture integrity, and HTTPS delivery of the exact HTML. Browser visual rendering and interaction have not been verified in this publishing environment.
