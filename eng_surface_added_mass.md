# Index of added mass data by surface type

In total 153 books (2 DEU, 132 ENG, 19 RUS) and 511 table rows: one row is one book and one surface.

## Surfaces found

The books give a formula for the added mass and/or a concrete value (a number, a table, or a graph with numbers) for the following types of surfaces. For each type, the number of books in which it occurs is given (a book can belong to several types):

- **ship hull and hull sections (strip theory, Lewis sections)**: 83 books.
- **circular and other cylinders (including 2D)**: 75 books.
- **plate, disk, flat strip**: 73 books.
- **sphere**: 66 books.
- **ellipsoid and spheroid, body of revolution**: 47 books.
- **body of arbitrary shape (general theory, tensor λik / m_ik)**: 33 books.
- **submarine, AUV, torpedo, rocket, underwater vehicle**: 30 books.
- **airfoil and wing, Joukowski airfoils, cascades**: 28 books.
- **rectangle, prism, parallelepiped**: 27 books.
- **offshore and other structures (platforms, trusses, perforated structures, moonpool)**: 21 books.
- **airship**: 8 books.
- **torus, ring**: 8 books.

Meaning of the note in parentheses in the `surface` column: "formula" means the book has an expression for the added mass of this surface; "values" means it has a number, a coefficient, a table, or a graph with numbers; "formula and values" means both.

The most useful references for verifying the engine: sphere (½ of the displaced fluid mass, `(2/3)πρa³`), circular cylinder (`πρa²` per unit length), circular disk (`(8/3)ρa³`), ellipsoid and spheroid (Lamb's formulas through the integrals A0, B0, C0, k11…k66), body of revolution with fins and planar sections (Grumondz, Degtyar, Shcherbakov), Joukowski airfoils, plates and cascades in 2D (Sedov), ship hull by Lewis sections (Lewis, Tasai, Bertram), SUBOFF-type underwater vehicles (Lind, Kiycak, Safari), and the structures from DNV RP-N103. Numerical tables and examples exist, for instance, for ellipsoids and airships (Grumondz), ships (Krivoy, Severholt), and for added masses in general (Patton, Korotkin; see the verdicts in `added_mass_pages.md`).

## Limitations

- Page numbers are sequential page numbers counted from the start of the book (the first page = 1), not printed page numbers. For scanned editions, check formulas and numbers against the book itself. For the book "Continuum Mechanics in Problems" the pages refer to vol. 1 (202, 207) and vol. 2 (145–147) respectively.
- For the Russian books and the books re-checked by hand, the surfaces and pages were determined by reading; for the other ENG and DEU books they were determined automatically from the text near the term, so the set of surfaces is approximate. The "ship hull" label in such rows may also mean the hull of an airship, a submarine, or another elongated body.
- If the `page` column holds a long list (including an ellipsis) or "see added_mass_pages.md", the pages given are those where the book discusses added mass; the exact formulas and tables on them have to be found in the text. Details for each book are in `added_mass_pages.md`.

## Table

| index | language | surface | book | page |
|---:|---|---|---|---|
| 1 | DEU | sphere (formula) | Bohlmann | 30 |
| 2 | DEU | ship hull (formula) | Bohlmann | 30 |
| 3 | DEU | airfoil / wing (formula) | Bohlmann | 30 |
| 4 | DEU | ellipsoid / spheroid (formula) | Bohlmann | 32 |
| 5 | DEU | ship hull (formula and values) | Kämpf | 27, 65–66, 83, 85, 98, 188, 193 |
| 6 | DEU | airship (formula and values) | Kämpf | 25, 83, 98–99, 120, 200 |
| 7 | DEU | ellipsoid / spheroid (formula and values) | Kämpf | 27, 65, 98, 193 |
| 8 | DEU | plate / disk (formula) | Kämpf | 188, 193 |
| 9 | DEU | cylinder (formula) | Kämpf | 99 |
| 10 | ENG | hull of arbitrary shape, panel method (radiation potential) (formula) | ANSYS | 43, 46, 49–50, 52 |
| 11 | ENG | tubular members, slamming (dA/dt) (formula) | ANSYS | 78 |
| 12 | ENG | added mass at the drift frequency (formula) | ANSYS | 149 |
| 13 | ENG | body of arbitrary shape in an ideal fluid (6×6 tensor, Kirchhoff equations) (formula) | Aref | 115–116 |
| 14 | ENG | ship hull by sections (strip theory) (formula) | Arslan | 1, 3–9 |
| 15 | ENG | cylinder (formula and values) | Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis | 3–4, 6–7 |
| 16 | ENG | plate / disk (formula and values) | Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis | 3, 6, 8 |
| 17 | ENG | ship hull (formula and values) | Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis | 3–4, 8 |
| 18 | ENG | offshore structure / pipe / barge (formula and values) | Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis | 6–8 |
| 19 | ENG | planar cross-section / strips (2D) (formula) | Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis | 4 |
| 20 | ENG | planar cross-section / strips (2D) (values) | Bertram | 161, 170 |
| 21 | ENG | ship hull (values) | Bertram | 170–171 |
| 22 | ENG | ellipsoid / spheroid (values) | Bertram | 171 |
| 23 | ENG | ship hull (formula and values) | Berté | 4–5 |
| 24 | ENG | planar cross-section / strips (2D) (formula and values) | Berté | 4–5 |
| 25 | ENG | submarine / AUV / torpedo (formula) | Berté | 4 |
| 26 | ENG | propeller (formula and values) | Berté | 5 |
| 27 | ENG | sphere (formula) | Biringen | 17, 34 |
| 28 | ENG | airfoil / wing (formula) | Biringen | 31 |
| 29 | ENG | planar cross-section / strips (2D) (formula) | Biringen | 31 |
| 30 | ENG | cylinder (formula) | Birk | 251, 253 |
| 31 | ENG | ship hull (formula) | Birk | 253 |
| 32 | ENG | sphere (formula) | Birkhoff, Hydrodynamics | 163, 169 |
| 33 | ENG | cylinder (formula) | Birkhoff, Hydrodynamics | 173–174 |
| 34 | ENG | ellipsoid / spheroid (formula) | Birkhoff, Hydrodynamics | 169 |
| 35 | ENG | planar cross-section / strips (2D) (formula) | Birkhoff, Hydrodynamics | 174 |
| 36 | ENG | ship hull (formula) | Birkhoff, Hydrodynamics | 174 |
| 37 | ENG | body in an ideal fluid (general matrices A, C) (formula) | Borisov, Rigid Body Dynamics | 65, 193 |
| 38 | ENG | cylinder (added mass vs. boundary radius ratio, table 1) (values) | Brebbia | 139 |
| 39 | ENG | plate / disk (formula) | Brennen, A Review of Added Mass | 11 |
| 40 | ENG | cylinder (formula) | Brennen, A Review of Added Mass | 11 |
| 41 | ENG | bubble / drop (formula and values) | Brennen, Cavitation and Bubble Dynamics | 153–154, 162 |
| 42 | ENG | sphere (formula and values) | Brennen, Cavitation and Bubble Dynamics | 149, 154 |
| 43 | ENG | plate / disk (formula and values) | Brennen, Cavitation and Bubble Dynamics | 149 |
| 44 | ENG | cylinder (formula and values) | Brennen, Cavitation and Bubble Dynamics | 149 |
| 45 | ENG | propeller (formula and values) | Carlton | 288, 291–295, 299, 306, 455 |
| 46 | ENG | ship hull (formula) | Carlton | 288, 299, 306 |
| 47 | ENG | rectangle / prism / parallelepiped (formula) | Carlton | 288 |
| 48 | ENG | cylinder (formula) | Carlton | 291 |
| 49 | ENG | planar cross-section / strips (2D) (formula) | Carlton | 306 |
| 50 | ENG | plate / disk (formula) | Carlton | 455 |
| 51 | ENG | cylinder (formula and values) | Chen | 18, 21, 26, 28, 63 |
| 52 | ENG | surface not specified (general theory) (values) | Chen | 27 |
| 53 | ENG | shaft / cylinder in fluid, annular gap (Fritz, Nagy–Chen) (formula) | Corbo | 26–28, 34 |
| 54 | ENG | multihull vessel in shallow water (values) | Dabssi | 1, 3–8 |
| 55 | ENG | ship hull (formula) | De Barros | 3 |
| 56 | ENG | planar cross-section / strips (2D) (formula) | De Barros | 3 |
| 57 | ENG | submarine / AUV / torpedo (formula) | De Barros | 3 |
| 58 | ENG | sphere (m_a = (ρ_s + a_m·ρ)πd³/6; a_m = 0.5) (formula and values) | Dey | 318, 413 |
| 59 | ENG | flat plates, cylinders, rectangular structures (A33) (formula and values) | DNV GL | 5, 8, 11, 26–28, 32–36, 42, 44–46, 50, 53–61, 63–65, 69–70, 73–75, 77, 79–80 … |
| 60 | ENG | perforated structures (A33/A33,0 at perforation 0.15–0.47) (values) | DNV GL | 61 |
| 61 | ENG | water column in a suction anchor (formula) | DNV GL | 53 |
| 62 | ENG | moonpool, κ = 0.46 (formula and values) | DNV GL | 77 |
| 63 | ENG | ship hull (formula and values) | Do, Control of Ships | 60, 113, 135, 156, 194, 209, 233, 331 |
| 64 | ENG | sphere (values) | Do, Control of Ships | 331 |
| 65 | ENG | ship hull (formula and values) | Do, Determination of Added Mass | 2–3, 6 |
| 66 | ENG | planar cross-section / strips (2D) (formula and values) | Do, Determination of Added Mass | 3–4, 6 |
| 67 | ENG | ellipsoid / spheroid (formula and values) | Do, Determination of Added Mass | 2–4 |
| 68 | ENG | sphere (formula) | Do, Determination of Added Mass | 2 |
| 69 | ENG | ship hull (values) | Do, Influence of Added Water Mass | 1 |
| 70 | ENG | sphere (½ of the displaced fluid mass), body of arbitrary shape (formula) | ELecture2015 Note18 | 5, 8–10, 18, 37, 40–42 |
| 71 | ENG | ship hull (formula and values) | Ellenrieder | 48, 106, 223, 299, 316, 327, 382 |
| 72 | ENG | submarine / AUV / torpedo (formula and values) | Ellenrieder | 69, 493 |
| 73 | ENG | planar cross-section / strips (2D) (formula and values) | Ellenrieder | 433 |
| 74 | ENG | surface not specified (general theory) (values) | Ellenrieder | 484 |
| 75 | ENG | sphere (formula and values) | Emanuel | 490–491, 508 |
| 76 | ENG | airfoil / wing (formula and values) | Emanuel | 508 |
| 77 | ENG | cylinder (formula and values) | Emanuel | 508 |
| 78 | ENG | body of arbitrary shape (tensor m_ik) (formula) | Falkovich, Fluid Mechanics | 44–46 |
| 79 | ENG | sphere (½ρV0), cylinder (formula 1.38) (formula and values) | Falkovich, Fluid Mechanics | 44–46 |
| 80 | ENG | cylinder (formula and values) | Falnes | 150, 169, 180, 197, 203 |
| 81 | ENG | sphere (formula and values) | Falnes | 67, 145, 180, 197, 203 |
| 82 | ENG | surface not specified (general theory) (values) | Falnes | 168, 179, 189, 214 |
| 83 | ENG | body of revolution (formula and values) | Falnes | 178, 180, 204 |
| 84 | ENG | offshore structure / pipe / barge (formula and values) | Falnes | 148, 150 |
| 85 | ENG | plate / disk (formula and values) | Falnes | 178, 244 |
| 86 | ENG | planar cross-section / strips (2D) (formula and values) | Falnes | 150 |
| 87 | ENG | ship hull (formula and values) | Faltinsen | 248, 256, 264, 269, 271–274, 276, 279, 296, 304–305, 307, 335, 342 … |
| 88 | ENG | planar cross-section / strips (2D) (formula and values) | Faltinsen | 259, 264, 269, 273, 276, 307, 315, 329, 334–335, 342, 349–350, 391 … |
| 89 | ENG | airfoil / wing (formula and values) | Faltinsen | 248, 269, 271–272, 306–307, 448 |
| 90 | ENG | rectangle / prism / parallelepiped (formula and values) | Faltinsen | 259, 274, 349, 394–395, 410 |
| 91 | ENG | cylinder (formula and values) | Faltinsen | 259, 264, 272–273, 304–305 |
| 92 | ENG | plate / disk (formula and values) | Faltinsen | 329–330, 334 |
| 93 | ENG | body of revolution (formula and values) | Faltinsen | 417, 424–425 |
| 94 | ENG | torus / ring (formula and values) | Faltinsen | 279 |
| 95 | ENG | surface not specified (general theory) (values) | Faltinsen | 355 |
| 96 | ENG | ship hull (formula and values) | Fossen, Guidance and Control | 48, 51, 53, 57–58, 70, 195, 217–218, 367, 377, 398 |
| 97 | ENG | submarine / AUV / torpedo (formula and values) | Fossen, Guidance and Control | 48, 51, 57, 69, 117 |
| 98 | ENG | airfoil / wing (formula and values) | Fossen, Guidance and Control | 48, 398–399 |
| 99 | ENG | ellipsoid / spheroid (formula and values) | Fossen, Guidance and Control | 55–56, 69 |
| 100 | ENG | sphere (formula and values) | Fossen, Guidance and Control | 56, 69 |
| 101 | ENG | planar cross-section / strips (2D) (formula) | Fossen, Guidance and Control | 51–53 |
| 102 | ENG | propeller (formula) | Fossen, Guidance and Control | 367 |
| 103 | ENG | body of revolution (formula) | Fossen, Guidance and Control | 399 |
| 104 | ENG | rectangle / prism / parallelepiped (formula) | Fossen, Guidance and Control | 53 |
| 105 | ENG | cylinder (formula) | Fossen, Guidance and Control | 58 |
| 106 | ENG | ship hull (formula and values) | Fossen, Handbook of Marine Craft | 23, 83, 106, 111, 130, 134, 141, 147, 176–177, 199, 263 |
| 107 | ENG | submarine / AUV / torpedo (formula and values) | Fossen, Handbook of Marine Craft | 23, 125, 134, 141, 147, 177, 199 |
| 108 | ENG | offshore structure / pipe / barge (formula) | Fossen, Handbook of Marine Craft | 147, 177, 199 |
| 109 | ENG | surface not specified (general theory) (values) | Fossen, Handbook of Marine Craft | 107, 119 |
| 110 | ENG | planar cross-section / strips (2D) (formula and values) | Fossen, Handbook of Marine Craft | 263 |
| 111 | ENG | ship hull (formula and values) | Fossen, Marine Control Systems | 24, 77–82, 118, 124, 167, 245, 295, 316, 377, 382, 485 |
| 112 | ENG | planar cross-section / strips (2D) (formula and values) | Fossen, Marine Control Systems | 113, 167, 485 |
| 113 | ENG | propeller (formula and values) | Fossen, Marine Control Systems | 315, 426, 485 |
| 114 | ENG | submarine / AUV / torpedo (formula and values) | Fossen, Marine Control Systems | 80, 309 |
| 115 | ENG | airfoil / wing (formula and values) | Fossen, Marine Control Systems | 80 |
| 116 | ENG | circular and rectangular cylinders near the free surface (formula) | Frank | 5–7, 9, 16, 18–20, 35–38, 40, 42–44, 46–47, 52 |
| 117 | ENG | cylinder (formula and values) | Friel | 5, 9 |
| 118 | ENG | planar cross-section / strips (2D) (formula and values) | Friel | 4–5 |
| 119 | ENG | offshore structure / pipe / barge (formula) | Friel | 9 |
| 120 | ENG | body of revolution (formula) | Friel | 9 |
| 121 | ENG | ship hull (formula) | Gaythwaite | 215, 309 |
| 122 | ENG | cylinder (formula) | Gaythwaite | 215 |
| 123 | ENG | propeller (formula) | Ghassemi | 3, 7 |
| 124 | ENG | airfoil / wing (formula and values) | Ghassemi | 3, 9 |
| 125 | ENG | sphere (formula and values) | Ghassemi | 5–7 |
| 126 | ENG | ellipsoid / spheroid (formula) | Ghassemi | 6–7 |
| 127 | ENG | planar cross-section / strips (2D) (formula and values) | Graebel | 129–130 |
| 128 | ENG | cylinder (formula) | Graebel | 130 |
| 129 | ENG | sphere (formula) | Graebel | 96 |
| 130 | ENG | cylinder (formula and values) | Greenhow | 4 |
| 131 | ENG | planar cross-section / strips (2D) (formula and values) | Greenhow | 4 |
| 132 | ENG | plate / disk (formula and values) | Grift | 34, 37–38, 43–45, 47, 56 |
| 133 | ENG | torus / ring (values) | Grift | 44, 47 |
| 134 | ENG | rectangle / prism / parallelepiped (formula and values) | Grift | 37 |
| 135 | ENG | sphere (formula) | Grift | 45 |
| 136 | ENG | rectangle / prism / parallelepiped (formula and values) | Grue | 10, 35, 39, 49 |
| 137 | ENG | planar cross-section / strips (2D) (formula) | Grue | 8, 18, 39 |
| 138 | ENG | surface not specified (general theory) (values) | Grue | 12 |
| 139 | ENG | sphere (formula) | Grue | 14 |
| 140 | ENG | plate / disk (formula) | Grue | 18 |
| 141 | ENG | cylinder (formula) | Grue | 8 |
| 142 | ENG | cylinders, spheres, truss members (coefficient Cm) (values) | Gudmestad, Hydrodynamic Coefficients |  |
| 143 | ENG | offshore structure / pipe / barge (formula and values) | Gudmestad, Marine Technology and Operations | 234, 242–243, 276, 310, 366, 371 |
| 144 | ENG | cylinder (formula and values) | Gudmestad, Marine Technology and Operations | 93, 111 |
| 145 | ENG | rectangle / prism / parallelepiped (formula) | Gudmestad, Marine Technology and Operations | 243 |
| 146 | ENG | ship hull (formula and values) | Guedes Soares | 32, 77–78, 293, 720 |
| 147 | ENG | rectangle / prism / parallelepiped (formula and values) | Guedes Soares | 67, 79 |
| 148 | ENG | planar cross-section / strips (2D) (values) | Guedes Soares | 79–80 |
| 149 | ENG | sphere (formula) | Guedes Soares | 29 |
| 150 | ENG | offshore structure / pipe / barge (formula and values) | Guedes Soares | 67 |
| 151 | ENG | sphere (formula and values) | Guyon | 219, 222 |
| 152 | ENG | planar cross-section / strips (2D) (values) | Guyon | 219 |
| 153 | ENG | airfoil / wing (values) | Guyon | 219 |
| 154 | ENG | ship hull (formula and values) | Saunders | 447–449, 452, 461, 464, 466–468, 746 |
| 155 | ENG | rectangle / prism / parallelepiped (formula and values) | Saunders | 447–448, 452, 463–464 |
| 156 | ENG | ellipsoid / spheroid (formula and values) | Saunders | 449, 452, 461 |
| 157 | ENG | propeller (formula and values) | Saunders | 464, 466, 468 |
| 158 | ENG | plate / disk (formula and values) | Saunders | 449, 466 |
| 159 | ENG | planar cross-section / strips (2D) (formula and values) | Saunders | 461, 468 |
| 160 | ENG | cylinder (formula) | Saunders | 467 |
| 161 | ENG | airfoil / wing (formula) | Saunders | 746 |
| 162 | ENG | ship hull (formula and values) | Havelock | 503, 509, 521, 597 |
| 163 | ENG | rectangle / prism / parallelepiped (values) | Havelock | 503, 521 |
| 164 | ENG | planar cross-section / strips (2D) (values) | Havelock | 503 |
| 165 | ENG | sphere (formula) | Havelock | 597 |
| 166 | ENG | ellipsoid / spheroid (formula) | Havelock | 597 |
| 167 | ENG | planar cross-section / strips (2D) (formula and values) | Howe | 131, 216, 221 |
| 168 | ENG | sphere (formula) | Howe | 89, 91, 277 |
| 169 | ENG | cylinder (formula) | Howe | 131, 221 |
| 170 | ENG | airfoil / wing (formula and values) | Howe | 216 |
| 171 | ENG | deep-sea underwater vehicle (coefficient identification) (values) | Hua |  |
| 172 | ENG | deep-sea mining vehicle (CFD) (values) | Huang | 1, 3–8, 10–20 |
| 173 | ENG | cylinder (formula and values) | Hutchison | 3–5, 8 |
| 174 | ENG | propeller (formula and values) | Hutchison | 2–8 |
| 175 | ENG | triangle / polygon (formula) | Hutchison | 3 |
| 176 | ENG | sphere (formula and values) | Imlay | 5, 17, 22, 24 |
| 177 | ENG | ellipsoid / spheroid (formula and values) | Imlay | 5, 22, 24 |
| 178 | ENG | body of revolution (formula and values) | Imlay | 5, 14 |
| 179 | ENG | submarine / AUV / torpedo (formula and values) | Inzartsev | 347, 553–554 |
| 180 | ENG | surface not specified (general theory) (values) | Inzartsev | 458 |
| 181 | ENG | cylinder (formula) | Irschik | 89, 216 |
| 182 | ENG | sphere (formula) | Irschik | 88–89 |
| 183 | ENG | torus / ring (formula) | Irschik | 216 |
| 184 | ENG | airfoil / wing (formula and values) | Jakuba | 22, 29, 34–40, 106–107 |
| 185 | ENG | planar cross-section / strips (2D) (formula and values) | Jakuba | 34–36, 38, 40, 55 |
| 186 | ENG | ship hull (formula and values) | Jakuba | 22, 40, 55 |
| 187 | ENG | plate / disk (formula and values) | Jakuba | 36–37 |
| 188 | ENG | submarine / AUV / torpedo (formula) | Jakuba | 35 |
| 189 | ENG | underwater vehicle: ellipsoid, body of revolution (formula and values) | Jones | 31 |
| 190 | ENG | ship hull (formula and values) | Journee | 261, 272, 409, 432, 435, 474 |
| 191 | ENG | cylinder (formula and values) | Journee | 218–220, 225, 272, 473 |
| 192 | ENG | planar cross-section / strips (2D) (formula and values) | Journee | 219, 272, 419, 474 |
| 193 | ENG | offshore structure / pipe / barge (formula and values) | Journee | 409, 432, 474 |
| 194 | ENG | sphere (values) | Journee | 219 |
| 195 | ENG | ellipsoid / spheroid (formula and values) | Journee | 220 |
| 196 | ENG | rectangle / prism / parallelepiped (values) | Journee | 409 |
| 197 | ENG | submerged sphere, ½ of the displaced fluid mass (formula and values) | Justino | 3–4, 6, 8, 10–11 |
| 198 | ENG | submarine (scale effects on vertical derivatives) (formula and values) | Kahramanoğlu | 1, 3, 6, 8–10 |
| 199 | ENG | sphere (formula and values) | Kambe | 126 |
| 200 | ENG | cylinder (formula and values) | Kambe | 126 |
| 201 | ENG | planar cross-section / strips (2D) (formula and values) | Kambe | 126 |
| 202 | ENG | SUBOFF-type underwater vehicle (PMM) (values) | Kim | 3, 9 |
| 203 | ENG | DARPA SUBOFF at different scales (Xu̇, Yv̇, Zẇ, Mq̇, Nṙ) (values) | Kiycak | 8, 21–22 |
| 204 | ENG | triangle / polygon (formula and values) | Koo | 3, 7, 9–10, 12 |
| 205 | ENG | rectangle / prism / parallelepiped (formula and values) | Koo | 3, 6–7, 9–10 |
| 206 | ENG | planar cross-section / strips (2D) (formula and values) | Koo | 3, 9, 12 |
| 207 | ENG | cylinder (formula and values) | Korde | 101, 332, 337, 342–343, 362 |
| 208 | ENG | planar cross-section / strips (2D) (formula and values) | Korde | 342–343, 358 |
| 209 | ENG | sphere (formula and values) | Korde | 358, 372 |
| 210 | ENG | offshore structure / pipe / barge (formula) | Korde | 332 |
| 211 | ENG | surface not specified (general theory) (values) | Korde | 335 |
| 212 | ENG | plate / disk (formula and values) | Korde | 342 |
| 213 | ENG | ellipsoid / spheroid (formula and values) | Korde | 358 |
| 214 | ENG | rectangle / prism / parallelepiped (formula) | Korde | 372 |
| 215 | ENG | wedge section of a planing hull, m = k(β)ρh1² (formula) | Kornev | section 2.4 |
| 216 | ENG | plate / disk (formula and values) | Korotkin | 45, 55, 109–111, 217, 226–228, 230–232, 249, 263, 281, 283, 293, 296 … |
| 217 | ENG | ship hull (formula and values) | Korotkin | 70, 86, 92, 109, 147, 150–151, 167, 234, 249, 251, 281, 283 … |
| 218 | ENG | cylinder (formula and values) | Korotkin | 138, 150–151, 212, 217, 226–228, 230–234, 263, 281, 291 |
| 219 | ENG | ellipsoid / spheroid (formula and values) | Korotkin | 92, 109, 111, 138, 212, 220–221, 234, 251 |
| 220 | ENG | rectangle / prism / parallelepiped (formula and values) | Korotkin | 55, 110, 212, 230–231, 242–243, 251, 263 |
| 221 | ENG | sphere (formula and values) | Korotkin | 111, 118, 150, 220, 237 |
| 222 | ENG | propeller (formula and values) | Korotkin | 344, 348 |
| 223 | ENG | airfoil / wing (formula and values) | Korotkin | 55, 138 |
| 224 | ENG | planar cross-section / strips (2D) (formula and values) | Korotkin | 70, 151 |
| 225 | ENG | offshore structure / pipe / barge (formula and values) | Korotkin | 242–243 |
| 226 | ENG | offshore structure / pipe / barge (formula and values) | Kraemer | 19, 22, 32–34, 41–42, 49 |
| 227 | ENG | rectangle / prism / parallelepiped (values) | Kraemer | 19 |
| 228 | ENG | sphere (formula) | Kundu | 369, 372, 377 |
| 229 | ENG | cylinder (formula) | Kundu | 367 |
| 230 | ENG | planar cross-section / strips (2D) (formula) | Kundu | 367 |
| 231 | ENG | ship hull (formula and values) | Lewandowski | 42, 52, 54, 59–60, 63–64, 79, 101, 122, 127–128, 135, 250–251, 291 … |
| 232 | ENG | planar cross-section / strips (2D) (formula and values) | Lewandowski | 51, 59–60, 65, 127, 244, 250–251, 291, 294, 297, 302 |
| 233 | ENG | sphere (formula and values) | Lewandowski | 54, 65, 135, 234 |
| 234 | ENG | rectangle / prism / parallelepiped (formula and values) | Lewandowski | 61, 63, 251, 354 |
| 235 | ENG | propeller (formula and values) | Lewandowski | 101, 123, 135 |
| 236 | ENG | ellipsoid / spheroid (formula and values) | Lewandowski | 54, 60, 65 |
| 237 | ENG | surface not specified (general theory) (values) | Lewandowski | 66, 295 |
| 238 | ENG | plate / disk (formula and values) | Lewandowski | 61, 63 |
| 239 | ENG | cylinder (values) | Lewandowski | 250 |
| 240 | ENG | offshore structure / pipe / barge (values) | Lewandowski | 300 |
| 241 | ENG | submarine / AUV / torpedo (formula and values) | Lewandowski | 52 |
| 242 | ENG | triangle / polygon (values) | Lewandowski | 61 |
| 243 | ENG | body of revolution (values) | Lewandowski | 79 |
| 244 | ENG | Lewis sections, ship hull (strip method) (formula) | Lewis | 69–70 |
| 245 | ENG | airship (formula and values) | Li, Airship Dynamics Modeling | 4, 6, 18 |
| 246 | ENG | body of revolution (formula and values) | Li, Airship Dynamics Modeling | 6, 18 |
| 247 | ENG | ship hull (formula and values) | Li, Airship Dynamics Modeling | 4, 6 |
| 248 | ENG | planar cross-section / strips (2D) (formula) | Li, Airship Dynamics Modeling | 18 |
| 249 | ENG | ellipsoid / spheroid (formula) | Li, Airship Dynamics Modeling | 4 |
| 250 | ENG | airship (formula and values) | Li, Dynamics Modeling and Simulation | 19, 45–46, 59–60, 118, 122 |
| 251 | ENG | ship hull (formula and values) | Li, Dynamics Modeling and Simulation | 46–47, 49, 60, 123 |
| 252 | ENG | ellipsoid / spheroid (formula and values) | Li, Dynamics Modeling and Simulation | 46, 106, 118 |
| 253 | ENG | surface not specified (general theory) (values) | Li, Dynamics Modeling and Simulation | 98–99 |
| 254 | ENG | cone (values) | Li, Dynamics Modeling and Simulation | 118 |
| 255 | ENG | planar cross-section / strips (2D) (formula and values) | Li, Dynamics Modeling and Simulation | 47 |
| 256 | ENG | surface not specified (general theory) (values) | Lin | 22 |
| 257 | ENG | ship hull (formula) | Lin | 7 |
| 258 | ENG | submarine (Xu̇, Yv̇, Zẇ, Kṗ, Mq̇, Nṙ, table 6.1) (values) | Lind | 78–79 |
| 259 | ENG | cylinder (formula) | Maheri | 3, 10, 12 |
| 260 | ENG | planar cross-section / strips (2D) (formula and values) | Manneville | 355, 411 |
| 261 | ENG | sphere (formula and values) | Manneville | 355, 357 |
| 262 | ENG | cylinder (formula and values) | Manneville | 355, 357 |
| 263 | ENG | submarine / AUV / torpedo (formula and values) | Manneville | 352 |
| 264 | ENG | airship (formula and values) | Manneville | 352 |
| 265 | ENG | airfoil / wing (formula) | Manneville | 411 |
| 266 | ENG | planar cross-section / strips (2D) (formula and values) | Newman, Marine Hydrodynamics (2018) | 17, 76, 174–176, 186–187, 334, 360–361, 377–378, 383–384, 386, 397, 404–406, 411 … |
| 267 | ENG | ship hull (formula and values) | Newman, Marine Hydrodynamics (2018) | 17, 336, 383, 385–387, 398, 405–406, 411, 415 |
| 268 | ENG | rectangle / prism / parallelepiped (formula and values) | Newman, Marine Hydrodynamics (2018) | 17, 176, 183, 185, 187, 345, 360, 380, 385 |
| 269 | ENG | body of revolution (formula and values) | Newman, Marine Hydrodynamics (2018) | 375, 377–378, 387, 397, 405, 411, 415 |
| 270 | ENG | sphere (formula and values) | Newman, Marine Hydrodynamics (2018) | 175, 177, 336, 361, 378, 421 |
| 271 | ENG | cylinder (formula and values) | Newman, Marine Hydrodynamics (2018) | 76, 175, 334, 361, 396, 406 |
| 272 | ENG | plate / disk (formula and values) | Newman, Marine Hydrodynamics (2018) | 176–177, 185–187, 259, 384 |
| 273 | ENG | ellipsoid / spheroid (formula and values) | Newman, Marine Hydrodynamics (2018) | 177, 336, 421 |
| 274 | ENG | airfoil / wing (formula) | Newman, Marine Hydrodynamics (2018) | 262, 380 |
| 275 | ENG | offshore structure / pipe / barge (formula and values) | Newman, Marine Hydrodynamics (2018) | 360, 396 |
| 276 | ENG | surface not specified (general theory) (values) | Newman, Marine Hydrodynamics (2018) | 333 |
| 277 | ENG | triangle / polygon (formula) | Newman, Marine Hydrodynamics (2018) | 380 |
| 278 | ENG | cylinder (formula) | Massey | 404 |
| 279 | ENG | sphere (formula) | Massey | 404 |
| 280 | ENG | planar cross-section / strips (2D) (formula) | Massey | 404 |
| 281 | ENG | thick-walled open-bottom cylinder at finite depth (formula and values) | Mavrakos | 1, 10–14 |
| 282 | ENG | simple subsea structures (parallelepiped, plates, cylinders) (values) | Mentzoni | 1–11 |
| 283 | ENG | torus / ring (formula and values) | Miloh, Mass Coefficients of a Torus | 7–8, 12–13 |
| 284 | ENG | body of revolution (formula) | Miloh, Mass Coefficients of a Torus | 8, 13 |
| 285 | ENG | sphere (formula) | Miloh, Mass Coefficients of a Torus | 13 |
| 286 | ENG | torus / ring (formula and values) | Miloh, The Added Mass Coefficients | 7–8, 12–13 |
| 287 | ENG | body of revolution (formula) | Miloh, The Added Mass Coefficients | 8, 13 |
| 288 | ENG | sphere (formula) | Miloh, The Added Mass Coefficients | 13 |
| 289 | ENG | sphere (values) | Mironer | 304, 310 |
| 290 | ENG | cylinder (values) | Mironer | 304, 314 |
| 291 | ENG | rectangle / prism / parallelepiped (formula and values) | Mironer | 304, 306 |
| 292 | ENG | plate / disk (formula and values) | Mironer | 306, 314 |
| 293 | ENG | cylinder (formula and values) | Molin | 113–114, 129, 134, 140, 142, 150–152, 170, 191–192, 296, 324, 330, 339–341 … |
| 294 | ENG | planar cross-section / strips (2D) (formula and values) | Molin | 129, 191, 200, 229, 324, 339, 341–342 |
| 295 | ENG | ship hull (formula and values) | Molin | 180, 183, 219, 277, 296, 330, 387 |
| 296 | ENG | rectangle / prism / parallelepiped (formula and values) | Molin | 113, 200, 223, 229, 296, 344 |
| 297 | ENG | plate / disk (formula and values) | Molin | 114, 134, 228, 324, 341–343 |
| 298 | ENG | offshore structure / pipe / barge (formula and values) | Molin | 134, 150, 152, 157, 200–201 |
| 299 | ENG | sphere (formula and values) | Molin | 114, 219 |
| 300 | ENG | surface not specified (general theory) (values) | Molin | 141, 345 |
| 301 | ENG | airfoil / wing (values) | Molin | 170 |
| 302 | ENG | ship: added moment of inertia in roll, impact (Kármán) (formula) | Molland | 509, 540, 558 |
| 303 | ENG | plate / disk (formula) | Monterrubio | 5 |
| 304 | ENG | oblate spheroid (formula) | Moraga | 1–2, 23–24, 26–27, 30, 32 |
| 305 | ENG | airship (formula) | Mueller | 8, 10 |
| 306 | ENG | ellipsoid / spheroid (formula) | Mueller | 8, 10 |
| 307 | ENG | body of revolution (formula) | Mueller | 10 |
| 308 | ENG | ship hull (formula) | Mueller | 8 |
| 309 | ENG | Lewis sections (values) | Mundekkatt | 39–40 |
| 310 | ENG | 42 stations (values) | Mundekkatt | 39–40 |
| 311 | ENG | planar cross-section / strips (2D) (formula) | Munk | 13 |
| 312 | ENG | ship hull (formula) | Munk | 13 |
| 313 | ENG | cylinder (formula) | Munk | 13 |
| 314 | ENG | plate / disk (formula) | Nesteruk | 123 |
| 315 | ENG | torus / ring (formula) | Nesteruk | 123 |
| 316 | ENG | planar cross-section / strips (2D) (formula and values) | Newman, Marine Hydrodynamics (old edition) | 156–157, 167–168, 310, 351–352, 357, 370, 378–379, 388 |
| 317 | ENG | ship hull (formula and values) | Newman, Marine Hydrodynamics (old edition) | 307, 311, 357, 359, 376, 379, 388 |
| 318 | ENG | sphere (formula and values) | Newman, Marine Hydrodynamics (old edition) | 156, 158–159, 312, 352 |
| 319 | ENG | cylinder (formula and values) | Newman, Marine Hydrodynamics (old edition) | 62, 157, 310–311, 379 |
| 320 | ENG | plate / disk (formula and values) | Newman, Marine Hydrodynamics (old edition) | 157–158, 166–168, 353 |
| 321 | ENG | rectangle / prism / parallelepiped (formula and values) | Newman, Marine Hydrodynamics (old edition) | 164, 166, 311, 320 |
| 322 | ENG | body of revolution (formula) | Newman, Marine Hydrodynamics (old edition) | 353, 370, 376, 378 |
| 323 | ENG | ellipsoid / spheroid (formula and values) | Newman, Marine Hydrodynamics (old edition) | 158–159, 312, 352 |
| 324 | ENG | offshore structure / pipe / barge (formula) | Newman, Marine Hydrodynamics (old edition) | 62, 370 |
| 325 | ENG | airfoil / wing (formula) | Newman, Marine Hydrodynamics (old edition) | 62, 241 |
| 326 | ENG | sphere (formula and values) | Padfield | 163, 354 |
| 327 | ENG | plate / disk (formula and values) | Padfield | 164 |
| 328 | ENG | airfoil / wing (values) | Padfield | 201 |
| 329 | ENG | surface not specified (general theory) (values) | Padfield | 357 |
| 330 | ENG | ellipsoid / spheroid (formula and values) | Patton, An Experimental Determination | 33, 54 |
| 331 | ENG | airfoil / wing (values) | Patton, An Experimental Determination | 54 |
| 332 | ENG | sphere (values) | Patton, An Experimental Determination | 54 |
| 333 | ENG | plate / disk (values) | Patton, An Experimental Determination | 55 |
| 334 | ENG | rectangle / prism / parallelepiped (values) | Patton, An Experimental Determination | 55 |
| 335 | ENG | triangle / polygon (values) | Patton, An Experimental Determination | 55 |
| 336 | ENG | plate / disk (formula) | Patton, Hydrodynamic Mass of Bodies | 11 |
| 337 | ENG | ellipsoid / spheroid (formula and values) | Patton, Hydrodynamic Mass of Bodies | 15 |
| 338 | ENG | body of revolution (formula and values) | Patton, Hydrodynamic Mass of Bodies | 15 |
| 339 | ENG | rectangle / prism / parallelepiped (formula and values) | Patton, Hydrodynamic Mass of Bodies | 15 |
| 340 | ENG | circular, elliptic and floating cylinders (2D) (formula and values) | Porter | 1–2, 4, 6, 8, 10, 20, 24, 26, 30, 32, 34, 40, 82, 84 … |
| 341 | ENG | sphere (formula and values) | Potter | 408–409, 459 |
| 342 | ENG | ellipsoid / spheroid (formula and values) | Potter | 408, 459 |
| 343 | ENG | airfoil / wing (values) | Potter | 409, 459 |
| 344 | ENG | cylinder (formula and values) | Potter | 408–409 |
| 345 | ENG | sphere (formula) | Rahman | 77, 80 |
| 346 | ENG | cylinder (formula) | Rahman | 77 |
| 347 | ENG | flexible 3D barge (heave, pitch), graphs (values) | Ramli | 6–8 |
| 348 | ENG | submarine / AUV / torpedo (formula and values) | Renilson | 16, 79, 82 |
| 349 | ENG | propeller (formula) | Renilson | 15–16 |
| 350 | ENG | plate / disk (formula and values) | Renilson | 82 |
| 351 | ENG | plate / disk (formula) | Review of Added Mass and Fluid Inertial Forces (1982) | 11 |
| 352 | ENG | cylinder (formula) | Review of Added Mass and Fluid Inertial Forces (1982) | 11 |
| 353 | ENG | submarine / AUV / torpedo (formula) | Ridley | 2 |
| 354 | ENG | propeller (formula and values) | Ridley | 8 |
| 355 | ENG | ship hull (formula and values) | Ridley | 8 |
| 356 | ENG | submarine / AUV / torpedo (formula) | Roberts | 182, 382 |
| 357 | ENG | planar cross-section / strips (2D) (formula and values) | Roberts | 44, 282 |
| 358 | ENG | propeller (formula) | Roberts | 382 |
| 359 | ENG | airfoil / wing (formula) | Roberts | 428 |
| 360 | ENG | ellipsoid / spheroid (formula) | Roberts | 428 |
| 361 | ENG | ship hull (formula and values) | Roberts | 44 |
| 362 | ENG | SUBOFF-type AUV (Zẇ = −569; Mq̇ = −522, etc.) (values) | Safari | 7 |
| 363 | ENG | sphere and floating structure (a∞, table 1) (values) | Schou | 5 |
| 364 | ENG | plate / disk (formula and values) | Sedov, Two-Dimensional Problems | 70–71, 73, 161, 194 |
| 365 | ENG | airfoil / wing (formula) | Sedov, Two-Dimensional Problems | 36, 39, 70 |
| 366 | ENG | rectangle / prism / parallelepiped (formula and values) | Sedov, Two-Dimensional Problems | 161, 163 |
| 367 | ENG | ship hull (formula) | Sedov, Two-Dimensional Problems | 194 |
| 368 | ENG | cylinder (formula) | Sedov, Two-Dimensional Problems | 39 |
| 369 | ENG | ship hull, 6 degrees of freedom (equivalent ellipsoid and other methods) (formula and values) | Sen | 2–7 |
| 370 | ENG | ship hull (formula and values) | Severholt | 14, 23, 35, 37–39, 41 |
| 371 | ENG | plate / disk (formula and values) | Severholt | 18–19, 25, 33, 38, 51 |
| 372 | ENG | submarine / AUV / torpedo (formula and values) | Severholt | 18, 25, 33, 36, 39 |
| 373 | ENG | ellipsoid / spheroid (formula and values) | Severholt | 17, 23, 41 |
| 374 | ENG | sphere (formula and values) | Severholt | 17, 23, 41 |
| 375 | ENG | body of revolution (formula and values) | Severholt | 14–15, 17 |
| 376 | ENG | planar cross-section / strips (2D) (formula) | Severholt | 14–15, 35 |
| 377 | ENG | cylinder (formula) | Severholt | 15, 35 |
| 378 | ENG | airfoil / wing (formula and values) | Severholt | 18, 25 |
| 379 | ENG | ship hull (formula) | Shi | 141 |
| 380 | ENG | surface not specified (general theory) (values) | Shi | 152 |
| 381 | ENG | cylinder (formula and values) | Sigrist | 20–22, 128, 160–161, 166, 190, 214 |
| 382 | ENG | surface not specified (general theory) (values) | Sigrist | 172–173, 177, 182, 193–194, 198 |
| 383 | ENG | torus / ring (formula and values) | Sigrist | 190, 192, 195–197 |
| 384 | ENG | rectangle / prism / parallelepiped (formula and values) | Sigrist | 184, 190 |
| 385 | ENG | body of revolution (formula and values) | Sigrist | 220, 223 |
| 386 | ENG | plate / disk (formula) | Sigrist | 165 |
| 387 | ENG | offshore structure / pipe / barge (formula) | Sigrist | 165 |
| 388 | ENG | sphere (formula and values) | Sigrist | 214 |
| 389 | ENG | airship (formula and values) | Sinha | 365–366 |
| 390 | ENG | airfoil / wing (formula) | Sinha | 365 |
| 391 | ENG | boat (Xu̇, Yv̇, Yṙ, Nv̇, Nṙ, table 2) (values) | Soares | 385–386 |
| 392 | ENG | reference ships in roll (table 5) (values) | Soares | 276 |
| 393 | ENG | underwater glider (matrix notation and numbers) (values) | Song | 8 |
| 394 | ENG | offshore structure / pipe / barge (formula and values) | Sørensen, Propulsion and Motion Control | 393–394, 434, 441 |
| 395 | ENG | ship hull (formula and values) | Sørensen, Propulsion and Motion Control | 212, 434, 441 |
| 396 | ENG | cylinder (formula and values) | Sørensen, Propulsion and Motion Control | 393–394 |
| 397 | ENG | planar cross-section / strips (2D) (values) | Sørensen, Propulsion and Motion Control | 394 |
| 398 | ENG | sphere (2/3 π r³ ρ, formula 10.160), body of arbitrary shape (m_ij) (formula) | Spurk | 10, 389–391, 393–395, 588 |
| 399 | ENG | glider on a wave, hydrofoils (Mq̇ = 0.3734 kg·m²) (values) | Sun | 18 |
| 400 | ENG | ship hull (formula) | Sutulo | 6, 21 |
| 401 | ENG | airfoil / wing (formula) | Sutulo | 21 |
| 402 | ENG | plate / disk (formula) | Sutulo | 21 |
| 403 | ENG | planar cross-section / strips (2D) (formula) | Sutulo | 6 |
| 404 | ENG | ellipsoid / spheroid (formula) | Sutulo | 6 |
| 405 | ENG | offshore structure / pipe / barge (formula and values) | Sørensen, Lecture Notes | 393–394, 434, 441 |
| 406 | ENG | ship hull (formula and values) | Sørensen, Lecture Notes | 212, 434, 441 |
| 407 | ENG | cylinder (formula and values) | Sørensen, Lecture Notes | 393–394 |
| 408 | ENG | planar cross-section / strips (2D) (values) | Sørensen, Lecture Notes | 394 |
| 409 | ENG | cylinder (formula and values) | Tasai | 2, 5, 14–15, 22 |
| 410 | ENG | planar cross-section / strips (2D) (formula and values) | Tasai | 2, 15–16, 22 |
| 411 | ENG | ship hull (formula and values) | Tasai | 2, 14 |
| 412 | ENG | sphere (formula) | Techet, Added Mass Derivation | 1 |
| 413 | ENG | cylinder (formula) | Techet, Added Mass Derivation | 2 |
| 414 | ENG | ship hull (formula and values) | Techet, Added Mass 2016 | 1, 8 |
| 415 | ENG | sphere (formula and values) | Techet, Added Mass 2016 | 4, 7 |
| 416 | ENG | rectangle / prism / parallelepiped (formula and values) | Techet, Added Mass 2016 | 3–4 |
| 417 | ENG | body of revolution (formula and values) | Techet, Added Mass 2016 | 8 |
| 418 | ENG | planar cross-section / strips (2D) (formula and values) | Techet, Added Mass 2016 | 8 |
| 419 | ENG | cylinder (formula and values) | Techet, L 01 Added Mass | 5 |
| 420 | ENG | sphere (formula and values) | Techet, L 01 Added Mass | 5 |
| 421 | ENG | ship hull (formula) | Thuné | 20, 22 |
| 422 | ENG | submarine / AUV / torpedo (formula) | Thuné | 20 |
| 423 | ENG | sphere (formula) | Thuné | 20 |
| 424 | ENG | surface not specified (general theory) (values) | Thuné | 21 |
| 425 | ENG | planar cross-section / strips (2D) (formula) | Thuné | 22 |
| 426 | ENG | propeller (values) | Thuné | 40 |
| 427 | ENG | ship hull (formula and values) | Trivedi | 20–23, 28, 33–34, 39, 41–43, 45, 47, 49, 51, 65 |
| 428 | ENG | ellipsoid / spheroid (formula and values) | Trivedi | 21–23, 33, 39, 41, 45 |
| 429 | ENG | planar cross-section / strips (2D) (formula and values) | Trivedi | 28, 33, 39, 45, 65 |
| 430 | ENG | cylinder (formula and values) | Trivedi | 21, 41–43, 65 |
| 431 | ENG | surface not specified (general theory) (values) | Trivedi | 48, 50 |
| 432 | ENG | sphere (formula) | Trivedi | 22 |
| 433 | ENG | ship, virtual displacement in vibration (Todd's formula) (formula) | Tupper | 243 |
| 434 | ENG | cylinders (2D) on the free surface: sway, heave, roll (values) | Vugts | 2–3, 7–9, 11–12, 14–17, 20–22 |
| 435 | ENG | cylinder (formula) | Wang, Dynamic Modeling | 5 |
| 436 | ENG | ellipsoid / spheroid (formula and values) | Wang, Numerical Simulation | 1–2, 18–19 |
| 437 | ENG | planar cross-section / strips (2D) (formula and values) | Wang, Numerical Simulation | 1–2, 18 |
| 438 | ENG | submarine / AUV / torpedo (values) | Wang, Numerical Simulation | 1–2 |
| 439 | ENG | cylinder (formula and values) | White | 583, 601 |
| 440 | ENG | sphere (formula and values) | White | 583, 601 |
| 441 | ENG | planar cross-section / strips (2D) (values) | White | 583 |
| 442 | ENG | sphere ((2/3)πρa³ = ½ρV) (formula and values) | Wu, Elements of Vorticity | 135–136, 139 |
| 443 | ENG | circular disk ((8/3)ρa³) (formula and values) | Wu, Elements of Vorticity | 136 |
| 444 | ENG | cylinder (2D), airfoil, finite wing (formula) | Wu, Elements of Vorticity | 139–142 |
| 445 | ENG | ship hull (formula) | Wu, Practical Design of Ships | 263, 595 |
| 446 | ENG | planar cross-section / strips (2D) (formula and values) | Wu, Practical Design of Ships | 475, 646 |
| 447 | ENG | bubble / drop (formula) | Wu, Practical Design of Ships | 475 |
| 448 | ENG | ship (empirical formulas for μ11, μ22, etc.) (formula) | Xu | 9 |
| 449 | ENG | ship hull (formula and values) | Zhao | 5 |
| 450 | ENG | ellipsoid / spheroid (formula and values) | Zhao | 5 |
| 451 | ENG | submarine / AUV / torpedo (formula and values) | Zhao | 5 |
| 452 | RUS | sphere (½ of the displaced fluid mass, Dubuat experiments k = 0.45–0.67) (formula and values) | Birkgof, Gidrodinamika | 194–196, 202–204 |
| 453 | RUS | body of arbitrary shape (formula) | Birkgof, Gidrodinamika | 197–199 |
| 454 | RUS | planar regions (conformal mapping) (formula) | Birkgof, Gidrodinamika | 209–210 |
| 455 | RUS | sphere, circular cylinder, plate in oscillating fluid (formula) | Birkgof, Gidrodinamika | 226–231 |
| 456 | RUS | circular cylinder (formula) | Chernyak | 117–118 |
| 457 | RUS | sphere (½ρV), balloon, spherical pendulum (formula and values) | Chernyak | 118–120 |
| 458 | RUS | ship hull (planar motion), k11, k22, k66 (formula) | Kryvyi | 4–5, 11–12 |
| 459 | RUS | equivalent triaxial ellipsoid a = L/2, b = B/2, c = T (formula) | Kryvyi | 5–8 |
| 460 | RUS | 16 ship types (k11, k22, k66, table 3) (values) | Kryvyi | 10 |
| 461 | RUS | body of arbitrary shape, sphere (problem statements) (formula) | Continuum Mechanics in Problems, Vol. 1: Theory and Problems | 202, 207 |
| 462 | RUS | circular cylinder (μ = πρa²) (formula) | Continuum Mechanics in Problems, Vol. 2: Answers and Solutions | 145 |
| 463 | RUS | sphere (μ = 2/3·πρa³), plate (formula) | Continuum Mechanics in Problems, Vol. 2: Answers and Solutions | 146 |
| 464 | RUS | bubble (μ = M1/2, acceleration ≈ 2g) (formula and values) | Continuum Mechanics in Problems, Vol. 2: Answers and Solutions | 147 |
| 465 | RUS | body in an ideal fluid (matrices A, B, C) (formula) | Borisov, Dynamics of a Rigid Body | 70–71, 165, 185, 265 |
| 466 | RUS | sphere ((2π/3)a³ρ), spherical pendulum (formula and values) | Vekshtein | 126, 131 |
| 467 | RUS | body of arbitrary shape (tensor m_ik) (formula) | Vekshtein | 126–128 |
| 468 | RUS | two spheres on a thin rod (formula) | Vekshtein | 129–130 |
| 469 | RUS | long cylinder in a coaxial pipe (formula) | Vekshtein | 132 |
| 470 | RUS | triaxial ellipsoid (formula) | Grigolyuk | 15–17 |
| 471 | RUS | spheroid, sphere, cylinder (formula) | Grigolyuk | 17–19 |
| 472 | RUS | circular disk (near a bottom and in a cylindrical vessel, table 1) (formula and values) | Grigolyuk | 20–23 |
| 473 | RUS | elliptic cylinder, plates (formula) | Grigolyuk | 26–27 |
| 474 | RUS | wedge, cone, sphere during immersion (formula) | Grigolyuk | 35–46 |
| 475 | RUS | body of revolution with fins, symmetries, section method (formula) | Grumondz, Algorithms of Aerohydroballistic Design | 40–43 |
| 476 | RUS | axisymmetric vehicle entering and leaving water (formula) | Grumondz, Algorithms of Aerohydroballistic Design | 55, 59, 61, 65–67 |
| 477 | RUS | body of arbitrary shape, symmetries of the λik matrix (formula) | Grumondz, Airship Aeromechanics | 235–243 |
| 478 | RUS | triaxial ellipsoid and spheroid (k11…k66) (formula) | Grumondz, Airship Aeromechanics | 246–248 |
| 479 | RUS | equivalent spheroid (formula) | Grumondz, Airship Aeromechanics | 248–249 |
| 480 | RUS | body of revolution of arbitrary profile (section method) (formula) | Grumondz, Airship Aeromechanics | 249–250 |
| 481 | RUS | body of revolution with fins (formula) | Grumondz, Airship Aeromechanics | 250–251 |
| 482 | RUS | spheroid near a wall (formula) | Grumondz, Airship Aeromechanics | 253–255 |
| 483 | RUS | airships D1 and D2.1/D2.2 (numerical examples) (values) | Grumondz, Airship Aeromechanics | 346–349, 372 |
| 484 | RUS | body of arbitrary shape (λik, axis transformation) (formula) | Degtyar | 42–48 |
| 485 | RUS | body of revolution with tail stabilizers, truncated cone (table 2.1) (formula and values) | Degtyar | 48–52 |
| 486 | RUS | body of revolution in a disturbed fluid (formula) | Degtyar | 101–113 |
| 487 | RUS | body of revolution near a screen (table 5.2) (formula and values) | Degtyar | 143–145, 162 |
| 488 | RUS | rocket in a flooded silo (graphs) (values) | Degtyar | 176–186 |
| 489 | RUS | body of arbitrary shape (formula) | Landau | 50 |
| 490 | RUS | sphere (½ of the displaced fluid mass) (formula and values) | Landau | 54 |
| 491 | RUS | body of arbitrary shape (36 coefficients) (formula) | Loitsyansky, Mechanics of Fluid and Gas | 325–327 |
| 492 | RUS | circular cylinder (πρa² per unit length) (formula and values) | Loitsyansky, Mechanics of Fluid and Gas | 327 |
| 493 | RUS | sphere (½ of the fluid mass in its volume) (formula and values) | Loitsyansky, Mechanics of Fluid and Gas | 328 |
| 494 | RUS | body of revolution and spheroid (formula) | Loitsyansky, Mechanics of Fluid and Gas | 328–329 |
| 495 | RUS | sphere (½ of the fluid mass in its volume) (formula and values) | Loitsyansky, Dynamics | 30 |
| 496 | RUS | circular cylinder (formula and values) | Milne-Thomson | 229–232 |
| 497 | RUS | elliptic cylinder (formula) | Milne-Thomson | 239, 243 |
| 498 | RUS | sphere (D = 2/3·πa³, sphere in a spherical vessel) (formula and values) | Milne-Thomson | 442, 470 |
| 499 | RUS | prolate and oblate spheroids (formula) | Milne-Thomson | 450 |
| 500 | RUS | body with a liquid-filled cavity (formula) | Milne-Thomson | 501 |
| 501 | RUS | airfoil (conformal mapping) (formula) | Sedov, Plane Problems | 30–37 |
| 502 | RUS | ellipse, plate, Joukowski airfoils (table 1) (formula and values) | Sedov, Plane Problems | 40 |
| 503 | RUS | two plates on one line (formula) | Sedov, Plane Problems | 68–71 |
| 504 | RUS | airfoils in a cascade (formula) | Sedov, Plane Problems | 160–166 |
| 505 | RUS | plate in a compressible fluid (graphs) (values) | Sedov, Plane Problems | 117–118 |
| 506 | RUS | body of arbitrary shape (formula) | Sedov, Continuum Mechanics | 180–183 |
| 507 | RUS | body of revolution (formula) | Sedov, Continuum Mechanics | 184–186 |
| 508 | RUS | sphere (λ = ρV/2) (formula and values) | Sedov, Continuum Mechanics | 186–187 |
| 509 | RUS | body of arbitrary shape (m_ik = 4πρα_ik − ρV0δ_ik) (formula) | Falkovich, Modern Hydrodynamics | 42–44 |
| 510 | RUS | sphere, bubble (ρV/2, acceleration ≈ 2g), spherical pendulum (formula and values) | Falkovich, Modern Hydrodynamics | 41, 161 |
| 511 | RUS | body of revolution, airship envelope (k11 ≈ 0.08; k22 ≈ 0.85) (formula and values) | Shcherbakov | 23–27, 32–33 |

## Literature

All 153 books referenced in the table, combined across languages (RUS/ENG/DEU) and sorted by first author (Russian authors are shown in Latin transliteration, so the same author appears next to each other). Books without a stated author are listed by title. The `book` column of the table gives the surname of the first author; if the table contains several books by the same author, the first words of the title are added.

1. ANSYS. Aqwa Theory Manual [ENG]
2. Aref. A First Course in Computational Fluid Dynamics [ENG]
3. Arslan. Frequency-Domain Ship Motion Code with Python Programming Language [ENG]
4. Basic Analytical and Numerical Computation of Added Mass in Ship Vibration Analysis [ENG]
5. Berté. A 6-DOF Submarine Manoeuvrability Prediction Code. Part I: Development and Validation [ENG]
6. Bertram. Practical Ship Hydrodynamics [ENG]
7. Biringen. An Introduction to Computational Fluid Mechanics by Example [ENG]
8. Birk. Fundamentals of Ship Hydrodynamics: Fluid Mechanics, Ship Resistance and Propulsion [ENG]
9. Birkgof. Gidrodinamika. Metod, fakty, podobie (1963) [RUS]
10. Birkhoff. Hydrodynamics [ENG]
11. Bohlmann. Berechnung hydrodynamischer Koeffizienten von Ubooten zur Vorhersage des Bewegungsverhaltens [DEU]
12. Borisov. Dynamics of a Rigid Body (2001) [RUS]
13. Borisov. Rigid Body Dynamics [ENG]
14. Brebbia. Computational Ballistics III [ENG]
15. Brennen. A Review of Added Mass and Fluid Inertia [ENG]
16. Brennen. Cavitation and Bubble Dynamics (1995) [ENG]
17. Carlton. Marine Propellers and Propulsion, 2nd ed. [ENG]
18. Chen. Design Guide for Calculating Hydrodynamic Mass. Part 1: Circular Cylindrical Structures [ENG]
19. Chernyak. Mexanika sploshnyx sred. Ucheb. posob. dlya vuzov (2006) [RUS]
20. Continuum Mechanics in Problems, Vol. 1: Theory and Problems [RUS]
21. Continuum Mechanics in Problems, Vol. 2: Answers and Solutions [RUS]
22. Corbo. Pump Rotordynamics Made Simple [ENG]
23. Dabssi. Hydrodynamic Coefficients and Forces on Multihulls in Shallow Water with Constant or Variable Depth [ENG]
24. De Barros. Progress Towards a Method for Predicting AUV Derivatives [ENG]
25. Degtyar, Pegov. Hydrodynamics of Ballistic Missiles of Submarines (2004) [RUS]
26. Dey. Fluvial Hydrodynamics: Hydrodynamic and Sediment Transport Phenomena [ENG]
27. DNV GL. Modelling and Analysis of Marine Operations, RP-N103 [ENG]
28. Do. Control of Ships and Underwater Vehicles: Design for Underactuated and Nonlinear Marine Systems [ENG]
29. Do. Determination of Added Mass and Inertia Moment of Marine Ships Moving in 6 Degrees of Freedom [ENG]
30. Do. Influence of Added Water Mass on Ship Structure Vibration Parameters in Virtual and Real Conditions [ENG]
31. ELecture2015 Note18 [ENG]
32. Ellenrieder. Control of Marine Vehicles [ENG]
33. Emanuel. Analytical Fluid Dynamics, 2nd ed. [ENG]
34. Falkovich. Fluid Mechanics, 2nd ed. [ENG]
35. Falkovich. Modern Hydrodynamics: A Short Course (2014) [RUS]
36. Falnes. Ocean Waves and Oscillating Systems [ENG]
37. Faltinsen. Hydrodynamics of High-Speed Marine Vehicles [ENG]
38. Fossen. Guidance and Control of Ocean Vehicles [ENG]
39. Fossen. Handbook of Marine Craft Hydrodynamics and Motion Control [ENG]
40. Fossen. Marine Control Systems: Guidance, Navigation and Control of Ships, Rigs and Underwater Vehicles [ENG]
41. Frank. Oscillation of Cylinders in or below the Free Surface of Deep Fluids [ENG]
42. Friel. Hydrodynamic Investigation of Design Parameters for a Cylindrical Type Floating Solar System [ENG]
43. Gaythwaite. Design of Marine Facilities [ENG]
44. Ghassemi. The Added Mass Coefficient Computation of Sphere, Ellipsoid and Marine Propellers Using Boundary Element Method [ENG]
45. Graebel. Advanced Fluid Mechanics (AP, 2007) [ENG]
46. Greenhow. Added Mass and Damping of Horizontal Circular Cylinder Sections [ENG]
47. Grift. The Hydrodynamics of Rowing Propulsion: An Experimental Study [ENG]
48. Grigolyuk. Interaction of Elastic Structures with Fluid (Impact and Immersion) [RUS]
49. Grue. Topics in Marine Hydrodynamics with Numerical Methods and MATLAB Scripting [ENG]
50. Grumondz. Airship Aeromechanics [RUS]
51. Grumondz, Yakovlev. Algorithms of Aerohydroballistic Design (1994) [RUS]
52. Gudmestad. Hydrodynamic Coefficients for Calculation of Hydrodynamic Loads on Offshore Truss Structures [ENG]
53. Gudmestad. Marine Technology and Operations: Theory and Practice [ENG]
54. Guedes Soares (ed.). Analysis and Design of Marine Structures [ENG]
55. Guyon. Physical Hydrodynamics [ENG]
56. Havelock, Wigley. The Collected Papers of Sir Thomas Havelock on Hydrodynamics [ENG]
57. Howe. Hydrodynamics and Sound [ENG]
58. Hua. Design and Hydrodynamic Coefficient Identification of Deep-Sea Unmanned Underwater Vehicles [ENG]
59. Huang. Numerical Investigation of Hydrodynamic Coefficients and Wake Characteristics of a Deep-Sea Mining Vehicle [ENG]
60. Hutchison. Numerical Investigation of Ducted Propeller Added Mass [ENG]
61. Imlay. The Complete Expressions for Added Mass of a Rigid Body Moving in an Ideal Fluid [ENG]
62. Inzartsev. Underwater Vehicles (2008) [ENG]
63. Irschik. Dynamics of Mechanical Systems with Variable Mass [ENG]
64. Jakuba. Modeling and Control of an Autonomous Underwater Vehicle with Combined Foil Thruster Actuators [ENG]
65. Jones. The Calculation of Hydrodynamic Coefficients for Underwater Vehicles [ENG]
66. Journee. Offshore Hydromechanics [ENG]
67. Justino. Computation of Hydrodynamic Coefficients for Submerged Spheres: A Comprehensive Analysis [ENG]
68. Kahramanoğlu. Investigation of Scale Effects on Linear Vertical Maneuvering Derivatives of a Submarine [ENG]
69. Kambe. Elementary Fluid Mechanics (WorldSci, 2007) [ENG]
70. Kämpf. Flugmechanik und Flugregelung von Luftschiffen [DEU]
71. Kim. Estimation of the Hydrodynamic Derivatives by RaNS Simulation of Planar Motion Mechanism Test [ENG]
72. Kiycak. Scale Effects on the Linear Hydrodynamic Coefficients of DARPA SUBOFF [ENG]
73. Koo. Simplified Formulas of Heave Added Mass Coefficients at High Frequency for Various Two-Dimensional Bodies in a Finite Water Depth [ENG]
74. Korde. Engineering Mathematics for Marine Applications [ENG]
75. Kornev. Dynamics and Stability of Racing Boats with Air Wings [ENG]
76. Korotkin. Added Masses of Ship Structures (Fluid Mechanics and Its Applications) [ENG]
77. Kraemer. Analysis of the Added Mass of a Barge in … [ENG]
78. Kryvyi. Determination of Added Masses and Moments for the Planar Motion of a Ship [RUS]
79. Kundu. Fluid Mechanics, 6th ed.: Solution Manual [ENG]
80. Landau. Theoretical Physics, Vol. 6: Fluid Mechanics [RUS]
81. Lewandowski. The Dynamics of Marine Craft: Maneuvering and Seakeeping [ENG]
82. Lewis (ed.). Principles of Naval Architecture, Second Revision, Volume III: Motions in Waves and Controllability [ENG]
83. Li. Airship Dynamics Modeling: A Literature Review [ENG]
84. Li. Dynamics Modeling and Simulation of Flexible Airships [ENG]
85. Lin. The Hydrodynamic Analysis of the Fully Appended DARPA SUBOFF Model in the SPMM Tests Integrating the LES Model with the Dynamic Mesh Method [ENG]
86. Lind. Simulation and Control of Submarines [ENG]
87. Loitsyansky, Lurie. Dynamics, Vol. 2 (1983) [RUS]
88. Loitsyansky. Mechanics of Fluid and Gas (Classics of Russian Science), 7th ed., 2003 [RUS]
89. Maheri. Experimental Added Mass in Modal Vibrati… [ENG]
90. Manneville. Elements of Fluid Dynamics: Instabilities, Chaos and Turbulence [ENG]
91. Massey. Mechanics of Fluids, 9th ed. [ENG]
92. Mavrakos. Hydrodynamic Coefficients for a Thick-Walled Bottomless Cylindrical Body Floating in Water of Finite Depth [ENG]
93. Mentzoni. Hydrodynamic Coefficients of Simplified Subsea Structures [ENG]
94. Milne-Thomson. Theoretical Hydrodynamics [RUS]
95. Miloh. Mass Coefficients of a Torus [ENG]
96. Miloh. The Added Mass Coefficients of a Torus [ENG]
97. Mironer. Engineering Fluid Mechanics [ENG]
98. Molin. Offshore Structure Hydrodynamics [ENG]
99. Molland. The Maritime Engineering Reference Book [ENG]
100. Monterrubio. Efficient Calculation of the Added Mass Matrix for Vibration Analysis of Submerged Structures [ENG]
101. Moraga, Boneto, Drew, Lahey. The Virtual Mass and Lift Force on an Oblate Ellipsoid in Rotating and Straining Inviscid Flow [ENG]
102. Mueller. Development of an Aerodynamic Model and … [ENG]
103. Mundekkatt. Numerical Simulation of Transport Ships Dynamics when Launching Wind Turbine Floating Fundament [ENG]
104. Munk. The Aerodynamic Forces on Airship Hulls [ENG]
105. Nesteruk (ed.). Supercavitation: Advances and Perspectives [ENG]
106. Newman. Marine Hydrodynamics (2018) [ENG]
107. Newman. Marine Hydrodynamics (old edition) [ENG]
108. Padfield. Helicopter Flight Dynamics [ENG]
109. Patton. An Experimental Determination of Hydrodynamic Masses and Mechanical Impedances [ENG]
110. Patton. Hydrodynamic Mass of Bodies in a Fluid [ENG]
111. Porter. Pressure Distributions, Added-Mass and Damping Coefficients for Cylinders Oscillating in a Free Surface [ENG]
112. Potter. An Introduction to Fluid Mechanics, 6th ed. [ENG]
113. Rahman. Mechanics of Real Fluids [ENG]
114. Ramli. Hydrodynamic Coefficients for a 3-D Uniform Flexible Barge Using Weakly Compressible Smoothed Particle Hydrodynamics [ENG]
115. Renilson. Submarine Hydrodynamics, 2nd ed. [ENG]
116. Review of Added Mass and Fluid Inertial Forces (1982) [ENG]
117. Ridley. Submarine Dynamic Modeling [ENG]
118. Roberts (ed.). Advances in Unmanned Marine Vehicles [ENG]
119. Safari. Estimation of Hydrodynamic Coefficients and Simplification of the Depth Model of an AUV Using CFD and Sensitivity Analysis [ENG]
120. Saunders. Hydrodynamics in Ship Design, Volume Two [ENG]
121. Schou. Estimating Hydrodynamic Coefficients for Floating Offshore Structures from Movement Data Using Physics-Informed Neural Networks [ENG]
122. Sedov. Continuum Mechanics, Vol. 2 [RUS]
123. Sedov. Plane Problems of Hydrodynamics and Aerodynamics [RUS]
124. Sedov. Two-Dimensional Problems in Hydrodynamics and Aerodynamics [ENG]
125. Sen. Determination of Added Mass and Inertia Moment of Marine Ships Moving in 6 Degrees of Freedom [ENG]
126. Severholt. Generic 6-DOF Added Mass Formulation [ENG]
127. Shcherbakov. Theory of Airship Flight [RUS]
128. Shi. Advanced Model Predictive Control for Autonomous Marine Vehicles [ENG]
129. Sigrist. Fluid-Structure Interaction: An Introduction to Finite Element Coupling [ENG]
130. Sinha. Elementary Flight Dynamics with an Introduction to Bifurcation and Continuation Methods, 2nd ed. [ENG]
131. Soares. Ship Dynamics and Hydrodynamics [ENG]
132. Song. Evaluation of Energy Consumption and Motion Accuracy for Underwater Gliders Based on Quadrant Analysis [ENG]
133. Sørensen. Marine Control Systems: Lecture Notes [ENG]
134. Sørensen. Marine Control Systems: Propulsion and Motion Control of Ships and Ocean Structures [ENG]
135. Spurk. Fluid Mechanics, 3rd ed. [ENG]
136. Sun. Dynamics Modeling and Hydrodynamic Coefficients Identification of the Wave Glider [ENG]
137. Sutulo. Mathematical Models for Simulation of Manoeuvring Performance of Ships [ENG]
138. Tasai. On the Damping Force and Added Mass of Ships Heaving and Pitching [ENG]
139. Techet. Added Mass Derivation (05.09.16) [ENG]
140. Techet. Added Mass, 2016: Hydrodynamics, Reading 6 [ENG]
141. Techet. L 01 Added Mass (05.09.15) [ENG]
142. Thuné. Simulation of Submarine Manoeuvring [ENG]
143. Trivedi. Analysis of Added Mass Effect on Surface Ships Subjected to Underwater Explosions [ENG]
144. Tupper. Introduction to Naval Architecture, 4th ed. [ENG]
145. Vekshtein. Physics of Continuous Media in Problems [RUS]
146. Vugts. The Hydrodynamic Coefficients for Swaying, Heaving and Rolling Cylinders in a Free Surface [ENG]
147. Wang. Dynamic Modeling of an Autonomous Underwater Vehicle [ENG]
148. Wang, Xiao, Wang, Qi. Numerical Simulation and Analysis of Added Mass for the Underwater Variable Speed Motion of Small Objects [ENG]
149. White. Fluid Mechanics, 8th ed. [ENG]
150. Wu. Elements of Vorticity Aerodynamics [ENG]
151. Wu. Practical Design of Ships and Other Floating Structures, 8th PRADS 2001 (2-Volume Set) [ENG]
152. Xu. Convergence Analysis of Hydrodynamic Coefficients Estimation Using Regularization Filter Functions on Free-Running Ship Model Tests with Noise [ENG]
153. Zhao. Dynamic Analysis of Underwater Torpedo during Straight-Line Navigation [ENG]
