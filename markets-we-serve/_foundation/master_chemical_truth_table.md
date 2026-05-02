# Master Chemical Truth Table — Noah Chemicals

_Built: 2026-04-29 18:55 | Window: 2023-04-29 → 2026-04-29_

This is the canonical list of every chemical Noah Chemicals shipped in the last 3 years, 
derived from the IN15 invoice Excel files (3,650 chemical line items) and cross-referenced with 
2,699 closed-won HubSpot deals from the same window. **Every row in this table traces back to 
at least one real invoice.**

## Validation rules used

- **No invented CAS numbers.** If the source text didn't contain a verified CAS string, 
  the row reads `LOOKUP_NEEDED`. Of 784 chemicals, 43 had a CAS embedded in the source text.
- **No invented certifications.** Only labels actually present in PRODDESC/dealname text 
  (USP, ACS Reagent, FCC, NSF/ANSI 60, MIL-Spec, AMS-Spec, BASF Spec, UOP Spec, etc.).
- **Sub-industry tags are PROVISIONAL.** Hub assignment is inferred from the customer name, 
  not from chemistry. Every tag is marked `PROVISIONAL` and every row is flagged 
  `kelly_review_status = PENDING_REVIEW`.
- **Excluded line items:** SKUs starting `/` (`/MISC.`, `/MSDS`, `/HAZARD`, `/FRGHT`, `/PACK`), 
  service/labor SKUs (`13075`, `WB####`), and rows with $0 revenue and $0 cost.

## Hub summary

| Hub | Chemicals | 3-yr GP |
|---|---|---|
| Advanced Manufacturing | 98 | $3,180,815 |
| Aerospace & Defense | 138 | $2,918,209 |
| Life Sciences & Pharma | 148 | $2,485,895 |
| Unclassified | 362 | $1,071,580 |
| Energy & Nuclear | 9 | $353,255 |
| Consumer & Industrial | 29 | $347,493 |

Total: **784 chemicals, $10,357,248 GP**

## Chemicals grouped by primary hub

### Aerospace & Defense (138 chemicals, $2,918,209 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 2 | ZINC OXIDE, CALCINED, 99.995% pure, -20 mesh, (Special for SpaceX), ZnO | LOOKUP_NEEDED | $378,292 | 18 | SpaceX | — |
| 4 | SODIUM PHOSPHATE TRIBASIC, DODECAHYDRATE, Chemically pure, -10/+25 mesh, (Trisod | LOOKUP_NEEDED | $325,164 | 1 | Southwest Research Institute | — |
| 7 | CALCIUM CHROMATE, MIL-C-48038, 3 microns max., CaCrO₄ | LOOKUP_NEEDED | $239,016 | 6 | Eagle Picher Technologies / Networks Electronic / MT Chemica | MIL-Spec |
| 10 | LEAD (II) NITRATE, ACS Reagent, crystal,  Pb(NO₃)₂ | 10099-74-8 | $202,132 | 15 | Olin Winchester, LLC / B3 Systems, Inc. | ACS Reagent / Reagent |
| 11 | ZINC OXIDE, 99.9% pure, ACS Reagent, -200 mesh, ZnO | LOOKUP_NEEDED | $186,885 | 17 | SpaceX / I-Spec. Co., Ltd / Chemsavers | ACS Reagent / Reagent |
| 13 | SURROGATE WASTE, IHI Simulant for VSL (2024) | LOOKUP_NEEDED | $166,563 | 2 | Catholic University of America | — |
| 19 | MOLYBDENUM (IV) SULFIDE, 99% pure, 4-10 microns by Fisher, AMS-M-7866, (Molybden | LOOKUP_NEEDED | $98,383 | 16 | ASRC Federal / Metal Improvement Co., LLC / SAIC | AMS-Spec |
| 26 | LEAD ACETATE / CHROMIUM ACETATE, SOLUTION, Pb: 0.05%, Cr: 0.0625%, special for F | LOOKUP_NEEDED | $78,793 | 3 | Franklin Engineering Group Inc. | — |
| 29 | LEAD (II) ACETATE, TRIHYDRATE, 30% SOLUTION, 99% pure, 16.4% Pb,  Pb(OOCCH₃)₂.3H | LOOKUP_NEEDED | $66,262 | 2 | B3 Systems, Inc. | — |
| 31 | CHROMIUM (III) CHLORIDE, HEXAHYDRATE, 2 Molar solution, 7.76% Cr, CrCl₃.6H₂O | LOOKUP_NEEDED | $63,704 | 1 | B3 Systems, Inc. | — |
| 35 | ZINC SULFIDE, Schott Part Number 6366819, Drawing No. A426479 Rev. B, (99.99% pu | LOOKUP_NEEDED | $57,413 | 1 | SCHOTT North America, Inc. | — |
| 41 | POTASSIUM BROMIDE, ACS Reagent, granular,  KBr | LOOKUP_NEEDED | $54,524 | 24 | Eagle Picher Technologies / Ambyth Chemical | ACS Reagent / Reagent |
| 42 | ALUMINUM HYDROXIDE, Reagent, -325 mesh, (Aluminum Oxide, Trihydrate), Al(OH)₃ or | LOOKUP_NEEDED | $52,491 | 27 | Infiniumco / Atkins Enery Federal EPC Inc. / 0015013 | Reagent |
| 50 | SURROGATE WASTE FEED, Cluster 13 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $44,696 | 2 | Catholic University of America | — |
| 51 | MOLYBDENUM METAL, POWDER, 99.8% pure, 2.5-4.5 microns, Mo | LOOKUP_NEEDED | $44,646 | 6 | Austin Star Detonator Company | — |
| 54 | GERMANIUM (IV) OXIDE, 99.999% pure, -200 mesh, (Germanium Dioxide), GeO₂ | LOOKUP_NEEDED | $40,258 | 8 | Biolase, Inc / Cascade Columbia Distribution | — |
| 55 | MONOCHLOROBENZENE/NAPHTHALENE, 8.6% Naphthalene, C6H5C1 C10H8 | LOOKUP_NEEDED | $40,217 | 1 | B3 Systems, Inc. | — |
| 58 | BARIUM (II) NITRATE, 99% pure, -60/+100 mesh, Ba(NO₃)₂ | LOOKUP_NEEDED | $38,729 | 16 | BiSN Oil Tools LLC | — |
| 61 | THALLIUM (I) CARBONATE, 99.99% pure, -30 mesh, (Thallous Carbonate), Tl₂CO₃ | 6533-73-9 | $36,415 | 3 | Luxium Solutions | — |
| 62 | BISMUTH (III) OXIDE, 99.9% pure, -325 mesh, (Bismuth Trioxide), Bi₂O₃ | LOOKUP_NEEDED | $35,938 | 25 | Pyrotechnique by Grucci, Inc. / Univar Solutions USA, Inc. / | — |
| 64 | SURROGATE WASTE FEED, Cluster 5 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $35,653 | 2 | Catholic University of America | — |
| 71 | SURROGATE WASTE FEED, Melter Feed 23Tuning-3L Adjusted for Olivine for VSL | LOOKUP_NEEDED | $32,703 | 1 | Catholic University of America | — |
| 74 | ZIRCONIUM HYDROXIDE, HYDRATE, 99% pure, -50 mesh, Zr(OH)₄.xH₂O | 14475-63-9 | $30,357 | 7 | Catholic University of America / Posco Future M Co., LTD / T | — |
| 75 | SURROGATE WASTE FEED, Cluster 3 DFHLW Feed for VSL | LOOKUP_NEEDED | $30,033 | 2 | Catholic University of America | — |
| 76 | SURROGATE WASTE FEED, Melter Feed 23Tuning-3 REVISED for VSL | LOOKUP_NEEDED | $29,529 | 2 | Catholic University of America | — |
| 78 | MOLYBDENUM (IV) SULFIDE, 99% pure, 4-10 microns by Fisher, 284 gm (10oz) bottles | LOOKUP_NEEDED | $29,202 | 12 | SAIC / ASRC Federal | AMS-Spec |
| 81 | SURROGATE WASTE, Batch #1 SWARM Supernatant for Battelle (20 | LOOKUP_NEEDED | $26,958 | 1 | Battelle Pacific N. W. Labs | — |
| 83 | NICKEL (II) NITRATE, HEXAHYDRATE, 99.5% pure, -4 mesh, (Nickelous Nitrate, Hexah | LOOKUP_NEEDED | $25,123 | 16 | Austin Star Detonator Company / ENGI-Mat / Serveca Inc. | — |
| 92 | NEODYMIUM OXIDE, 99.5% pure, -325 mesh,  Nd₂O₃ | LOOKUP_NEEDED | $21,600 | 1 | Catholic University of America | — |
| 93 | MERCURY (II) NITRATE, 6.15% SOLUTION, 99% pure, 3.8% Hg, for B3 Systems | LOOKUP_NEEDED | $21,177 | 1 | B3 Systems, Inc. | — |
| 99 | CHROMIUM (VI) OXIDE, 7 Molar solution, 25.26% Cr, CrO₃ | LOOKUP_NEEDED | $19,830 | 1 | B3 Systems, Inc. | — |
| 106 | SURROGATE WASTE FEED, UK23-SIXEP25 Feed for VSL | LOOKUP_NEEDED | $18,833 | 1 | Catholic University of America | — |
| 110 | TETRACHLOROETHYLENE, (Perchloroethylene, EthyleneTetrachloride), Cl₂CCCl₂ | LOOKUP_NEEDED | $18,034 | 5 | Franklin Engineering Group Inc. | — |
| 138 | TITANIUM (IV) OXIDE, ANATASE & RUTILE, 99.7% pure, 0.2 micron, (Titanium Dioxide | LOOKUP_NEEDED | $13,388 | 2 | Sandia National Laboratories | — |
| 139 | SURROGATE WASTE FEED, Melter Feed BNIB83 for VSL | LOOKUP_NEEDED | $12,824 | 1 | Catholic University of America | — |
| 143 | SURROGATE WASTE FEED, Melter Feed 23Tuning-2 REVISED for VSL | LOOKUP_NEEDED | $12,169 | 1 | Catholic University of America | — |
| 147 | SURROGATE WASTE FEED, Melter Feed 23Tuning-1 for VSL | LOOKUP_NEEDED | $11,992 | 1 | Catholic University of America | — |
| 151 | SURROGATE WASTE FEED, Cluster 1 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $11,687 | 1 | Catholic University of America | — |
| 153 | LIQUID SILICATE, PC- 4002 binder, raw material for SpaceX kit | LOOKUP_NEEDED | $11,476 | 25 | SpaceX | — |
| 156 | SURROGATE WASTE FEED,  AP-107/AP-106 Feed for VSL (2025) | LOOKUP_NEEDED | $11,382 | 1 | Catholic University of America | — |
| 157 | SURROGATE WASTE FEED, Cluster 11 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $11,327 | 1 | Catholic University of America | — |
| 159 | SURROGATE WASTE FEED, AN-105 Envelope A1 Simulant Recipe #31mod w/GFR for BNI | LOOKUP_NEEDED | $10,900 | 1 | Catholic University of America | — |
| 160 | LEAD (II) NITRATE, 1 Molar solution, 16.46% Pb, Pb(NO₃)₂ | LOOKUP_NEEDED | $10,881 | 1 | B3 Systems, Inc. | — |
| 165 | SURROGATE WASTE FEED, Cluster 6 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $10,567 | 1 | Catholic University of America | — |
| 167 | MAGNESIUM CHLORIDE, HEXAHYDRATE,96.99% pure, crystal, (Magnesium Dichloride, Hex | LOOKUP_NEEDED | $10,380 | 5 | Southwest Research Institute | — |
| 171 | ALUMINUM OXIDE, 99.8% pure, -325 mesh, (Alumina),Al₂O₃ | LOOKUP_NEEDED | $10,147 | 9 | SpaceX / Catholic University of America | — |
| 177 | SURROGATE WASTE FEED, Simulant, AP-107 DFHLW, for PNNL | LOOKUP_NEEDED | $9,244 | 1 | Battelle Pacific N. W. Labs | — |
| 180 | LEAD ACETATE, Solution with 1% as elemental Pb | LOOKUP_NEEDED | $9,206 | 3 | B3 Systems, Inc. | — |
| 184 | C3073 | LOOKUP_NEEDED | $9,092 | 1 | Catholic University of America | — |
| 188 | SURROGATE WASTE FEED, Simulant, AN-105 DFHLW, for PNNL | LOOKUP_NEEDED | $8,831 | 1 | Battelle Pacific N. W. Labs | — |
| 194 | LEAD (II) ACETATE, TRIHYDRATE, 99% pure, -10 mesh,  Pb(OOCCH₃)₂.3H₂O | LOOKUP_NEEDED | $8,431 | 1 | B3 Systems, Inc. | — |
| 196 | SURROGATE WASTE, Batch #2 SWARM Supernatant for Battelle (20 | LOOKUP_NEEDED | $8,304 | 1 | Battelle Pacific N. W. Labs | — |
| 200 | SURROGATE WASTE, Batch #4 SWARM Supernatant for Battelle (2025) | LOOKUP_NEEDED | $7,977 | 1 | Battelle Pacific N. W. Labs | — |
| 206 | SURROGATE WASTE, Batch #5 SWARM Supernatant for Battelle (2025) | LOOKUP_NEEDED | $7,714 | 1 | Battelle Pacific N. W. Labs | — |
| 210 | SURROGATE WASTE FEED, Cluster 8 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $7,426 | 1 | Catholic University of America | — |
| 214 | MAGNESIUM OXIDE, 98% pure, -100 mesh,  MgO | LOOKUP_NEEDED | $7,164 | 6 | Infiniumco / MakrMed / SKINN Cosmetics | — |
| 227 | NICKEL (II) SULFATE, Solution with 2.5% elemental Ni | LOOKUP_NEEDED | $6,411 | 2 | B3 Systems, Inc. | — |
| 229 | 30 Calendar Days of Material Storage  (15Oct25 - 13Nov25) | LOOKUP_NEEDED | $6,336 | 4 | B3 Systems, Inc. | — |
| 237 | SURROGATE WASTE, Batch #3 SWARM Supernatant for Battelle (2025) | LOOKUP_NEEDED | $5,838 | 1 | Battelle Pacific N. W. Labs | — |
| 240 | LITHIUM CARBONATE, ACS Reagent, -40 mesh, Li₂CO₃ | LOOKUP_NEEDED | $5,751 | 2 | Catholic University of America | ACS Reagent / Reagent |
| 241 | SURROGATE WASTE FEED, Cluster 16 DFHLW Feed for VSL 2025 | LOOKUP_NEEDED | $5,564 | 1 | Catholic University of America | — |
| 270 | CALCIUM CARBONATE, 98% pure, 16 microns avg, (Special for SpaceX), CaCO₃ | LOOKUP_NEEDED | $4,657 | 6 | SpaceX | — |
| 285 | SILICON DIOXIDE, 99.5% pure, -200 mesh, Glass Former,  SiO₂ | LOOKUP_NEEDED | $4,051 | 3 | Catholic University of America | — |
| 289 | CHROMIUM (III) ACETATE, 50% SOLUTION, 99% pure, 11.5% Cr, (Chromic Acetate), Cr( | LOOKUP_NEEDED | $3,987 | 3 | Franklin Engineering Group Inc. | — |
| 330 | SULFUR, POWDER, 99.5% pure, -100 mesh,  S | LOOKUP_NEEDED | $3,042 | 4 | Southwest Research Institute / BeanTown Chemical Corp / Lyte | — |
| 333 | Chromium Nitrate Solution, 0.3% as Cr | LOOKUP_NEEDED | $2,990 | 1 | B3 Systems, Inc. | — |
| 344 | C3074 | LOOKUP_NEEDED | $2,722 | 1 | Franklin Engineering Group Inc. | — |
| 350 | SODIUM DICHROMATE, 1.43% SOLUTION, 0.5%Cr | LOOKUP_NEEDED | $2,635 | 2 | Franklin Engineering Group Inc. / B3 Systems, Inc. | — |
| 356 | Potassium Chloride Solution with 10% as Cl | LOOKUP_NEEDED | $2,591 | 1 | B3 Systems, Inc. | — |
| 357 | C3062 | LOOKUP_NEEDED | $2,580 | 1 | B3 Systems, Inc. | — |
| 359 | MERCURY (II) ACETATE 1.67% Solution, 1.05% as Hg (Mercuric acetate solution) Hg( | LOOKUP_NEEDED | $2,549 | 1 | B3 Systems, Inc. | — |
| 364 | MSO DISPERSION, 0.164% PbO, 22.9% TiO2, special for Eastman | LOOKUP_NEEDED | $2,452 | 2 | Franklin Engineering Group Inc. | — |
| 366 | SODIUM DICHROMATE, DIHYDRATE, 2.99% SOLUTION, 1.043% Cr, special for Eastman, Na | LOOKUP_NEEDED | $2,446 | 2 | Franklin Engineering Group Inc. | — |
| 370 | NEODYMIUM OXIDE, 99.9% pure, -325 mesh,  Nd₂O₃ | LOOKUP_NEEDED | $2,355 | 1 | Catholic University of America | — |
| 372 | Lead Nitrate Solution, 0.25% as Pb | LOOKUP_NEEDED | $2,345 | 1 | B3 Systems, Inc. | — |
| 389 | SODIUM TETRABORATE, DECAHYDRATE, 99.5% pure, crystalline, (Borax), Na₂B₄O₇.10H₂O | LOOKUP_NEEDED | $2,075 | 1 | Catholic University of America | — |
| 409 | MERCURY (II) CHLORIDE, ACS Reagent, powder, (Mercuric Chloride), HgCl₂ | LOOKUP_NEEDED | $1,704 | 1 | Eagle Picher Technologies | ACS Reagent / Reagent |
| 412 | CHROMIUM METAL, POWDER, 99.5% pure, minimum 96% -325 mesh, Cr | LOOKUP_NEEDED | $1,683 | 3 | B3 Systems, Inc. / SpaceX | — |
| 413 | SODIUM CARBONATE, ANHYDROUS, 99.5% pure, powder,  Na₂CO₃ | LOOKUP_NEEDED | $1,659 | 4 | Catholic University of America | Anhydrous |
| 420 | MOLYBDENUM (IV) SULFIDE, Chemical grade, < 5 microns avg, (Molybdenum Disulfide) | LOOKUP_NEEDED | $1,551 | 4 | SpaceX | — |
| 422 | Lead Acetate Solution with 7.2% as Pb | LOOKUP_NEEDED | $1,497 | 1 | B3 Systems, Inc. | — |
| 456 | BARIUM (II) NITRATE, ACS Reagent, crystal,  Ba(NO₃)₂ | LOOKUP_NEEDED | $1,142 | 3 | B3 Systems, Inc. / METSS Corporation | ACS Reagent / Reagent |
| 473 | 11297 | LOOKUP_NEEDED | $1,011 | 1 | B3 Systems, Inc. | — |
| 490 | 11258 | LOOKUP_NEEDED | $916 | 1 | B3 Systems, Inc. | — |
| 508 | ZINC CYANIDE, Tech grade, powder, Zn(CN)2 | LOOKUP_NEEDED | $846 | 1 | Armscor | — |
| 509 | POTASSIUM PERCHLORATE, ACS Reagent, crystal (Potassium chlorate (VII); Perchlori | LOOKUP_NEEDED | $840 | 1 | B3 Systems, Inc. | ACS Reagent / Reagent |
| 515 | METAL OXIDE BAGS, for Eastman Longview Set 1 | LOOKUP_NEEDED | $786 | 1 | Franklin Engineering Group Inc. | — |
| 516 | Sodium Dichromate Solution, 0.25 %  as Cr | LOOKUP_NEEDED | $778 | 1 | B3 Systems, Inc. | — |
| 522 | SODIUM DICHROMATE (VI), DIHYDRATE, 50% SOLUTION, 99% pure, 17.4% Cr,  Na₂Cr₂O₇.2 | LOOKUP_NEEDED | $748 | 1 | B3 Systems, Inc. | — |
| 526 | METAL OXIDE BAGS, for Eastman Longview Set 2 | LOOKUP_NEEDED | $719 | 1 | Franklin Engineering Group Inc. | — |
| 529 | MONOCHLOROBENZENE, (Chlorobenzene, Phenyl Chloride), C₆H₅Cl | LOOKUP_NEEDED | $694 | 1 | B3 Systems, Inc. | — |
| 532 | MERCURY ACETATE SOLUTION , Ethylene Glycol, 0.0005% as Hg | LOOKUP_NEEDED | $678 | 2 | B3 Systems, Inc. | — |
| 536 | SODIUM TETRABORATE, DECAHYDRATE, 99.5% pure, -70 mesh, (Borax), Na₂B₄O₇.10H₂O | LOOKUP_NEEDED | $651 | 2 | Catholic University of America | — |
| 549 | C3063 | LOOKUP_NEEDED | $584 | 1 | B3 Systems, Inc. | — |
| 559 | ALUMINUM OXIDE, 99% pure, -325 mesh, (Alumina), Al₂O₃ | LOOKUP_NEEDED | $546 | 1 | SpaceX | — |
| 560 | 11306 | LOOKUP_NEEDED | $542 | 1 | B3 Systems, Inc. | — |
| 565 | Sodium Dichromate Solution with 1.0% as Cr | LOOKUP_NEEDED | $516 | 1 | B3 Systems, Inc. | — |
| 567 | CADMIUM ACETATE, DIHYDRATE, 50% SOLUTION, 99.5% pure, 21.1% Cd,  Cd(OOCCH₃)₂.2H₂ | LOOKUP_NEEDED | $509 | 1 | B3 Systems, Inc. | — |
| 569 | LITHIUM CARBONATE, 99% pure, -200 mesh, Glass Former,  Li₂CO₃ | LOOKUP_NEEDED | $508 | 1 | Catholic University of America | — |
| 571 | TUNGSTEN METAL, POWDER, 99.95% pure, 1 micron average,  W | LOOKUP_NEEDED | $502 | 1 | SpaceX | — |
| 572 | Expedite Fee | LOOKUP_NEEDED | $500 | 2 | Catholic University of America | — |
| 574 | 11261 | LOOKUP_NEEDED | $489 | 1 | B3 Systems, Inc. | — |
| 575 | 11259 | LOOKUP_NEEDED | $489 | 1 | B3 Systems, Inc. | — |
| 578 | MERCURY ACETATE SOLUTION, Ethylene Glycol, 0.06% as Hg | LOOKUP_NEEDED | $481 | 2 | B3 Systems, Inc. | — |
| 587 | 11262 | LOOKUP_NEEDED | $428 | 1 | B3 Systems, Inc. | — |
| 591 | EUROPIUM OXIDE, 99.99% pure, -325 mesh,  Eu₂O₃ | LOOKUP_NEEDED | $405 | 1 | Catholic University of America | — |
| 593 | 11308 | LOOKUP_NEEDED | $402 | 1 | B3 Systems, Inc. | — |
| 598 | YTTRIUM CHLORIDE, HEXAHYDRATE, 99.9% pure, -10 mesh, (Yttrium Trichloride, Hexah | LOOKUP_NEEDED | $393 | 1 | SpaceX | — |
| 599 | IRON (III) HYDROXIDE, 99.5% pure, 13% slurry, stabilized, (Ferric Hydroxide), Fe | LOOKUP_NEEDED | $386 | 2 | Catholic University of America | — |
| 600 | LEAD (II) OXIDE, 99.999% pure, -200 mesh, (Lead Monoxide), PbO | LOOKUP_NEEDED | $383 | 2 | Biolase, Inc | — |
| 601 | SURROGATE WASTE FEED, Glass Formers, AN-105 DFHLW, for PNNL | LOOKUP_NEEDED | $380 | 2 | Battelle Pacific N. W. Labs | — |
| 603 | C3064 | LOOKUP_NEEDED | $366 | 1 | B3 Systems, Inc. | — |
| 608 | CALCIUM HYDROXIDE, 99% pure, ACS Reagent, -200 mesh, (Slaked Lime), Ca(OH)₂ | LOOKUP_NEEDED | $350 | 1 | Catholic University of America | ACS Reagent / Reagent |
| 618 | HAFNIUM (IV) OXIDE, 99% pure, -325 mesh, (HafniumDioxide; Hafnia), HfO₂ | LOOKUP_NEEDED | $284 | 1 | Catholic University of America | — |
| 620 | SURROGATE WASTE FEED, Glass Formers, AP-107 DFHLW, for PNNL | LOOKUP_NEEDED | $281 | 2 | Battelle Pacific N. W. Labs | — |
| 624 | SILICON, ELEMENTAL, POWDER, 99.5% pure, 95% <10 microns,  Si | LOOKUP_NEEDED | $258 | 1 | SpaceX | — |
| 636 | TITANIUM (IV) OXIDE, ANATASE & RUTILE, 99.5% pure, -325 mesh, (Titanium Dioxide) | LOOKUP_NEEDED | $237 | 2 | SpaceX / Cosmocel S.A. | — |
| 639 | 11289 | LOOKUP_NEEDED | $225 | 1 | Catholic University of America | — |
| 644 | Potassium Chloride/Mercury Acetate Solution10% Cl/ 0.011% Hg | LOOKUP_NEEDED | $200 | 1 | B3 Systems, Inc. | — |
| 652 | YTTRIUM OXIDE, 99.999% pure, < 6 microns average, Y₂O₃ | LOOKUP_NEEDED | $175 | 1 | SpaceX | — |
| 663 | SURROGATE WASTE FEED, Glass Formers, AN-106 DFHLW, for PNNL | LOOKUP_NEEDED | $151 | 1 | Battelle Pacific N. W. Labs | — |
| 676 | 11313 | LOOKUP_NEEDED | $111 | 1 | Catholic University of America | — |
| 679 | ALUMINUM OXIDE, 99.99% pure, 1-3 mm (Alumina) Al₂O₃ | LOOKUP_NEEDED | $108 | 1 | Battelle Pacific N. W. Labs | — |
| 683 | YTTRIUM OXIDE, 99.9% pure, < 6 microns average,  Y{2}O{3} | LOOKUP_NEEDED | $100 | 1 | SpaceX | — |
| 687 | IRON METAL, POWDER, ATOMIZED, ANNEALED, 99.5% pure, -325 mesh, Fe | LOOKUP_NEEDED | $99 | 1 | SpaceX | — |
| 695 | ZIRCONIUM SILICATE, 325 mesh, (as specified in WSRC-TR-2003-00220, Rev 0) | LOOKUP_NEEDED | $83 | 1 | Catholic University of America | — |
| 708 | CALCIUM CARBONATE, >90% pure, Reagent, powder CaCO₃ | LOOKUP_NEEDED | $44 | 1 | Catholic University of America | Reagent |
| 711 | SILICON (IV) OXIDE, 95% pure, -16/+20 mesh, SiO2 | LOOKUP_NEEDED | $40 | 1 | Catholic University of America | — |
| 723 | SILICON (IV) OXIDE, 99.9% pure, mean particle size 45 microns, (Silicon Dioxide, | LOOKUP_NEEDED | $19 | 2 | Catholic University of America / SpaceX | — |
| 735 | MAGNESIUM SILICATE, 325 mesh, (as specified in WSRC-TR-2003-00220, Rev 0) | LOOKUP_NEEDED | $-0 | 1 | Catholic University of America | — |
| 736 | SODIUM TETRABORATE, DECAHYDRATE, NF, -70 mesh, Special for Watson Foods, (Borax) | LOOKUP_NEEDED | $-0 | 1 | Catholic University of America | — |
| 740 | GIBBSITE, 3431, 8.0 micron, white, ATH, Al(OH)₃ or Al₂O₃.3H₂O | LOOKUP_NEEDED | $-4 | 2 | Oak Ridge National Laboratory | — |
| 745 | TITANIUM DIOXIDE, (as specified in WSRC-TR-2003-00220, Rev 0), TiO₂ | LOOKUP_NEEDED | $-22 | 1 | Catholic University of America | — |
| 756 | Drum, 55 gallon, plastic, open head, blue, 1H2 | LOOKUP_NEEDED | $-182 | 1 | Catholic University of America | — |
| 758 | Drum, 55 gallon, tight head, plastic, natural, UN1H1, Item 80215 | LOOKUP_NEEDED | $-227 | 1 | Franklin Engineering Group Inc. | — |
| 763 | Fiber drum, 10 gallon, Lok-Rim, ITEM #:DRFI05769NA20001 | LOOKUP_NEEDED | $-391 | 2 | Metal Improvement Co., LLC / Pyrotechnique by Grucci, Inc. | — |
| 779 | Drum, 30 gallon, plastic, open head, blue, UN 1H2/Y180/S, Item 80202 | LOOKUP_NEEDED | $-2,760 | 2 | Catholic University of America / SpaceX | — |
| 781 | Fiber drum, 30 gallon, Lok-Rim, Item DRFI03730NA20002 | LOOKUP_NEEDED | $-3,121 | 18 | Infiniumco / BASF Catalisadores Ltda. / BASF Catalysts South | — |

### Energy & Nuclear (9 chemicals, $353,255 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 5 | POTASSIUM CHLORIDE, USP, granular, KCI specifically for EOS Energy | LOOKUP_NEEDED | $262,798 | 12 | Eos Energy Enterprises Inc | USP |
| 25 | LANTHANUM CHLORIDE, HEPTAHYDRATE, 99.9% pure, -10mesh,  LaCl₃.7H₂O | 10025-84-0 | $79,365 | 13 | King Technology Inc. | — |
| 321 | C3069 | LOOKUP_NEEDED | $3,187 | 1 | Veolia Nuclear Solutions, Inc. | — |
| 329 | Barium Oxide, Technical, 90% pure, powder, BaO | LOOKUP_NEEDED | $3,075 | 1 | Ohmite Holding, LLC | — |
| 398 | C3070 | LOOKUP_NEEDED | $1,976 | 1 | Veolia Nuclear Solutions, Inc. | — |
| 416 | C3068 | LOOKUP_NEEDED | $1,588 | 1 | Veolia Nuclear Solutions, Inc. | — |
| 489 | NIOBIUM (V) OXIDE, 99.999% pure, typically 2 microns average, (Niobium Pentoxide | LOOKUP_NEEDED | $917 | 1 | Consolidated Nuclear Security | — |
| 622 | INDIUM (III) HYDROXIDE, 99.995% pure, -50 mesh,  In(OH)₃ | LOOKUP_NEEDED | $274 | 1 | AEsir Technologies | — |
| 699 | STRONTIUM FERRITE, 99.5% pure, 1.3 microns, (Strontium Iron Oxide), SrFe₁₂O₁₉ | LOOKUP_NEEDED | $75 | 1 | Tesla, Inc. | — |

### Advanced Manufacturing (98 chemicals, $3,180,815 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 1 | TITANIUM (IV) ISOPROPOXIDE, UOP/Honeywell Material No. 60560, (99% pure, liquid) | LOOKUP_NEEDED | $963,250 | 4 | Honeywell International Sdn. B | UOP Spec |
| 3 | LANTHANUM NITRATE, HEXAHYDRATE, Huntsman RMS No. R3022-C, (Huntsman Code 1930700 | LOOKUP_NEEDED | $365,862 | 15 | Huntsman Advanced Materials / Oqema AG / Huntsman Adv.Mat.(E | — |
| 12 | THALLIUM (I) SULFATE, 99.9% pure, -20 mesh, (Thallous Sulfate), Tl₂SO₄ | 7446-18-6 | $170,199 | 29 | Brenntag Mid-South, Inc. / K.C. Jones Plating Co. / Surface  | — |
| 14 | ILMENITE SAND, -40 mesh, FeTiO₃ | LOOKUP_NEEDED | $149,654 | 33 | Hickman, Williams & Company | — |
| 16 | ALUMINUM OXIDE, 99.5% pure, d₅₀ ≈ 90µm, recycled Special for Corning (Alumina),  | LOOKUP_NEEDED | $116,972 | 3 | Corning Incorporated | — |
| 18 | BARIUM ACETATE, 39% SOLUTION, BASF Spec No. G-PS-1449, Rev. 7, (Part Number 5000 | LOOKUP_NEEDED | $99,089 | 69 | BASF Mobile Emissions Catalyst / Heesung Catalysts Corporati | BASF Spec |
| 22 | MANGANESE (II) NITRATE, 50% SOLUTION, BASF Spec. No. GPS-0062, Rev. 8, BASF Arti | LOOKUP_NEEDED | $91,363 | 11 | BASF Catalysts (Shanghai) Co. Ltd. / BASF Mobile Emissions C | BASF Spec |
| 27 | TARIFF SURCHARGE | LOOKUP_NEEDED | $77,992 | 17 | BASF Mobile Emissions Catalyst | — |
| 28 | STRONTIUM ACETATE, 30% SOLUTION, BASF Spec. No. GPS-1591, Rev. 7, (Part Number 5 | LOOKUP_NEEDED | $73,217 | 32 | BASF Mobile Emissions Catalyst | BASF Spec |
| 33 | BARIUM SULFATE, Technical grade, BASF Spec. GPS-0585, Rev. 8, (Part Number 50006 | LOOKUP_NEEDED | $61,941 | 81 | BASF Mobile Emissions Catalyst / BASF Catalisadores Ltda. /  | BASF Spec / Technical Grade |
| 34 | BARIUM SULFATE, USP, -325 mesh, Sunlite Plastics Drawing No. 03-0003, Rev. J, Ba | 7727-43-7 | $59,515 | 11 | Sunlite Plastics | USP |
| 43 | BARIUM HYDROXIDE, OCTAHYDRATE, ACS Reagent, crystal,  Ba(OH)₂.8H₂O | LOOKUP_NEEDED | $51,926 | 13 | Carestream Health, Inc. / SCP Science | ACS Reagent / Reagent |
| 46 | SODIUM SULFIDE, NONAHYDRATE, ACS Reagent, crystal, Na₂S.9H₂O | LOOKUP_NEEDED | $48,494 | 13 | Strem Chemicals, Inc. / Aldrich Chemical Co. LLC / Productos | ACS Reagent / Reagent |
| 47 | AMMONIUM BICARBONATE, 99.2% pure min., powder, treated with anticaking agent | LOOKUP_NEEDED | $48,311 | 6 | American Chemet Corporation | — |
| 48 | MANGANESE (II) OXIDE, 99.5% pure, -40 mesh, (Manganese Monoxide; Manganous Oxide | 1344-43-0 | $48,087 | 19 | Nexceris, LLC / BeanTown Chemical Corp | — |
| 53 | IRON (II) CHLORIDE, TETRAHYDRATE, Ciba No. 91-997-640, RAC No. 825, BASF Article | LOOKUP_NEEDED | $42,827 | 7 | BASF Corporation | — |
| 57 | STRONTIUM CHLORIDE, HEXAHYDRATE, 99.5% pure, -10 mesh, SrCl₂.6H₂O | LOOKUP_NEEDED | $39,025 | 12 | BASF Corporation / California Academy of Sciences / Thermo F | — |
| 63 | CADMIUM OXIDE SLURRY, 50% w/w in water, special for Boeing Boeing Part Number F0 | LOOKUP_NEEDED | $35,883 | 14 | Cascade Columbia Distribution | — |
| 65 | COBALT (II) CHLORIDE, HEXAHYDRATE, ACS Reagent, crystal,  (Cobaltous Chloride, H | LOOKUP_NEEDED | $35,338 | 12 | Calumet Refining, LLC / Nutrisol LLC / Thermo Fisher Scienti | ACS Reagent / Reagent |
| 66 | PHOSPHOTUNGSTIC ACID, HYDRATE, Reagent, crystal, (Tungstophosphoric Acid, Hydrat | 12067-99-1 | $34,278 | 3 | Dixie Chemical Company | Reagent |
| 67 | BARIUM HYDROXIDE, OCTAHYDRATE, 96% pure, -40 mesh,  Ba(OH)₂.8H₂O | LOOKUP_NEEDED | $34,089 | 6 | Corechem, Inc. / STRUK  Auto Trsansporte / Blue Grass Chemic | — |
| 68 | TITANIUM (IV) OXIDE, ANATASE, 99.9% pure, < 5 microns average, Praxair PS 064006 | LOOKUP_NEEDED | $33,429 | 3 | Linde Advanced Material | — |
| 69 | STRONTIUM NITRATE, 99% pure, -35 mesh,  Sr(NO₃)₂ | LOOKUP_NEEDED | $33,323 | 19 | Mecano Tech, Inc. / CA Botana International, Inc. / METSS Co | — |
| 72 | MANGANESE (IV) OXIDE, 99.9% pure, -325 mesh , < 3 microns average (by Microtrac) | LOOKUP_NEEDED | $32,398 | 17 | Riverside Chemical Company / Aldrich Chemical Co. LLC / NEI  | — |
| 82 | SULFUR, POWDER, MIL-S-487B dated 29 JUN 1967, Amendment 2 dated 19 JUN 1986, Not | LOOKUP_NEEDED | $26,626 | 3 | Defense Finance and Accounting Service / Lyten, Inc | — |
| 84 | CALCIUM NITRATE, TETRAHYDRATE, 99.5% pure, -10 mesh,  Ca(NO₃)₂.4H₂O | 13477-34-4 | $25,042 | 1 | Nanogence SA | — |
| 85 | SODIUM BOROHYDRIDE, 98% pure, powder, (Sodium Tetrahydridoborate), NaBH₄ | 16940-66-2 | $24,766 | 10 | Pennakem / Minasolve LLC / Proton Energy Systems, Inc. | — |
| 87 | MAGNESIUM ACETATE, TETRAHYDRATE, 50% SOLUTION,  Developmental for BASF, (BASF Ar | LOOKUP_NEEDED | $24,401 | 20 | BASF Corporation (Cincinnati) | — |
| 89 | MANGANESE (II) OXIDE, 99.5% pure, -325 mesh, (Manganese Monoxide; Manganous Oxid | 1344-43-0 | $23,217 | 10 | Ortoquimicos S.A. de C.V. / Nexceris, LLC | — |
| 90 | SELENIUM (IV) SULFIDE, 99% pure, -60 mesh, (Selenium Disulfide), SeS₂ | LOOKUP_NEEDED | $22,394 | 4 | Neutraderm, Inc. / Thermo Fisher Scientific | — |
| 94 | STRONTIUM NITRATE, 99% pure, -35 mesh, (Special for Linde), Sr(NO₃)₂ | LOOKUP_NEEDED | $21,076 | 1 | Linde Advanced Material | — |
| 97 | BORON, ELEMENTAL, AMORPHOUS, 95-97% pure, <1 micron average,  B | LOOKUP_NEEDED | $20,557 | 11 | Technical Ordnance, Inc. / Stevens Tech., Inc. / Linde Advan | — |
| 100 | AMMONIUM OXALATE, MONOHYDRATE, ACS Reagent, crystal (Ethanedioic Acid Diammonium | LOOKUP_NEEDED | $19,497 | 3 | MacDermid de Mexico S.A.de C.V | ACS Reagent / Reagent |
| 101 | THALLIUM (I) SULFATE, POWDER, 99.5% pure, crystalline, (Thallous Sulfate), Tl₂SO | LOOKUP_NEEDED | $19,425 | 2 | Strem Chemicals, Inc. | — |
| 107 | STRONTIUM ACETATE, HEMIHYDRATE, BASF Specification No. GPS-1506, Rev. 5; (Part N | LOOKUP_NEEDED | $18,781 | 19 | BASF Mobile Emissions Catalyst / BASF Catalysts South | BASF Spec |
| 108 | SILICON CARBIDE, BETA, 99.995% pure, -325 mesh,  SiC | LOOKUP_NEEDED | $18,737 | 5 | Linde Advanced Material / Entegris, Inc. | — |
| 111 | IRON (III) OXIDE, ANHYDROUS, 99.9% pure, -325 mesh, < 3 microns average, (Ferric | LOOKUP_NEEDED | $18,015 | 19 | The Dow Chemical Company / CTS Corporation / MSC Industrial  | Anhydrous |
| 135 | OXAMIDE, MIL-O-60863A, TYPE II, (CONH₂)₂ | LOOKUP_NEEDED | $13,763 | 5 | Mecano Tech, Inc. | — |
| 140 | ALUMINUM NITRATE, NONAHYDRATE, BASF Spec GPS-1754, Rev. 3, BASF Part No. 500058- | LOOKUP_NEEDED | $12,786 | 16 | BASF Mobile Emissions Catalyst / BASF Chemcat (Thailand) Ltd | ACS Reagent / BASF Spec / Reagent |
| 144 | LITHIUM CHLORIDE, 40% Solution, (Special for Emerson Climate Technologies, Inc), | LOOKUP_NEEDED | $12,142 | 1 | Emerson Climate Technologies | — |
| 158 | COPPER (II) SULFIDE, 3M RM No. 11-0018-3199-6, (Cupric Sulfide), CuS | LOOKUP_NEEDED | $11,191 | 2 | 3M Corporation / Echo Therm | — |
| 166 | CALCIUM NITRATE, TETRAHYDRATE, ACS Reagent, crystal,  Ca(NO₃)₂.4H₂O | LOOKUP_NEEDED | $10,480 | 3 | Nanogence SA / CR Bard Inc / PT. Aik Moh Chemical Indonesia | ACS Reagent / Reagent |
| 178 | POTASSIUM FERRICYANIDE, ACS Reagent, crystalline powder, -30 mesh, special for S | LOOKUP_NEEDED | $9,228 | 4 | Strem Chemicals, Inc. | ACS Reagent / Reagent |
| 202 | THALLIUM (I) NITRATE, 99.99% pure, -40 mesh, (Thallous Nitrate), TlNO₃ | LOOKUP_NEEDED | $7,836 | 5 | Strem Chemicals, Inc. / Spex CertiPrep | — |
| 225 | IRON (III) OXIDE, ANHYDROUS, BASF Specification No. GPS-1709, Rev, 2., (Part Num | LOOKUP_NEEDED | $6,456 | 4 | BASF Catalysts South / BASF Mobile Emissions Catalyst / BASF | Anhydrous / BASF Spec |
| 246 | CALCIUM CHROMATE, Technical grade, 99.5% pure, -325 mesh, meeting Tech Ord speci | LOOKUP_NEEDED | $5,424 | 4 | Technical Ordnance, Inc. | Technical Grade |
| 251 | CHROMIUM (III) SULFATE, HYDRATE, Reagent, crystalline, (Chromic Sulfate, Hydrate | LOOKUP_NEEDED | $5,221 | 6 | Verdesian Life Sciences, LLC / Fujifilm Irvine Scientific In | Reagent |
| 264 | ALUMINUM (III) ACETYLACETONATE, 99.9% pure, -25 +100 mesh, very low dust, (Alumi | LOOKUP_NEEDED | $4,868 | 3 | Toyo Ink America, LLC | — |
| 280 | BARIUM CARBONATE, 99.9% pure, ACS Reagent, -200 mesh,  BaCO₃ | LOOKUP_NEEDED | $4,333 | 6 | Yee Young Cerachem, Ltd. / PIDC / METSS Corporation | ACS Reagent / Reagent |
| 283 | SODIUM LAURYL SULFATE, USP/NF, powder, (Dodecyl Sodium Sulfate), CH₃(CH₂)₁₁OSO₃N | 151-21-3 | $4,152 | 1 | American Chemet Corporation | USP |
| 292 | SODIUM SULFATE, ANHYDROUS, 99.8% pure, -60 mesh,Na₂SO₄ | 7757-82-6 | $3,843 | 5 | Pyrotek High Temperature | Anhydrous |
| 297 | BARIUM HYDROXIDE, OCTAHYDRATE, BASF Specification  GPS-0548, Rev. 7, (Part Numbe | LOOKUP_NEEDED | $3,673 | 44 | BASF Mobile Emissions Catalyst / BASF Catalisadores Ltda. | BASF Spec |
| 313 | 90625 | LOOKUP_NEEDED | $3,243 | 1 | The Dow Chemical Company | — |
| 318 | C3061 | LOOKUP_NEEDED | $3,207 | 1 | Technical Ordnance, Inc. | — |
| 367 | TIN (II) CHLORIDE, DIHYDRATE, 99.5% pure, ACS Reagent, -4 mesh, (Stannous Chlori | LOOKUP_NEEDED | $2,415 | 4 | Corry Micronics / 0014253 / Glanbia Nutritionals (NA), Inc | ACS Reagent / Reagent |
| 374 | SILICON (IV) OXIDE, 99.8% pure, 1 micron average,(Silicon Dioxide, Silica), SiO₂ | LOOKUP_NEEDED | $2,327 | 10 | Cascade Columbia Distribution / SpaceX / Tetra Technologies | — |
| 381 | MANGANESE (II) CHLORIDE, ANHYDROUS, 97% pure, flakes, (Manganese Dichloride, Anh | LOOKUP_NEEDED | $2,161 | 1 | Strem Chemicals, Inc. | Anhydrous |
| 386 | ZINC NITRATE, HEXAHYDRATE, 99.5% pure, crystal,  Zn(NO₃)₂.6H₂O | LOOKUP_NEEDED | $2,125 | 3 | BASF Mobile Emissions Catalyst | — |
| 387 | CALCIUM NITRATE, TRIHYDRATE, 99.5% pure, crystal,  Ca(NO₃)₂.3H₂O | LOOKUP_NEEDED | $2,102 | 3 | Nanogence SA / Bowers Distillery, Inc. | — |
| 394 | VANADIUM (V) OXIDE, 99.9% pure, -60 mesh, (Vanadium Pentoxide, Vanadic Anhydride | LOOKUP_NEEDED | $2,037 | 1 | Strem Chemicals, Inc. | — |
| 396 | ZINC ACETATE, DIHYDRATE, 99% pure, -20 mesh,  Zn(OOCCH₃)₂.2H₂O | LOOKUP_NEEDED | $2,011 | 4 | BASF Mobile Emissions Catalyst | — |
| 431 | IRON METAL, POWDER, ELECTROLYTIC, 99.9% pure, -325 mesh,  Fe | LOOKUP_NEEDED | $1,419 | 4 | Materion Advanced Materials | — |
| 437 | TIN METAL, POWDER, 99.9% pure, -100 mesh,  Sn | LOOKUP_NEEDED | $1,369 | 2 | Kinon surface Design / 0014289 | — |
| 439 | COPPER (II) OXIDE, 99+% pure, -325 mesh, black, (Cupric Oxide), CuO | LOOKUP_NEEDED | $1,333 | 7 | Nepa Chemical & Logistics / Yee Young Cerachem, Ltd. / Checo | — |
| 442 | SUCROSE, ACS Reagent, crystal, C₁₂H₂₂O₁₁ | LOOKUP_NEEDED | $1,318 | 2 | ExPost Technology | ACS Reagent / Reagent |
| 454 | SODIUM SULFATE, ANHYDROUS, ACS Reagent, -10/+30 mesh, Na₂SO₄ | LOOKUP_NEEDED | $1,153 | 2 | Pyrotek High Temperature / 0014237 | ACS Reagent / Anhydrous / Reagent |
| 458 | MOLYBDENUM (V) CHLORIDE, 99.6% pure, -8 mesh, (Molybdenum Pentachloride), MoCl₅ | LOOKUP_NEEDED | $1,126 | 1 | Strem Chemicals, Inc. | — |
| 461 | CITRIC ACID, MONOHYDRATE, ACS Reagent, -40 mesh, (2-Hydroxy-1,2,3-propanetricarb | LOOKUP_NEEDED | $1,100 | 3 | ExPost Technology / LEGOR Extraordinary Matter | ACS Reagent / Reagent |
| 465 | TIN (II) OXIDE, 99.9% pure, -100 mesh, (Stannous Oxide), SnO | LOOKUP_NEEDED | $1,079 | 2 | Yee Young Cerachem, Ltd. / E.I. Dupont  de Nemours & | — |
| 475 | DEXTROSE, Agglomerated, Chemically Pure, -30 mesh (special for Osage)  C₆H₁₂O₆ | LOOKUP_NEEDED | $1,000 | 1 | Osage Food Products Inc. | — |
| 476 | ZINC CARBONATE, Reagent grade, -200 mesh, (Zinc Monocarbate), [ZnCO₃]2 . [Zn(OH) | LOOKUP_NEEDED | $987 | 1 | BASF Corporation | Reagent |
| 483 | BARIUM (II) NITRATE, BASF Specification No. GPS-0044, Rev. 10, (Part Number 5000 | LOOKUP_NEEDED | $964 | 1 | BASF Catalysts LLC (Seneca) | BASF Spec |
| 487 | BARIUM ACETATE, BASF Specification No. GPS-0586, Rev. 12, (Part No. 500062-102,  | LOOKUP_NEEDED | $923 | 1 | BASF Mobile Emissions Catalyst | BASF Spec |
| 519 | MOLYBDENUM (VI) OXIDE, 99% pure, -325 mesh, (Molybdenum Trioxide, Molybdic Acid  | LOOKUP_NEEDED | $766 | 1 | CeramTec | — |
| 538 | NICKEL (II) OXIDE, 99% pure, -325 mesh, green, (Nickelous Oxide), NiO | LOOKUP_NEEDED | $645 | 3 | Strem Chemicals, Inc. | — |
| 553 | ZINC OXIDE, 99.9% pure, ACS Reagent, -200 mesh, ZnO | LOOKUP_NEEDED | $573 | 1 | BASF Mobile Emissions Catalyst | ACS Reagent / Reagent |
| 555 | ZINC METAL, SHOT, 99.99% pure, 6-10 mm dia. x 1-2mm thick, flattened,  Zn | LOOKUP_NEEDED | $562 | 2 | Honeywell / Honeywell Electronic Materials | — |
| 556 | NICKEL METAL, POWDER, 99.9% pure, < 5 microns average, spherical, Ni | LOOKUP_NEEDED | $550 | 2 | Nexceris, LLC | — |
| 561 | DEIONIZED WATER, Type I, Cl < 0.5 ppm, H₂O | LOOKUP_NEEDED | $542 | 2 | Corechem, Inc. | — |
| 570 | SILICON CARBIDE, ALPHA, 99.5% pure, 25-85 microns, green,  SiC | LOOKUP_NEEDED | $505 | 1 | Entegris, Inc. | — |
| 579 | CALCIUM SILICATE, -325 mesh, (Wollastonite), CaSiO₃ | LOOKUP_NEEDED | $468 | 2 | Entegris, Inc. / BioAg | — |
| 602 | SODIUM METHYLATE, 98% pure, powder CH₃NaO | LOOKUP_NEEDED | $370 | 1 | Pennakem | — |
| 638 | MAGNESIUM SULFATE, HEPTAHYDRATE, ACS Reagent, crystal, MgSO₄.7H₂O | LOOKUP_NEEDED | $229 | 2 | Google Asia Pacific Pte Ltd / Verily Life Sciences | ACS Reagent / Reagent |
| 642 | AMMONIUM ACETATE, ACS Reagent, crystal,  NH₄OOCCH₃ | LOOKUP_NEEDED | $212 | 2 | GE Chaplin / HACH Company | ACS Reagent / Reagent |
| 664 | STRONTIUM NITRATE, 99% pure, +35 mesh,  Sr(NO₃)₂ | LOOKUP_NEEDED | $150 | 1 | Mecano Tech, Inc. | — |
| 674 | TIN (IV) OXIDE, 99.9% pure, -325 mesh, < 1 micron average, (Stannic Oxide), SnO₂ | LOOKUP_NEEDED | $118 | 3 | E.I. Dupont  de Nemours & / Catalytic Combustion Corp | — |
| 698 | SODIUM ALUMINATE, 99% pure, granular, (Sodium Aluminum Oxide), Na₂Al₂O₄ | LOOKUP_NEEDED | $76 | 1 | Pyrotek High Temperature | — |
| 721 | UREA, USP, crystal H{2}NCONH{2} | LOOKUP_NEEDED | $22 | 2 | Cascade Columbia Distribution | USP |
| 725 | TUNGSTEN (VI) OXIDE, 99.99% pure, 1-4 mm pieces, sintered, (Tungsten Trioxide; T | LOOKUP_NEEDED | $12 | 1 | Strem Chemicals, Inc. | — |
| 730 | IRON (II) CHLORIDE, TETRAHYDRATE, 40% SOLUTION (Ferrous Chloride Solution), FeCl | LOOKUP_NEEDED | $0 | 1 | BASF SE (Germany) | — |
| 731 | CHEMALLOY MANOX POWDER, MnO | LOOKUP_NEEDED | $0 | 1 | The Dow Chemical Company | — |
| 732 | CHEMALLOY ILMENITE POWDER (30 X 200 MESH),  TiO2 | LOOKUP_NEEDED | $0 | 1 | The Dow Chemical Company | — |
| 733 | CHEMALLOY ILMENITE POWDER (-325 MESH) , TiO2 | LOOKUP_NEEDED | $0 | 1 | The Dow Chemical Company | — |
| 743 | Manganese (II) Acetate, Tetrahydrate, 37% solution, 8.25% Mn, (Developmental for | LOOKUP_NEEDED | $-12 | 1 | BASF Mobile Emissions Catalyst | — |
| 748 | COPPER (I) CHLORIDE, 99% pure, -40 mesh, (CuprousChloride), CuCl | LOOKUP_NEEDED | $-29 | 1 | Corning Incorporated | — |
| 755 | Pail, 3.5 gallon, Life Latch New Gen Screw Top Containers | LOOKUP_NEEDED | $-109 | 16 | Brenntag Mid-South, Inc. / Glanbia Nutritionals (NA), Inc /  | — |
| 772 | XANTHAN GUM, FCC, 80 mesh, C₃₅H₄₉O₂₉ | LOOKUP_NEEDED | $-1,016 | 1 | Cascade Columbia Distribution | FCC |
| 782 | Fiber drum, 8 gal, Lok-Rim, Item DRFI03741NA20001 | LOOKUP_NEEDED | $-3,615 | 8 | Franklin Engineering Group Inc. / Ortoquimicos S.A. de C.V.  | — |

### Life Sciences & Pharma (148 chemicals, $2,485,895 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 6 | SODIUM SULFITE, Special for Hope Pharmaceuticals (28 Mar 2024), Na₂SO₃ | LOOKUP_NEEDED | $259,374 | 18 | Hope Pharmaceuticals | — |
| 8 | VANADIUM OXYSULFATE, HYDRATE, USP, crystal, (Vanadyl Sulfate, Hydrate), VOSO₄.xH | LOOKUP_NEEDED | $234,312 | 51 | Nutrisol LLC / Biotron Laboratories, Inc. / Capital Resin Co | USP |
| 9 | SODIUM CYANIDE, ACS Reagent, granular,  NaCN | LOOKUP_NEEDED | $204,319 | 80 | Aldrich Chemical Co. LLC / Avantor Performance Materials / H | ACS Reagent / Reagent |
| 17 | ZIRCONIUM (IV) CHLORIDE, 99.95% pure, -40 mesh, (Zirconium Tetrachloride), ZrCl{ | LOOKUP_NEEDED | $116,689 | 2 | Gujarat Fluorochemicals Limite | — |
| 20 | SULFUR SUBLIMED, USP powder, ROI < 0.2% for Hope Pharmaceuticals, S | LOOKUP_NEEDED | $98,245 | 14 | Hope Pharmaceuticals | USP |
| 23 | IRON (III) ORTHOPHOSPHATE, HYDRATE, FCC, -325 mesh, (Ferric Orthophosphate, Hydr | LOOKUP_NEEDED | $90,259 | 24 | Homestat Farm, Ltd. / Thermo Fisher Scientific / The Foster  | FCC |
| 24 | LITHIUM CARBONATE, (Special for Nutrisol), -40 mesh, Li₂CO₃ | LOOKUP_NEEDED | $86,135 | 14 | Nutrisol LLC | ACS Reagent |
| 30 | THALLIUM-MERCURY AMALGAM, 8.5% Tl, (Thallium Amalgam), Hg:Tl | LOOKUP_NEEDED | $65,915 | 22 | Lawrence Livermore National Laboratory / Consolidated Nuclea | — |
| 32 | SODIUM SELENITE, ANHYDROUS, 99.5% pure, -20 mesh, Na₂SeO₃ | LOOKUP_NEEDED | $62,578 | 26 | Nutrisol LLC / Biotron Laboratories, Inc. / Core Agri, Inc. | Anhydrous |
| 36 | VANADIUM OXYSULFATE, HYDRATE, USP, crystal, special for Balchem, (Vanadyl Sulfat | 27774-13-6 | $57,339 | 5 | Balchem | USP |
| 37 | SODIUM HYDROXIDE, 50% SOLUTION, Reagent, (Caustic Soda), NaOH | LOOKUP_NEEDED | $56,576 | 35 | HACH Company / Alchemy Geopolymer Solutions / Southwest Rese | Reagent |
| 38 | LITHIUM HYDROXIDE, MONOHYDRATE, Ortho Clinical Diagnostic Specification #SPC3307 | LOOKUP_NEEDED | $56,553 | 5 | Ortho Clinical Diagnostics | — |
| 39 | SODIUM THIOSULFATE, ANHYDROUS, Reagent, granular, Na₂S₂O₃ | LOOKUP_NEEDED | $55,519 | 23 | Glanbia Nutritionals (NA), Inc / WET International, Inc / HA | Anhydrous / Reagent |
| 40 | MAGNESIUM METAL, POWDER, 99.8% pure, -325 mesh, Mg | LOOKUP_NEEDED | $55,345 | 11 | SISEL International / SupraNaturals LLC / Ohmite Holding, LL | — |
| 44 | Hutners Trace Elements Solution | LOOKUP_NEEDED | $50,434 | 32 | Verily Life Sciences / Google | — |
| 45 | VANADIUM OXYSULFATE, HYDRATE, 99.9% pure, crystal for ThermoFisher Scientifc, Pa | LOOKUP_NEEDED | $49,834 | 6 | Thermo Fisher Scientific / Thermo Fisher (Kandel) GmbH | — |
| 49 | VANADIUM OXYSULFATE, HYDRATE, 99.5% pure, crystal, (Vanadyl Sulfate, Hydrate), V | LOOKUP_NEEDED | $47,514 | 18 | Thermo Fisher Scientific / Nutrisol LLC / MFG Chemical, LLC | — |
| 52 | POTASSIUM PHOSPHATE DIBASIC, ACS Reagent, powder,(Dipotassium Hydrogen Phosphate | LOOKUP_NEEDED | $42,857 | 53 | World Bioproducts LLC / Verily Life Sciences / Google | ACS Reagent / Reagent |
| 56 | SODIUM SELENATE, ANHYDROUS, (according to Watson Specification No. R140247, Vers | LOOKUP_NEEDED | $39,142 | 3 | Glanbia Nutritionals (NA), Inc | Anhydrous |
| 59 | LITHIUM HYDROXIDE, MONOHYDRATE, 98% pure, ACS Reagent, powder,  LiOH.H₂O | LOOKUP_NEEDED | $38,498 | 5 | Thermo Fisher Scientific / AEsir Technologies | ACS Reagent / Reagent |
| 70 | CHROMIUM (III) CHLORIDE, HEXAHYDRATE, USP, crystal, (Chromic Chloride, Hexahydra | LOOKUP_NEEDED | $32,803 | 26 | Contract Pharmacal Corporation / IXOM / Entegris, Inc. | USP |
| 79 | TIN (II) FLUORIDE,  USP, -6 mesh, (Stannous Fluoride), SnF₂ | LOOKUP_NEEDED | $27,878 | 9 | Thermo Fisher (Kandel) GmbH / LSNE Contract Manufacturing /  | USP |
| 80 | THALLIUM METAL, 99.99% pure (in water), granular, Tl | LOOKUP_NEEDED | $27,174 | 14 | Lawrence Livermore National Laboratory / Thermo Fisher Scien | — |
| 86 | SODIUM MOLYBDATE, DIHYDRATE, FCC, crystal, (Molybdic Acid, Sodium Salt, Sodium M | 10102-40-6 | $24,647 | 21 | Glanbia Nutritionals (NA), Inc / Nutrisol LLC / Canton Chem, | FCC |
| 88 | THALLIUM (I) ACETATE, 99% pure, crystalline powder, (Thallous Acetate),  TlOOCCH | LOOKUP_NEEDED | $23,381 | 10 | Acros Organics B.V. / DC Fine Chemicals | — |
| 91 | SODIUM TARTRATE, DIHYDRATE, ACS Reagent, -20 mesh, (Tartaric Acid-L, Sodium Salt | LOOKUP_NEEDED | $22,389 | 17 | HACH Company | ACS Reagent / Reagent |
| 95 | SODIUM METAVANADATE, 99.5% pure, -100 mesh, (Sodium Vanadium Oxide), NaVO₃ | LOOKUP_NEEDED | $20,754 | 6 | Nutrisol LLC / MP Biomedicals LLC / Nutrabiotics S.A.S | — |
| 98 | POTASSIUM PHOSPHATE MONOBASIC, ACS Reagent, powder, (Potassium Dihydrogen Phosph | LOOKUP_NEEDED | $20,510 | 43 | Verily Life Sciences / World Bioproducts LLC / Google | ACS Reagent / Reagent |
| 102 | AMMONIUM CHLORIDE, ACS Reagent, crystal, NH₄Cl | LOOKUP_NEEDED | $19,359 | 15 | Verily Life Sciences / Google / Hitemco | ACS Reagent / Reagent |
| 104 | MAGNESIUM BROMIDE, HEXAHYDRATE, 98% pure, crystalline, MgBr2.6H2O | LOOKUP_NEEDED | $19,098 | 11 | Pall Corporation / Thermo Fisher Scientific | — |
| 113 | HYDROXYLAMINE SOLUTION, 50% in water, H₃NO | 7803-49-8 | $17,700 | 2 | Cambrex Charles City, Inc. | — |
| 117 | TITANIUM (IV) OXIDE, ANATASE, 99.9% pure, <5 microns average, (Titanium Dioxide) | LOOKUP_NEEDED | $16,849 | 23 | CTS Corporation / The Dow Chemical Company / Hickman, Willia | — |
| 123 | ZIRCONIUM OXYNITRATE, HYDRATE, 99% pure, -4 mesh (Sigma- Aldrich Part No. 243493 | LOOKUP_NEEDED | $15,576 | 3 | Aldrich Chemical Co. LLC / Catholic University of America | — |
| 127 | TITANIUM (IV) OXYSULFATE, DIHYDRATE, 99% pure, -10 mesh, (Titanyl Sulfate, Dihyd | LOOKUP_NEEDED | $15,060 | 10 | Thermo Fisher Scientific / All Metals Processing / Shepherd  | — |
| 130 | MANGANESE (II) CARBONATE, 99.9% pure, -200 mesh, Sigma Aldrich Part No. 377449,  | LOOKUP_NEEDED | $14,078 | 6 | Aldrich Chemical Co. LLC | — |
| 132 | SELENOUS ACID, 99% pure, -4 mesh, H₂SeO₃ | LOOKUP_NEEDED | $13,852 | 9 | Biotron Laboratories, Inc. / Custom Etch Inc. / Thermo Fishe | — |
| 134 | THALLIUM (I) FORMATE, 99.9% pure, -40 mesh, (Thallous Formate), TlOOCH | LOOKUP_NEEDED | $13,783 | 6 | Aldrich Chemical Co. LLC | — |
| 136 | SELENIUM METAL, POWDER, 99.999% pure, -200 mesh, Se | LOOKUP_NEEDED | $13,609 | 4 | Thermo Fisher Scientific | — |
| 149 | LITHIUM HYDRIDE, 99.9% pure, -10 mesh,  LiH | LOOKUP_NEEDED | $11,898 | 10 | Thermo Fisher Scientific / Government Scientific | — |
| 155 | BARIUM METAL, PIECES, 99% pure, ~ 1/4" pieces, Sigma Aldrich Part Number X47595, | LOOKUP_NEEDED | $11,422 | 1 | Aldrich Chemical Co. LLC | — |
| 161 | ZINC SULFIDE, 99.99% pure, cubic, -325 mesh, <5 microns average,  ZnS | LOOKUP_NEEDED | $10,844 | 4 | Aldrich Chemical Co. LLC | — |
| 168 | POTASSIUM HYDROXIDE, ACS Reagent, pellets,  KOH | LOOKUP_NEEDED | $10,379 | 7 | Aldrich Chemical Co. LLC / Vallen Canada / SWIC Scientific & | ACS Reagent / Reagent |
| 169 | GALLIUM (III) BROMIDE, 99.999% pure, -50 mesh, (Gallium Tribromide), GaBr₃ | LOOKUP_NEEDED | $10,319 | 4 | Aldrich Chemical Co. LLC | — |
| 173 | GLYCINE, USP, crystalline powder, (Aminoacetic acid, H-Gly-OH), C₂H₅NO₂ | LOOKUP_NEEDED | $9,824 | 7 | Biotron Laboratories, Inc. / Nutrisol LLC / Cascade Columbia | USP |
| 181 | AMMONIUM FLUORIDE, ACS Reagent, crystal, NH₄F | LOOKUP_NEEDED | $9,197 | 3 | Spectrum Chemical Mfg. Corp | ACS Reagent / Reagent |
| 183 | BORON OXIDE, 99.98% pure, Sigma-Aldrich Part No. 339075-BULK, (Boron Trioxide, B | LOOKUP_NEEDED | $9,119 | 6 | Aldrich Chemical Co. LLC | — |
| 185 | CHROMIUM (III) CHLORIDE, HEXAHYDRATE, FCC, crystal, (Chromic Chloride, Hexahydra | LOOKUP_NEEDED | $9,062 | 7 | Glanbia Nutritionals (NA), Inc / CTS Corporation | FCC |
| 189 | IRON (III) HYDROXIDE OXIDE, 99.5% pure, -325 mesh, (Ferric Hydroxide), FeO(OH) | 20344-49-4 | $8,769 | 11 | Thermo Fisher Scientific / Veolia Nuclear Solutions, Inc. /  | — |
| 190 | SILICON, ELEMENTAL, POWDER, 99% pure, -325 mesh, Si | LOOKUP_NEEDED | $8,663 | 2 | Aldrich Chemical Co. LLC / SpaceX | — |
| 191 | SILICOTUNGSTIC ACID, HYDRATE, Reagent, crystal, (Tungstosilicic Acid, Hydrate),  | LOOKUP_NEEDED | $8,498 | 4 | Thermo Fisher Scientific | Reagent |
| 192 | SODIUM PHOSPHATE DIBASIC, ANHYDROUS, ACS Reagent, powder, (Disodium Phosphate; D | 7558-79-4 | $8,489 | 17 | World Bioproducts LLC / Crystal Claire Cosmetics Inc. / Appl | ACS Reagent / Anhydrous / Reagent |
| 195 | THALLIUM (III) OXIDE, 99.5% pure, -20 mesh, (Thallic Oxide, Thallium Sesquioxide | LOOKUP_NEEDED | $8,427 | 1 | Thermo Fisher Scientific | — |
| 197 | AMMONIUM TUNGSTATE, META, HYDRATE, 99.9% pure, -100 mesh, (Ammonium Tungsten Oxi | LOOKUP_NEEDED | $8,235 | 2 | Thermo Fisher (Kandel) GmbH | — |
| 204 | SODIUM ORTHOVANADATE, Acros Product 20533-0000,  Version 4, Na₃VO₄ | LOOKUP_NEEDED | $7,771 | 5 | Acros Organics B.V. | — |
| 213 | SODIUM CHLORIDE, 99.9% pure, -60 mesh, NaCl | LOOKUP_NEEDED | $7,199 | 32 | World Bioproducts LLC / Shearwater Research Inc. / Aptar CSP | — |
| 215 | 1,2-DICHLOROBENZENE for Thermo Fisher Spectrophotometry | LOOKUP_NEEDED | $7,055 | 1 | Thermo Fisher Scientific | — |
| 216 | CALCIUM BORIDE, 99% pure, -20 mesh, (Calcium Hexaboride), CaB₆ | LOOKUP_NEEDED | $6,979 | 3 | Thermo Fisher Scientific / Atlantic Metals & Alloys, Inc. | — |
| 218 | MANGANESE (II) CARBONATE, 99.95% pure, -200 mesh, MnCO₃ | LOOKUP_NEEDED | $6,919 | 4 | Thermo Fisher Scientific / NEI Corporation | — |
| 220 | CALCIUM BROMIDE, HYDRATE, 99% pure, -50 mesh,  CaBr₂.xH₂O | LOOKUP_NEEDED | $6,800 | 1 | Thermo Fisher Scientific | — |
| 221 | STRONTIUM CARBONATE, 99.5% pure, -325 mesh, typically 1 micron, SrCO₃ | LOOKUP_NEEDED | $6,633 | 15 | Thermo Fisher Scientific / NC State University / Redoxblox | — |
| 222 | NIOBIUM (V) ETHOXIDE, 99.999% pure, liquid, Nb(C₂H₅O)₅ | LOOKUP_NEEDED | $6,620 | 5 | Thermo Fisher Scientific / NEI Corporation | — |
| 223 | CHROMIUM METAL, PIECES, 99.2% pure, 3-12 mm,  Cr | LOOKUP_NEEDED | $6,543 | 6 | Thermo Fisher Scientific / Universidad Tecnica Federico | — |
| 228 | IRON (III) NITRATE, NONAHYDRATE, 99.999+% pure, Sigma-Aldrich Part No. 529303-BU | LOOKUP_NEEDED | $6,407 | 2 | Aldrich Chemical Co. LLC | — |
| 231 | BARIUM SULFATE, USP, -325 mesh, BaSO₄ | LOOKUP_NEEDED | $6,301 | 4 | Merit Medical Systems Inc. | USP |
| 236 | CALCIUM SULFIDE, 99.9% pure, -325 mesh,  CaS | LOOKUP_NEEDED | $5,851 | 3 | Thermo Fisher Scientific | — |
| 243 | SODIUM CHLORIDE, USP grade, NaCl | LOOKUP_NEEDED | $5,542 | 15 | HACH Company / Alfasigma USA, Inc. | USP |
| 244 | COBALT (II) HYDROXIDE, 99.9% pure, -10 mesh,  Co(OH)₂ | LOOKUP_NEEDED | $5,454 | 4 | Thermo Fisher Scientific | — |
| 248 | VANADIUM OXYSULFATE, HYDRATE, USP, V 19.5 - 23.0%, for C2C Nutra, (Vanadyl Sulfa | LOOKUP_NEEDED | $5,290 | 1 | C2C Nutra, LLC | USP |
| 249 | BERYLLIUM OXIDE, 99.95% pure, -200 mesh,  BeO | LOOKUP_NEEDED | $5,280 | 3 | Aldrich Chemical Co. LLC / Thermo Fisher Scientific | — |
| 250 | NICKEL (II) CHLORIDE, HEXAHYDRATE, 99.5% pure, -20 mesh, (Nickelous Chloride, He | LOOKUP_NEEDED | $5,264 | 7 | Spectrum Chemical Mfg. Corp / FreeForm Technologies / MP Bio | — |
| 257 | ARSENIC (III) OXIDE, Reagent grade, -60 mesh, (Arsenic Trioxide), As₂O₃ | 1327-53-3 | $5,085 | 5 | Sigma-Aldrich International GmbH | Reagent |
| 263 | COPPER (II) SULFATE, ANHYDROUS, Reagent, -100 mesh, (Cupric Sulfate), CuSO₄ | LOOKUP_NEEDED | $4,894 | 3 | Thermo Fisher Scientific / ES Laboratory, LLC | Anhydrous / Reagent |
| 268 | MERCURY (II) OXIDE, RED, 99.9% pure, -200 mesh, (Mercuric Oxide, Red), HgO | LOOKUP_NEEDED | $4,749 | 3 | HACH Company / ESS / B3 Systems, Inc. | — |
| 282 | BORON OXIDE, 99.9% pure, -60 mesh, (Boron Trioxide; Boric Anhydride), B₂O₃ | LOOKUP_NEEDED | $4,179 | 3 | Thermo Fisher (Kandel) GmbH / DSO National Laboratories / Ye | — |
| 286 | POTASSIUM THIOCYANATE, ACS Reagent, powder, (Potassium Sulfocyanate), KSCN | 333-20-0 | $4,048 | 3 | Carl Roth GmbH+Co. KG | ACS Reagent / Reagent |
| 290 | LITHIUM HYDRIDE, 99.9% pure, -10 mesh, Oxygen of 500ppm (according to Lawrence L | LOOKUP_NEEDED | $3,903 | 2 | Lawrence Livermore National Laboratory | — |
| 293 | ALUMINUM METAL, POWDER, 99.975% pure, -325 mesh, approx. 15 microns avg, Al | LOOKUP_NEEDED | $3,726 | 2 | Aldrich Chemical Co. LLC | — |
| 295 | SODIUM PYROPHOSPHATE, DECAHYDRATE, ACS Reagent, crystal, (Diphosphoric Acid, Tet | LOOKUP_NEEDED | $3,696 | 12 | HACH Company / Symcon, Inc / Symcon, Inc. | ACS Reagent / Reagent |
| 304 | CADMIUM SULFATE, 8/3 HYDRATE, ACS Reagent, crystal,  3CdSO₄.8H₂O | LOOKUP_NEEDED | $3,472 | 4 | Spectrum Chemical Mfg. Corp / Thermo Fisher Scientific / Rap | ACS Reagent / Reagent |
| 308 | NIOBIUM (V) CHLORIDE, 99.95% pure, -15 mm lumps, (Columbium Pentachloride), NbCl | LOOKUP_NEEDED | $3,406 | 2 | Thermo Fisher Scientific | — |
| 311 | MANGANESE (III) OXIDE, 99.5% pure, -325 mesh, (Manganese Sesquioxide), Mn₂O₃ | LOOKUP_NEEDED | $3,350 | 2 | Thermo Fisher Scientific / Pennsylvania State University | — |
| 316 | THALLIUM (I) ACETATE, 99.999% pure, -60 mesh, (Thallous acetate; Acetic Acid, Th | LOOKUP_NEEDED | $3,228 | 2 | Thermo Fisher Scientific | — |
| 323 | SODIUM ACETATE, ANHYDROUS, FCC, crystal, (Acetic Acid, Sodium Salt), NaOOCCH₃ | LOOKUP_NEEDED | $3,120 | 2 | Solar Biotech | Anhydrous / FCC |
| 328 | PLATINUM (IV) CHLORIDE, Sigma Aldrich Part No. 379840-Bulk, (99.99% pure), (Plat | LOOKUP_NEEDED | $3,091 | 3 | Aldrich Chemical Co. LLC | — |
| 334 | POTASSIUM TETRABORATE, TETRAHYDRATE, 99% pure, -20 mesh, granular, (Potassium Bo | LOOKUP_NEEDED | $2,970 | 7 | Hakala Research Lab / HACH Company | — |
| 340 | ZINC METAL, Developmental for Hach | LOOKUP_NEEDED | $2,874 | 2 | HACH Company | — |
| 342 | LITHIUM CARBONATE, 97% - 98% pure, Tech Grade, Li₂CO₃ | LOOKUP_NEEDED | $2,750 | 1 | Trafa Pharmaceutical Inc | — |
| 347 | AMMONIUM HYDROGEN SULFATE, 99.9% pure, lump, (Ammonium Bisulfate), NH₄HSO₄ | LOOKUP_NEEDED | $2,674 | 5 | Thermo Fisher Scientific | — |
| 353 | SELENIUM (IV) SULFIDE, 99% pure, -60 mesh, Sigma-Aldrich Part No. 257710, (Selen | LOOKUP_NEEDED | $2,625 | 3 | Aldrich Chemical Co. LLC | — |
| 363 | POTASSIUM TUNGSTATE, 99.95% pure, -100 mesh, (Potassium Tungsten Oxide), K₂WO₄ | 7790-60-5 | $2,459 | 5 | Aldrich Chemical Co. LLC / Acros Organics B.V. | — |
| 379 | CADMIUM OXIDE, 99.95% pure, -325 mesh,  CdO | LOOKUP_NEEDED | $2,202 | 3 | Thermo Fisher Scientific / BeanTown Chemical Corp / SCP Scie | — |
| 384 | BARIUM CHLORIDE, DIHYDRATE, ACS Reagent, crystal, BaCl₂.2H₂O | LOOKUP_NEEDED | $2,132 | 5 | HACH Company | ACS Reagent / Reagent |
| 390 | TANTALUM (V) OXIDE, 99% pure, -325 mesh, Ta₂O₅ | LOOKUP_NEEDED | $2,073 | 2 | Aldrich Chemical Co. LLC | — |
| 391 | MAGNESIUM OXIDE, 98% pure, -10 +50 mesh beads, Sigma-Aldrich Part No. 220361, Mg | LOOKUP_NEEDED | $2,059 | 3 | Aldrich Chemical Co. LLC | — |
| 393 | SODIUM HYDROXIDE, 99.99% pure, pellets, (Caustic soda), NaOH | LOOKUP_NEEDED | $2,044 | 4 | Thermo Fisher Scientific / Duke University | — |
| 397 | POTASSIUM PERSULFATE, ACS Reagent, crystalline, (Potassium Peroxydisulfate), K₂S | LOOKUP_NEEDED | $1,984 | 1 | HACH Company | ACS Reagent / Reagent |
| 401 | SODIUM SULFITE, 98% pure, crystalline powder, Cambrex Specification No 836998, N | LOOKUP_NEEDED | $1,838 | 2 | Cambrex Charles City, Inc. | — |
| 404 | MAGNESIUM-ALUMINUM OXIDE, 99% pure, -325 mesh, (Double Spinel), MgAl₂O₄ | LOOKUP_NEEDED | $1,770 | 2 | Thermo Fisher Scientific / The Ohio State University | — |
| 411 | SODIUM CHLORIDE, ACS Reagent, crystal,  NaCl | LOOKUP_NEEDED | $1,697 | 12 | HACH Company / Bio Basic Inc. | ACS Reagent / Reagent |
| 417 | ZINC OXIDE, 99.999% pure, -325 mesh, < 5 microns average, ZnO | LOOKUP_NEEDED | $1,582 | 5 | Aldrich Chemical Co. LLC / Biolase, Inc | — |
| 421 | CALCIUM HYDROXIDE, 99.995% pure, Sigma-Aldrich Part No. 450146, (Slaked Lime), C | LOOKUP_NEEDED | $1,545 | 1 | Aldrich Chemical Co. LLC | — |
| 426 | ZINC METAL, COARSE POWDER, 99.9% pure, ACS Reagent, +20 mesh, Zn | LOOKUP_NEEDED | $1,469 | 2 | Spectrum Chemical Mfg. Corp | ACS Reagent / Reagent |
| 438 | VANADIUM METAL, POWDER, 99.5% pure, -325 mesh, V | LOOKUP_NEEDED | $1,339 | 3 | Aldrich Chemical Co. LLC | — |
| 452 | MOLYBDENUM (IV) OXIDE, 99% pure, -200 mesh, (Molybdenum Dioxide), MoO₂ | LOOKUP_NEEDED | $1,159 | 5 | Thermo Fisher Scientific / SCI Engineered Materials, Inc. | — |
| 463 | ANTIMONY METAL, POWDER, 99.999% pure, -200 mesh, Sb | LOOKUP_NEEDED | $1,087 | 2 | Thermo Fisher Scientific | — |
| 464 | IRON METAL, POWDER, ELECTROLYTIC, 99.9% pure, -20 mesh,  Fe | LOOKUP_NEEDED | $1,082 | 5 | Thermo Fisher Scientific | — |
| 466 | POTASSIUM TUNGSTATE, 99.5% pure, -60 mesh, (Potassium Tungsten Oxide), K₂WO₄ | LOOKUP_NEEDED | $1,056 | 1 | Thermo Fisher Scientific | — |
| 471 | SILICON (IV) OXIDE, 99.5% pure, -325 mesh, <3 microns average, (Silicon Dioxide, | 7631-86-9 | $1,017 | 2 | Thermo Fisher Scientific / The Ohio State University | — |
| 494 | POTASSIUM OXALATE, MONOHYDRATE, ACS Reagent, crystal, (Oxalic Acid, Potassium Sa | LOOKUP_NEEDED | $905 | 2 | VWR Chemicals, LLC / Avantor Performance Materials | ACS Reagent / Reagent |
| 500 | ALUMINUM CARBIDE, 95% pure, -325 mesh, < 44  microns, Sigma-Aldrich Part No. 241 | LOOKUP_NEEDED | $880 | 1 | Aldrich Chemical Co. LLC | — |
| 505 | NICKEL (II) ACETATE, TETRAHYDRATE, Reagent grade, crystal,  Ni(OOCCH₃)₂.4H₂O | LOOKUP_NEEDED | $868 | 1 | Spectrum Chemical Mfg. Corp | Reagent |
| 507 | SILICON (IV) OXIDE, 99.99% pure, 3-12 mm granules, fused, (Silicon Dioxide, Sili | LOOKUP_NEEDED | $848 | 3 | Thermo Fisher Scientific / Southwest Research Institute | — |
| 512 | POTASSIUM NITRATE, ACS Reagent, -4 mesh,  KNO₃ | LOOKUP_NEEDED | $824 | 3 | HACH Company / METSS Corporation | ACS Reagent / Reagent |
| 520 | TUNGSTEN METAL, POWDER, 99.999% pure, <10 microns average,  W | LOOKUP_NEEDED | $763 | 1 | Aldrich Chemical Co. LLC | — |
| 524 | MAGNESIUM BROMIDE, HEXAHYDRATE, 99% pure, -20 mesh,  MgBr₂.6H₂O | LOOKUP_NEEDED | $736 | 1 | Thermo Fisher Scientific | — |
| 533 | NICKEL (II) HYDROXIDE, 99.5% pure, -100 mesh, (Nickelous Hydroxide), Ni(OH)₂ | LOOKUP_NEEDED | $668 | 1 | Thermo Fisher Scientific | — |
| 539 | SODIUM MOLYBDATE, DIHYDRATE, ACS Reagent, crystal, (Molybdic Acid, Sodium Salt,  | LOOKUP_NEEDED | $643 | 2 | Avantor Performance Materials / Nutrisol LLC | ACS Reagent / Reagent |
| 540 | TELLURIUM (IV) OXIDE, 99.5% pure, -60 mesh, (Tellurium Dioxide), TeO₂ | LOOKUP_NEEDED | $640 | 1 | Spectrum Chemical Mfg. Corp | — |
| 542 | ARSENIC (III) OXIDE, 99.5% pure, -100 mesh, (Arsenic Trioxide; Arsenous Acid), A | LOOKUP_NEEDED | $628 | 1 | BeanTown Chemical Corp | — |
| 543 | THALLIUM (I) CHLORIDE, 99% pure,  powder,Thermo Fisher Part No 208880000, (Thall | LOOKUP_NEEDED | $623 | 1 | Acros Organics B.V. | — |
| 546 | SILICON (IV) NITRIDE, ALPHA, 99.7% pure, <2 microns average,  Si₃N₄ | LOOKUP_NEEDED | $605 | 1 | Aldrich Chemical Co. LLC | — |
| 548 | HAFNIUM (IV) FLUORIDE, 99.9% pure, -60 mesh, (Hafnium Tetrafluoride), HfF₄ | LOOKUP_NEEDED | $590 | 1 | Thermo Fisher Scientific | — |
| 550 | GALLIUM (III) ETHOXIDE, 99.9% pure, crystal/ granule,  Ga(OC₂H₅)₃ | LOOKUP_NEEDED | $581 | 1 | Thermo Fisher Scientific | — |
| 564 | COPPER (I) OXIDE, 99.9% pure, -200 mesh, red, (Cuprous Oxide), Cu₂O | LOOKUP_NEEDED | $516 | 2 | Thermo Fisher Scientific | — |
| 585 | NICKEL (II) HYDROXIDE, 98.8% pure, -100 mesh, (Nickelous Hydroxide), Ni(OH)₂ | LOOKUP_NEEDED | $430 | 1 | Thermo Fisher Scientific | — |
| 592 | ANTIMONY (III) BROMIDE, 99.5% pure, -8 mesh, (Antimony Tribromide), SbBr₃ | LOOKUP_NEEDED | $405 | 1 | Thermo Fisher Scientific | — |
| 594 | SODIUM THIOSULFATE, PENTAHYDRATE, ACS Reagent, crystal,  Na₂S₂O₃.5H₂O | LOOKUP_NEEDED | $402 | 4 | World Bioproducts LLC | ACS Reagent / Reagent |
| 619 | TITANIUM SILICIDE (5:3 atomic), 99.5% pure, -325 mesh,  Ti₅Si₃ | LOOKUP_NEEDED | $283 | 1 | Thermo Fisher Scientific | — |
| 625 | STRONTIUM HYDROXIDE, OCTAHYDRATE, 99% pure, -6 mesh,  (Strontium Hydrate, Octahy | LOOKUP_NEEDED | $252 | 1 | Thermo Fisher Scientific | — |
| 640 | THALLIUM (I) SULFATE, 99.99% pure, -40 mesh, (Thallous Sulfate) Tl₂SO₄ | LOOKUP_NEEDED | $220 | 1 | Aldrich Chemical Co. LLC | — |
| 643 | CHROMIUM (III) OXIDE, ANHYDROUS, 99% pure, -325 mesh, Green, (Chromium Sesquioxi | LOOKUP_NEEDED | $202 | 1 | Spectrum Chemical Mfg. Corp | Anhydrous |
| 646 | TERBIUM (III) ACETATE HYDRATE, 99.99% pure, powder, Tb(OOCCH₃)₃.xH₂O | LOOKUP_NEEDED | $195 | 1 | Alfa Aesar / Thermo Fisher | — |
| 647 | CADMIUM BROMIDE, TETRAHYDRATE, 99.5% pure, -80 mesh,  CdBr₂.4H₂O | LOOKUP_NEEDED | $195 | 2 | Thermo Fisher Scientific | — |
| 648 | VANADIUM OXYSULFATE, HYDRATE, Ortho-Clinical Diagnostics #R1018, Rev 6, VOSO₄.xH | LOOKUP_NEEDED | $193 | 2 | Ortho Clinical Diagnostics | — |
| 649 | MANGANESE METAL, FLAKES, 99.9% pure, 50 mm and smaller,  Mn | LOOKUP_NEEDED | $188 | 2 | Spectrum Chemical Mfg. Corp / Universidad Tecnica Federico | — |
| 651 | CADMIUM NITRATE, TETRAHYDRATE, Chemically Pure, crystal, Cd(NO₃)₂.4H₂O | LOOKUP_NEEDED | $180 | 3 | Thermo Fisher Scientific / ESS | — |
| 656 | LITHIUM MANGANATE, 99.5% pure, -325 mesh, (Lithium Manganese Oxide), LiMn₂O₄ | LOOKUP_NEEDED | $162 | 1 | Thermo Fisher Scientific | — |
| 661 | ZINC METAL, POWDER, 99.5% pure, -325 mesh, Zn | LOOKUP_NEEDED | $156 | 2 | HACH Company | — |
| 662 | CESIUM CHLORIDE, 99.9% pure, -6 mesh,  CsCl | LOOKUP_NEEDED | $152 | 1 | Aldrich Chemical Co. LLC | — |
| 689 | NICKEL (II) SULFATE, HEXAHYDRATE, ACS Reagent, -4mesh, (Nickelous Sulfate, Hexah | LOOKUP_NEEDED | $97 | 1 | Glanbia Nutritionals (NA), Inc | ACS Reagent / Reagent |
| 692 | TARTARIC ACID, Technical grade, crystal, (2,3 Dihydroxybutanedioic acid) (HO₂CCH | LOOKUP_NEEDED | $92 | 1 | HACH Company | Technical Grade |
| 726 | COPPER (II) CARBONATE, BASIC, 99% pure, -325 mesh, (Copper (II) Carbonate Dihydr | LOOKUP_NEEDED | $9 | 1 | HACH Company | — |
| 753 | TELLURIUM METAL, POWDER, 99.99% pure, -30 mesh,  Te | LOOKUP_NEEDED | $-94 | 2 | Thermo Fisher Scientific | — |
| 759 | AMMONIUM PHOSPHATE DIBASIC, FCC, crystal, (Diammonium Hydrogen Phosphate). (NH₄) | LOOKUP_NEEDED | $-244 | 1 | Solar Biotech | FCC |
| 761 | CALCIUM PHOSPHATE MONOBASIC, MONOHYDRATE, Reagent, powder, (Monocalcium Phosphat | LOOKUP_NEEDED | $-325 | 2 | Spectrum Chemical Mfg. Corp / XL Sci-Tech, Inc. | Reagent |
| 773 | SODIUM MOLYBDATE, DIHYDRATE, 99.5% pure, -40 mesh, (Molybdic Acid, Sodium Salt;  | LOOKUP_NEEDED | $-1,044 | 3 | Biotron Laboratories, Inc. / 0014212 | — |
| 774 | Jerrican, 5 gallon, HDPE, natural, square, closed head, 3H1/Y1.9/150 | LOOKUP_NEEDED | $-1,102 | 2 | HACH Company | — |
| 780 | GADOLINIUM OXIDE, 99.999% pure, -325 mesh,  Gd₂O₃ | LOOKUP_NEEDED | $-2,844 | 1 | Advance Research Chemical | — |

### Consumer & Industrial (29 chemicals, $347,493 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 15 | CITRIC ACID, ANHYDROUS, Technical Grade, Granular (2-Hydroxy-1,2,3-propanetricar | LOOKUP_NEEDED | $141,221 | 10 | United Chemical International LLC | Anhydrous / Technical Grade |
| 21 | AMMONIUM METAVANADATE, 99% pure, Reagent, -20 mesh, (Ammonium Vanadium Oxide), N | LOOKUP_NEEDED | $91,920 | 19 | Cosmocel S.A. / Verdesian Life Sciences, LLC / Atotech USA,  | Reagent |
| 60 | SODIUM CHLORIDE, 99.9% pure, NaCl  (Developmental Product for ASEA) | LOOKUP_NEEDED | $37,734 | 17 | ASEA Global | — |
| 118 | AMMONIUM BIFLUORIDE, 99% pure, crystalline, (Ammonium Hydrogen Fluoride), (NH₄)H | 1341-49-7 | $16,783 | 12 | APV Engineered Coatings | — |
| 209 | POTASSIUM CYANIDE, ACS Reagent, granular, KCN | 151-50-8 | $7,457 | 15 | SWIC Scientific & Chemical / HACH Company / Connovation Ltd | ACS Reagent / Reagent |
| 211 | ZINC ACETATE, DIHYDRATE, 27.5% solution, 99% pure, Zn(OOCCH₃)₂.2H₂O | LOOKUP_NEEDED | $7,302 | 3 | Fifield Inc USA | — |
| 217 | SODIUM CITRATE, DIHYDRATE, 99% pure, granular, (Trisodium Citrate, Dihydrate), N | LOOKUP_NEEDED | $6,949 | 2 | United Chemical International LLC | — |
| 224 | COBALT (II) HYDROXIDE, powder, Part No. 2900205-0001, (Special for Acme Electric | LOOKUP_NEEDED | $6,458 | 5 | Acme Aerospace Inc. | — |
| 277 | COPPER (II) NITRATE, HYDRATE, 99% pure, crystal, (Cupric Nitrate, Hydrate), Cu(N | LOOKUP_NEEDED | $4,467 | 8 | PIDC / 0014285 / K2 Concepts, Inc | — |
| 303 | POTASSIUM FLUORIDE, DIHYDRATE, 98% pure, powder, crystal, or granule, FH₄KO₂ | LOOKUP_NEEDED | $3,482 | 4 | PIDC | — |
| 307 | SODIUM PHOSPHATE MONOBASIC, MONOHYDRATE, ACS Reagent, -50 mesh, (Monosodium Phos | LOOKUP_NEEDED | $3,407 | 6 | Crystal Claire Cosmetics Inc. / Supreme Resources, Inc. | ACS Reagent / Reagent |
| 320 | LITHIUM HYDROXIDE, MONOHYDRATE, 99.9% pure, -20 mesh,  LiOH.H₂O | LOOKUP_NEEDED | $3,189 | 5 | PIDC / NEI Corporation | — |
| 335 | CADMIUM BROMIDE, ANHYDROUS, 99.9% pure, -60 mesh, CdBr₂ | LOOKUP_NEEDED | $2,966 | 4 | ArtCraft Chemicals, Inc. | Anhydrous |
| 336 | AMMONIUM MOLYBDATE, TETRAHYDRATE (VI), ACS Reagent, crystal, (Ammonium Paramolyb | 12027-67-7 | $2,930 | 5 | PIDC / Honeywell International Inc | ACS Reagent / Reagent |
| 337 | LITHIUM ORTHOSILICATE, 99.9% pure, -325 mesh, Li₄SiO₄ | LOOKUP_NEEDED | $2,915 | 1 | PPG Aerospace | — |
| 408 | COPPER (I) CYANIDE, 93% pure, powder CuCN | LOOKUP_NEEDED | $1,710 | 4 | SWIC Scientific & Chemical | — |
| 415 | ALUMINUM SULFATE, HYDRATE, USP, (Alum), Al₂(SO₄)₃.xH₂O | LOOKUP_NEEDED | $1,590 | 3 | PIDC / PCCA | USP |
| 460 | CALCIUM ACETATE, HYDRATE, Reagent, powder,  Ca(OOCCH₃)₂.xH₂O | LOOKUP_NEEDED | $1,100 | 1 | Advancing Eco-Agriculture, LLC | Reagent |
| 462 | LEAD (IV) OXIDE, Missiles & Space Batteries, Drawing No. 274618, Rev. 4, (Lead D | LOOKUP_NEEDED | $1,100 | 1 | Missiles & Space Batteries Ltd | — |
| 501 | SCANDIUM OXIDE, 99.9% pure, -325 mesh, Sc₂O₃ | LOOKUP_NEEDED | $877 | 2 | PIDC / Ben-Gurion University | — |
| 510 | AMMONIUM PHOSPHATE DIBASIC, ACS Reagent, crystal,(Diammonium Hydrogen Phosphate) | LOOKUP_NEEDED | $834 | 3 | PIDC | ACS Reagent / Reagent |
| 545 | SODIUM CARBONATE, ANHYDROUS, USP,  powder, Na₂CO₃ | LOOKUP_NEEDED | $610 | 2 | PIDC / Unique Corals, Inc. | Anhydrous / USP |
| 563 | COPPER (II) ACETATE, MONOHYDRATE, ACS Reagent, crystal, (Cupric Acetate, Monohyd | LOOKUP_NEEDED | $519 | 1 | PIDC | ACS Reagent / Reagent |
| 582 | POTASSIUM NITRATE, FCC, -20 mesh,  KNO₃ | LOOKUP_NEEDED | $445 | 2 | Hoyco Food Ingredients / 0015011 | FCC |
| 613 | AMMONIUM BICARBONATE, Reagent, powder, (Ammonium Hydrogen Carbonate), NH₄HCO₃ | LOOKUP_NEEDED | $304 | 1 | PIDC | Reagent |
| 615 | MANGANESE (II) ACETATE, TETRAHYDRATE, 99.9% pure, -10 mesh, Mn(OOCCH₃)₂.4H₂O | LOOKUP_NEEDED | $295 | 1 | PIDC | — |
| 616 | SODIUM METABISULFITE, 99.9% pure, Reagent, -100 mesh, (Sodium Pyrosulfite), Na₂S | LOOKUP_NEEDED | $292 | 2 | WET International, Inc | Reagent |
| 677 | LITHIUM OXIDE, 98.9% pure, powder, (Li₂O) | LOOKUP_NEEDED | $111 | 1 | PPG Aerospace | — |
| 776 | Fiber drum, 15 gallon, Lok-Rim, Item DRFI01831NA20003 | LOOKUP_NEEDED | $-1,473 | 18 | Americhem Pharmaceutical Corp. / BASF Mobile Emissions Catal | — |

### Unclassified (362 chemicals, $1,071,580 GP)

| # | Chemical | CAS | 3-yr GP | Txns | Top Customers | Certs |
|---|---|---|---|---|---|---|
| 73 | MERCURY AMMONIUM CHLORIDE, USP, powder, (Ammoniated Mercury), NH₂HgCl | LOOKUP_NEEDED | $31,484 | 5 | E. W. Abrahams & Sons Ltd. | USP |
| 77 | POTASSIUM HYDROXIDE, 99.9% pure, flake, KOH | 1310-58-3 | $29,394 | 23 | Standard Meat Company / KL Coating / ExPost Technology | — |
| 96 | C3067 | LOOKUP_NEEDED | $20,697 | 2 | 0014220 | — |
| 103 | LEAD (IV) OXIDE, 99% pure, -100 mesh, (Lead Peroxide; Lead Dioxide), PbO₂ | LOOKUP_NEEDED | $19,138 | 12 | Materion Advanced Materials / South Coast Products / Sentury | — |
| 105 | ASHWAGANDHA ROOT EXT 5.5% WITH ANOLIDES (KSM66) VEGAN | LOOKUP_NEEDED | $18,920 | 6 | American Nutritional Corp. | — |
| 109 | SILICON (IV) NITRIDE, w/2% MAGNESIUM OXIDE, 99.9% pure,  < 10 mu avg, (Tosoh Par | LOOKUP_NEEDED | $18,718 | 4 | Tosoh SMD, Inc. | — |
| 112 | LEAD (II) OXIDE, 99.9% pure, -325 mesh, < 5 microns average, (Lead Monoxide), Pb | LOOKUP_NEEDED | $17,718 | 13 | TD*X Associates, LP / Eastman Chemical Company / ESS | — |
| 114 | BARIUM SULFATE, 99% pure, -325 mesh, BaSO₄ | LOOKUP_NEEDED | $17,031 | 6 | Nugreen Metals, LLC / Merit Medical Systems Inc. / Catalytic | — |
| 115 | SODIUM SELENITE, ANHYDROUS, 99.5% pure, -20 mesh, (special for Innophos), Na2SeO | LOOKUP_NEEDED | $16,982 | 6 | Innophos, LLC | Anhydrous |
| 116 | ANTIMONY (III) OXIDE, 99.9% pure, -325 mesh, 1 micron average, (Antimony Trioxid | LOOKUP_NEEDED | $16,856 | 10 | Höganäs / Hallmark Metals Corporation / HACH Company | — |
| 119 | LEAD (IV) OXIDE, Orica Sweden PT-MS:338, Issue 3, Material No. 30002019, (Lead P | LOOKUP_NEEDED | $16,680 | 3 | Orica Sweden AB | — |
| 120 | INDOPOL H-100 | LOOKUP_NEEDED | $16,569 | 8 | Citrus and Allied Essences Ltd | — |
| 121 | YTTRIUM OXIDE, 99.999% pure, powder, (Yttria), Y₂O₃ | LOOKUP_NEEDED | $15,673 | 3 | Belvac | — |
| 122 | LANTHANUM NITRATE, HEXAHYDRATE, 99% pure, -6 mesh,  La(NO₃)₃.6H₂O | LOOKUP_NEEDED | $15,592 | 10 | Catalytic Combustion Corp | — |
| 124 | BARIUM HYDROXIDE, MONOHYDRATE, 99.5% pure, -100 mesh, Ba(OH)₂.H₂O | LOOKUP_NEEDED | $15,567 | 13 | Atlas Putty Products Company / Bio Development / METSS Corpo | — |
| 125 | CALCIUM HYDROXIDE, 97% pure, -200 mesh, (Slaked Lime), Ca(OH)₂ | LOOKUP_NEEDED | $15,529 | 10 | Low Carbon / 0014230 / Green Jeeva LLC | — |
| 126 | METAL DISPERSION, 9.25% Cr, 0.59% Pb, special for Eastman | LOOKUP_NEEDED | $15,112 | 2 | Eastman Chemical Company | — |
| 128 | CIP CAUSTIC WASH, 10% solution with anti-foaming agents | LOOKUP_NEEDED | $14,696 | 9 | Crazy Bottling Company, LLC. | — |
| 129 | AMMONIUM NITRATE, ACS Reagent, crystal, NH₄NO₃ | 6484-52-2 | $14,286 | 15 | NCCM Global Roll Technology / Analytichem Canada Inc. / AECO | ACS Reagent / Reagent |
| 131 | SULFUR, SUBLIMED, USP, powder, S | 7704-34-9 | $14,026 | 12 | Harcros Chemicals, Inc. / Raymond Labs / Americhem Pharmaceu | USP |
| 133 | DEXTROSE, ANHYDROUS, Technical grade, powder, (d-(+)-Glucose), CH₂OH(CHOH)₄CHO | LOOKUP_NEEDED | $13,801 | 1 | Hello Nature Bioscience, LLC | Anhydrous / Technical Grade |
| 137 | SODIUM HYDROXIDE, 99% pure, beads, (Caustic Soda), NaOH | LOOKUP_NEEDED | $13,407 | 31 | Alchemy Geopolymer Solutions / Southern Steam Service / PIDC | — |
| 141 | TANTALUM (V) ETHOXIDE, 99.999% pure, liquid,  Ta(C₂H₅O)₅ | LOOKUP_NEEDED | $12,702 | 5 | Richter Precision Inc. | — |
| 142 | STRONTIUM CARBONATE, 98% pure, powder, Ba SrCO₃ | LOOKUP_NEEDED | $12,346 | 1 | 0014252 | — |
| 145 | STRONTIUM CHLORIDE, HEXAHYDRATE, ACS Reagent, crystal, SrCl₂.6H₂O | LOOKUP_NEEDED | $12,136 | 13 | Sea World Parks  & Entertainment / Corechem, Inc. / Thermo F | ACS Reagent / Reagent |
| 146 | RUTHENIUM (IV) OXIDE, ANHYDROUS, 99.95% pure, -100 mesh, (Ruthenium Dioxide), Ru | LOOKUP_NEEDED | $12,131 | 2 | Rogers Corporation | Anhydrous |
| 148 | VANADIUM (V) OXIDE, 99.6% pure, -20 mesh, (Vanadium Pentoxide), V₂O₅ | LOOKUP_NEEDED | $11,927 | 5 | Mo-Sci Corporation / Eleqtrion Industries Inc. | — |
| 150 | STRONTIUM CARBONATE, 99% pure, typically 1 micron, Ba < 2%, SrCO₃ | LOOKUP_NEEDED | $11,865 | 1 | Koprimo S.A. de C.V. | — |
| 152 | CALCIUM ACETATE, Anhydrous, 98% pure, powder, C₄H₆O₄Ca | LOOKUP_NEEDED | $11,591 | 1 | DAXX | Anhydrous |
| 154 | TITANIUM (IV) ETHOXIDE, Grace Davison Document No. EDRM -042, Rev. 2, (Titanium  | LOOKUP_NEEDED | $11,439 | 2 | W.R. Grace | — |
| 162 | ZINC ACETATE, DIHYDRATE, USP, powder,  Zn(OOCCH₃)₂.2H₂O | 5970-45-6 | $10,736 | 7 | Ask Chemicals L.P. / Weeks and Leo / Biotone | USP |
| 163 | 17789 | LOOKUP_NEEDED | $10,665 | 1 | Oakwood Products, Inc. | — |
| 164 | CHROMIUM (III) OXIDE, ANHYDROUS, 99.5% pure, -325  mesh, typ. 0.5 mu, Green, (Ch | 1308-38-9 | $10,651 | 18 | Heraeus Precious Metals NA / Eastman Chemical Company / Nexc | Anhydrous |
| 170 | SODIUM SILICATE, 40% SOLUTION, 99% pure, (Sodium Metasilicate Solution) Na₂SiO₃ | LOOKUP_NEEDED | $10,294 | 12 | HTM Manufacturing / Alchemy Geopolymer Solutions | — |
| 172 | OXALIC ACID, DIHYDRATE, Technical grade, crystal, (Ethanedioic Acid, Dihydrate), | LOOKUP_NEEDED | $10,132 | 4 | Minoritech, Inc. / METSS Corporation | Technical Grade |
| 174 | BARIUM SULFATE, 99% pure, -100 mesh, BaSO₄ | 7727-43-7 | $9,578 | 19 | Clean Air Cats / Pyrotek High Temperature / Wagstaff Inc. | — |
| 175 | LITHIUM CHLORIDE, 99.8% pure, -20 mesh, LiCl | 7447-41-8 | $9,452 | 12 | International Battery Metals / Verdesian Life Sciences, LLC  | — |
| 176 | C3071 | LOOKUP_NEEDED | $9,385 | 1 | 0014216 | — |
| 179 | SODIUM CHLORITE, 80% pure, powder/flake | LOOKUP_NEEDED | $9,206 | 7 | Cyber Enviro-Tech / Stellar Chemical Corp | — |
| 182 | POTASSIUM IODIDE, ACS Reagent, -20 mesh, KI | LOOKUP_NEEDED | $9,146 | 6 | General Ecology Inc. / WET International, Inc / California A | ACS Reagent / Reagent |
| 186 | ZINC SULFATE, HEPTAHYDRATE, Atotech Material No. 1665095,_x000D_
ZnSO₄.7H₂O | LOOKUP_NEEDED | $8,985 | 9 | Atotech USA, LLC | — |
| 187 | Nitric Acid, 10µM Solution, pH Target 5 | LOOKUP_NEEDED | $8,955 | 1 | NuVision Engineering, Inc. | — |
| 193 | SODIUM NITRITE, FCC, granular,  NaNO₂ | LOOKUP_NEEDED | $8,434 | 2 | Casey Ingredients, Inc. | FCC |
| 198 | MANGANESE (II) CARBONATE, 98% pure, -200 mesh, MnCO₃ | LOOKUP_NEEDED | $8,143 | 9 | SKF USA, Inc. / Mason Color Works, Inc / NC State University | — |
| 199 | 12034 | LOOKUP_NEEDED | $8,134 | 2 | 0014227 / Honeywell | — |
| 201 | POTASSIUM FLUORIDE, ANHYDROUS, 99% pure, ACS Reagent, -20 mesh,  KF | LOOKUP_NEEDED | $7,919 | 3 | Kingston Process Metallurgy | ACS Reagent / Anhydrous / Reagent |
| 203 | THALLIUM (I) ACETATE, 99.9% pure, -60 mesh, (Thallous Acetate),  TlOOCCH₃ | LOOKUP_NEEDED | $7,836 | 4 | DC Fine Chemicals / Labworld International Corp. | — |
| 205 | MAGNESIUM OXIDE, 98% pure, -200 mesh, MgO | LOOKUP_NEEDED | $7,719 | 7 | Babcock & Wilcox Company / Hanco Industries, ltd. / KPL Grou | — |
| 207 | LEAD (IV) OXIDE, meeting MIL-L-376C, Type I, Class 2, (Lead Dioxide, Lead Peroxi | LOOKUP_NEEDED | $7,596 | 6 | Celanese Ltd / Riverbend Energetics / Valor Tactical Innovat | — |
| 208 | ZINC CHLORIDE, 80% solution, (special for IOWA DOT) ZnCl₂ | LOOKUP_NEEDED | $7,518 | 1 | IOWA DOT | — |
| 212 | TIN (II) CHLORIDE, ANHYDROUS, 99.5% pure, -4 mesh, (Stannous Chloride, Anhydrous | LOOKUP_NEEDED | $7,248 | 18 | P & O Custom Glass Mirror / MP Biomedicals LLC / BeanTown Ch | Anhydrous |
| 219 | SELENIUM (IV) OXIDE, 99.5% pure, -4 mesh, (Selenium Dioxide), SeO₂ | LOOKUP_NEEDED | $6,916 | 2 | NLCE Denmark, LLC / Coventya, Inc. | — |
| 226 | MERCURY (II) ACETATE, 1.6% Solution, 1.0% as Hg, Hg(C₂H₃O₂)₂ | LOOKUP_NEEDED | $6,437 | 1 | ESS | — |
| 230 | BORIC ACID, 99% pure, powder, (Boracic Acid), H₃BO₃ | LOOKUP_NEEDED | $6,323 | 11 | Prismatik DentalCraft Inc / California Academy of Sciences / | — |
| 232 | AMMONIUM IODIDE, ACS Reagent, granular, NH₄I | 12027-06-4 | $6,074 | 7 | GFS Chemicals, Inc. / Let It Snow Inc. / ArtCraft Chemicals, | ACS Reagent / Reagent |
| 233 | 50% Perchloroethylene / 50% Monochlorobenzene | LOOKUP_NEEDED | $6,062 | 1 | Eastman Chemical Company | — |
| 234 | AMMONIUM BICARBONATE, 20% SOLUTION, theoretical saturation in deionized water, ( | LOOKUP_NEEDED | $5,945 | 1 | Cabot Corporation | — |
| 235 | AMMONIUM CHLORIDE, conforming to G.E. Spec. D4G2C,  NH₄Cl | LOOKUP_NEEDED | $5,870 | 4 | Hitemco | — |
| 238 | C3059 | LOOKUP_NEEDED | $5,831 | 4 | Barrington Nutritionals | — |
| 239 | ETHYLENEDIAMINETETRAACETIC ACID, ACS Reagent, powder (EDTA, Free Acid; (Ethylene | 60-00-4 | $5,805 | 6 | Evonik Corporation | ACS Reagent / Reagent |
| 242 | BENZOTRIAZOLE, 99% pure, (Benzotriazole-1,2,3; Aminobenzene), C₆H₄NHN₂ | LOOKUP_NEEDED | $5,551 | 2 | A+ Corporation, LLC | — |
| 245 | SODIUM SULFIDE, TRIHYDRATE, Reagent, flake, (Sodium Monosulfide, Trihydrate), Na | LOOKUP_NEEDED | $5,446 | 6 | ICL Specialty Products Inc / Clean Harbors Environmental Ser | Reagent |
| 247 | SODIUM PEROXIDE, ACS Reagent, -35 mesh,  Na₂O₂ | LOOKUP_NEEDED | $5,364 | 30 | PGM of Texas LLC / Legend Smelting & Recycling / 0015018 | ACS Reagent / Reagent |
| 252 | TANTALUM (V) CHLORIDE, 99.99% pure, -6 mesh, (Tantalum  Pentachloride), TaCl₅ | LOOKUP_NEEDED | $5,210 | 1 | Ti Anode Fabricators Pvt. Ltd. | — |
| 253 | LEAD (II) OXIDE, Special for BST Systems, (BST Spec SMS-000134 Rev. K), PbO | LOOKUP_NEEDED | $5,195 | 2 | BST Systems, Inc. | — |
| 254 | CALCIUM CHLORIDE, DIHYDRATE, ACS Reagent, granular, CaCl₂.2H₂O | LOOKUP_NEEDED | $5,185 | 4 | ProTab Laboratories / Barium & Chemicals, Inc. / Verily Life | ACS Reagent / Reagent |
| 255 | SILVER NITRATE, 99.9+% pure, ACS Reagent, -6 mesh,  AgNO₃ | LOOKUP_NEEDED | $5,169 | 8 | Friendship Oxygen Limited / P & O Custom Glass Mirror / ERC  | ACS Reagent / Reagent |
| 256 | MAGNESIUM CARBONATE HYDROXIDE, PENTAHYDRATE, 99% pure, USP, -100 mesh, (Magnesiu | LOOKUP_NEEDED | $5,153 | 6 | Mo-Sci Corporation / Analytichem Canada Inc. | USP |
| 258 | CIP ACID CLEAN, 10% solution with chelating agents | LOOKUP_NEEDED | $5,063 | 5 | Crazy Bottling Company, LLC. | — |
| 259 | SODIUM BICARBONATE, USP, powder, treated with Tricalcium Phosphate, NaHCO₃ | LOOKUP_NEEDED | $5,046 | 4 | BluePallet / The Lavish Goat | USP |
| 260 | LEAD ACETATE/CHROMIUM ACETATE SOLUTION, 2.0% Pb, 3.4% Cr, for Eastman Chemical | LOOKUP_NEEDED | $4,994 | 1 | Eastman Chemical Company | — |
| 261 | METHANOL, 99% pure, (Methyl Alcohol), CH₃OH | LOOKUP_NEEDED | $4,957 | 2 | NOV, Inc. | — |
| 262 | SURROGATE WASTE, PFOOS Simulant for Nuvision Engineering, crystallization path | LOOKUP_NEEDED | $4,940 | 5 | NuVision Engineering, Inc. | — |
| 265 | COBALT (II) ACETATE, TETRAHYDRATE, 99.9% pure, ACS Reagent, -6 mesh,  Co(OOCCH₃) | LOOKUP_NEEDED | $4,858 | 5 | Chasm Advanced Materials, Inc / NLCE Denmark, LLC | ACS Reagent / Reagent |
| 266 | SODIUM BICARBONATE, Tech grade, powder, NaHCO₃ | LOOKUP_NEEDED | $4,785 | 5 | BluePallet / The Lavish Goat | — |
| 267 | CHROMIUM (II) CHLORIDE, 99.9% pure, -80 mesh, (Chromium Dichloride), CrCl₂ | LOOKUP_NEEDED | $4,764 | 4 | Oakwood Products, Inc. | — |
| 269 | MANGANESE (II) CHLORIDE, TETRAHYDRATE, 99% pure,  ACS Reagent, -40 mesh, (Mangan | LOOKUP_NEEDED | $4,672 | 2 | RWM Technologies / Alsym Energy | ACS Reagent / Reagent |
| 271 | POTASSIUM ACETATE, Kemet M-SPEC 557, Rev. 4, Dated 10/29/2014 (Kemet Part No. 55 | LOOKUP_NEEDED | $4,654 | 7 | Kemet Electronics Corporation | — |
| 272 | CADMIUM OXIDE SLURRY, 50% w/w in water, for Curtiss Wright Flight,  CdO | LOOKUP_NEEDED | $4,611 | 2 | Fastenal | — |
| 273 | BISMUTH (III) NITRATE, PENTAHYDRATE, ACS Reagent,crystal, (Bismuth Trinitrate, P | LOOKUP_NEEDED | $4,602 | 7 | Alsym Energy | ACS Reagent / Reagent |
| 274 | LEAD ACETATE/CHROMIUM ACETATE, 0.44% Pb and 1.02% Cr, for B3 Systems | LOOKUP_NEEDED | $4,594 | 1 | 0014225 | — |
| 275 | CALCIUM NITRATE, TETRAHYDRATE, GE No. GE0024-0562, Ver. 7, GE Part No. CP2688656 | LOOKUP_NEEDED | $4,584 | 3 | Current Lighting Solutions LLC | — |
| 276 | BARIUM CARBONATE, 99% pure, -325 mesh, BaCO₃ | LOOKUP_NEEDED | $4,574 | 6 | Quadra Chemicals Ltd. / Spectra-Mat Inc / Spectra-Mat, Inc ( | — |
| 278 | C3066 | LOOKUP_NEEDED | $4,465 | 1 | 0014225 | — |
| 279 | AMMONIUM POLYPHOSPHATE, >98% pure, -200 mesh, (NH₄PO₃)ₙ | LOOKUP_NEEDED | $4,404 | 6 | NanoTech Materials / Caracara Ventures, LLC / GEMM Technolog | — |
| 281 | TRIETHANOLAMINE, technical grade, liquid, (TEA), C₆H₁₅NO₃ | LOOKUP_NEEDED | $4,278 | 3 | Prismatik DentalCraft Inc | Technical Grade |
| 284 | CALCIUM FLUORIDE, 99% pure, -325 mesh, Superfine, (Fluorspar), CaF₂ | LOOKUP_NEEDED | $4,126 | 7 | Coatings for Industry, Inc. / Mo-Sci Corporation / 0014232 | — |
| 287 | Potassium Carbonate, Anhydrous, 99.998% pure, -20 mesh, K₂CO₃ | LOOKUP_NEEDED | $4,012 | 1 | Gooch & Housego Company | Anhydrous |
| 288 | STRONTIUM HYDROXIDE, ANHYDROUS, Reagent, powder, (Strontium Hydrate, Anhydrous), | LOOKUP_NEEDED | $4,003 | 3 | Brightwell Aquatics / METSS Corporation | Anhydrous / Reagent |
| 291 | SULFAMIC ACID, ACS Reagent, crystal, (Amidosulfonic Acid), H₂NSO₃H | LOOKUP_NEEDED | $3,896 | 3 | Innovative Chemical Technologies, Inc. / Friendship Oxygen L | ACS Reagent / Reagent |
| 294 | GALLIUM (III) OXIDE, 99.995% pure, -100 mesh,  Ga₂O₃ | LOOKUP_NEEDED | $3,700 | 3 | Tosoh SMD, Inc. / 0014246 | — |
| 296 | ZINC HYDROXIDE, 99% pure, powder, Zn(OH)₂ | LOOKUP_NEEDED | $3,678 | 4 | MP Biomedicals LLC / W.R. Meadows. Inc. | — |
| 298 | AMMONIUM METAVANADATE, ACS Reagent, -40 mesh, (Ammonium Vanadate (V); Ammonium V | LOOKUP_NEEDED | $3,567 | 7 | MP Biomedicals LLC / Millipore Sigma / Aldrich Chemical Co.  | ACS Reagent / Reagent |
| 299 | THALLIUM-MERCURY AMALGAM, 11% Tl, (Thallium Amalgam), Hg:Tl | LOOKUP_NEEDED | $3,559 | 4 | Sigma Products & Manufacturing | — |
| 300 | MERCURY PHENYL ACETATE, 98% pure, -40 mesh, (Phenylmercuric Acetate), C₆H₅HgOOCC | LOOKUP_NEEDED | $3,542 | 1 | Polytek Development Corp. | — |
| 301 | CADMIUM OXIDE, 99.7% pure, -200 mesh,  CdO | LOOKUP_NEEDED | $3,541 | 5 | Vallen Canada / SWIC Scientific & Chemical | — |
| 302 | SODIUM IODATE, Reagent, crystal,  NaIO₃ | LOOKUP_NEEDED | $3,488 | 3 | BouMatic / GFS Chemicals, Inc. | Reagent |
| 305 | ZINC METAL, POWDER, 99.9% pure, < 5 microns average, Special for Han Kyung, (Zin | 7440-66-6 | $3,455 | 1 | Han Kyung Special Chemical Co. | — |
| 306 | COPPER (II) SULFATE, PENTAHYDRATE, 99% pure, crystal, (Cupric Sulfate, Pentahydr | LOOKUP_NEEDED | $3,420 | 7 | Alfie Packers, Inc. | — |
| 309 | AMMONIUM MOLYBDATE, TETRAHYDRATE (VI), 99% pure, crystal, (Ammonium Paramolybdat | LOOKUP_NEEDED | $3,398 | 1 | NLCE Denmark, LLC | — |
| 310 | POTASSIUM CARBONATE, ANHYDROUS, Reagent, granular,  K₂CO₃ | 584-08-7 | $3,376 | 4 | Mo-Sci Corporation | Anhydrous / Reagent |
| 312 | IRON (III) ACETYLACETONATE, 99.5% pure, -60 mesh,(Iron 2,4-Pentanedionate), Fe(C | LOOKUP_NEEDED | $3,314 | 5 | Industrial Supply | — |
| 314 | CALCIUM HYDROXIDE, 99% pure, -200 mesh, (Slaked Lime), Ca(OH)₂ | LOOKUP_NEEDED | $3,239 | 3 | Low Carbon / AEsir Technologies / Heirloom Carbon Technologi | — |
| 315 | RUTHENIUM (IV) OXIDE, ANHYDROUS, 99.0% pure, -100 mesh, (Ruthenium Dioxide), RuO | LOOKUP_NEEDED | $3,234 | 2 | Rogers Corporation | Anhydrous |
| 317 | COPPER (II) OXIDE, 99.9% pure, -200 mesh, black, (Cupric Oxide), CuO | LOOKUP_NEEDED | $3,224 | 10 | Fastenal / PiezoTech, LLC / ENGI-Mat | — |
| 319 | BARIUM CHROMATE, 99% pure, -325 mesh, MIL-B-550A, Grade A, BaCrO₄ | LOOKUP_NEEDED | $3,193 | 1 | Pacific Scientific Energetic | — |
| 322 | ALUMINUM CHLORIDE, ANHYDROUS, 99.98% pure, -100 mesh,  (Aluminum Trichloride), A | LOOKUP_NEEDED | $3,175 | 1 | EnerSys Advanced Systems, Inc | Anhydrous |
| 324 | SODIUM PERCARBONATE, Technical Grade, 84% >100 mesh, Na₂CO₃.1.5H₂O₂ | LOOKUP_NEEDED | $3,108 | 2 | BluePallet | Technical Grade |
| 325 | SODIUM GLUCONATE, FCC, granular, HOCH₂(CH(OH))₄CO₂Na | LOOKUP_NEEDED | $3,102 | 3 | A.W. Chesterton Company | FCC |
| 326 | NIOBIUM (V) OXIDE, 99.8% pure, -325 mesh, (Niobium Pentoxide), Nb₂O₅ | LOOKUP_NEEDED | $3,100 | 5 | NEI Corporation / Pyrotek High Temperature | — |
| 327 | POTASSIUM HYDROXIDE, 50% Solution, 99.5% pure, KOH | LOOKUP_NEEDED | $3,091 | 2 | Verdagy | — |
| 331 | DICHLOROBENZENE-1,2 (Orthodichlorobenzene), C₆H₄Cl₂ | LOOKUP_NEEDED | $3,000 | 5 | Austin Chemical Company, Inc. | — |
| 332 | VANADIUM (V) OXIDE, 99.6% pure, -60 mesh, (Vanadium Pentoxide), V₂O₅ | LOOKUP_NEEDED | $2,997 | 1 | LuxWall, Inc. | — |
| 338 | CALCIUM METAL, GRANULES, 99% pure, -8 mm +3.25 mm,  Ca | LOOKUP_NEEDED | $2,892 | 4 | Scientific Sales, Inc. / Aldrich Chemical Co. LLC | — |
| 339 | SODIUM HYDROXIDE, Reagent Grade, Flake, (Caustic Soda), NaOH | LOOKUP_NEEDED | $2,879 | 8 | Invest Cast Inc / Southern Steam Service / BluePallet | Reagent |
| 341 | SODIUM SELENATE, ANHYDROUS, 99.5% pure, -200 mesh,  Na₂SeO₄ | LOOKUP_NEEDED | $2,817 | 3 | 21st Century HealthCare, Inc. / NFP Holdings LLC / SKINN Cos | Anhydrous |
| 343 | SUPPRESSOR SAUCE, BLEND B, crystalline for HUXWRX | LOOKUP_NEEDED | $2,729 | 2 | HUXWRX | — |
| 345 | SULFAMIC ACID, 99.8% pure, crystal, H₂NSO₃H | LOOKUP_NEEDED | $2,686 | 1 | Koy Concrete | — |
| 346 | SODIUM NITRITE, 99% pure, granular, NaNO₂ | LOOKUP_NEEDED | $2,683 | 2 | DAXX | — |
| 348 | SUPPRESSOR SAUCE, BLEND A, crystalline for HUXWRX | LOOKUP_NEEDED | $2,659 | 2 | HUXWRX | — |
| 349 | SODIUM METASILICATE, ANHYDROUS, 99.9% pure, -20 +48 mesh, beads,  Na₂SiO₃ | LOOKUP_NEEDED | $2,638 | 1 | Alchemy Geopolymer Solutions | Anhydrous |
| 351 | MAGNESIUM HYDROXIDE, 99% pure, -200 mesh,  Mg(OH)₂ | 1309-42-8 | $2,634 | 8 | Superior Technical Ceramics Co / GEMM Technologies, LLC | — |
| 352 | VANADIUM (V) OXIDE, 99% pure, -20 mesh, (Vanadium Pentoxide), V₂O₅ | LOOKUP_NEEDED | $2,629 | 2 | Analytichem Canada Inc. | — |
| 354 | SILVER CHLORIDE, 99.9% pure, -10 mesh,  AgCl | LOOKUP_NEEDED | $2,603 | 4 | MC Miller Co. Inc. | — |
| 355 | POTASSIUM DICHROMATE (VI), 99.9% pure, Reagent, -4 mesh,  K₂Cr₂O₇ | LOOKUP_NEEDED | $2,592 | 5 | Haas Group International / P & O Custom Glass Mirror | Reagent |
| 358 | NICKEL (II) OXIDE, 99.98% pure, -325 mesh, <10 microns average, green, (Nickelou | LOOKUP_NEEDED | $2,549 | 2 | APC International, Ltd. | — |
| 360 | General Research and Development Code | LOOKUP_NEEDED | $2,500 | 1 | MakrMed | — |
| 361 | ZINC PHOSPHATE, DIHYDRATE, 99% pure, -325 mesh,  Zn₃(PO₄)₂.2H₂O | 7779-90-0 | $2,465 | 7 | Mo-Sci Corporation / Hoeganaes Corporation / Trans Gulf Indu | — |
| 362 | METALS SOLUTION, for Perma-Fix Environmental (03.21.23) | LOOKUP_NEEDED | $2,465 | 1 | Perma-Fix of Florida, Inc | — |
| 365 | LITHIUM ACETATE, DIHYDRATE, 99% pure, -10 mesh ,(Acetic Acid, Lithium Salt), LiO | LOOKUP_NEEDED | $2,450 | 2 | MP Biomedicals LLC | — |
| 368 | CALCIUM OXIDE, 99.95% pure, -20 mesh,  CaO | LOOKUP_NEEDED | $2,390 | 3 | Heirloom Carbon Technologies | — |
| 369 | ZINC METAL, POWDER, 99.9% pure, < 5 microns average, (Zinc Dust),  Zn | LOOKUP_NEEDED | $2,379 | 3 | Vomaris Wound Care, Inc. / Hyland's Manufacturing Inc. | — |
| 371 | MERCURY METAL, LIQUID, ACS Reagent, triple distilled, Hg | LOOKUP_NEEDED | $2,354 | 2 | Perma-Fix of Florida, Inc / B3 Systems, Inc. | ACS Reagent / Reagent |
| 373 | COBALT (II) SULFATE, HEPTAHYDRATE, Reagent, crystal, for Captek Softgel, (Cobalt | LOOKUP_NEEDED | $2,340 | 3 | Captek Softgel Int'l | Reagent |
| 375 | COPPER (II) CHLORIDE, DIHYDRATE, 99% pure, crystal, (Cupric Chloride, Dihydrate) | LOOKUP_NEEDED | $2,290 | 4 | Luxfer Magtech Inc. / Skin Biology Inc. | — |
| 376 | BERYLLIUM NITRATE, TRIHYDRATE, 48.4% SOLUTION, 99.9% pure, 2.3% Be, Be(NO₃)₂.3H₂ | LOOKUP_NEEDED | $2,283 | 1 | De Bruyn Spectroscopic | — |
| 377 | HYDROFLUORIC ACID, 50% w/w solution, liquid | LOOKUP_NEEDED | $2,280 | 4 | Maruichi Stainless Tube Texas | — |
| 378 | MANGANESE (II) CARBONATE, Rogers Corporation Spec. No. 501-SCM-PCH24-103, Rev. 5 | LOOKUP_NEEDED | $2,275 | 3 | Rogers Corporation | — |
| 380 | STRONTIUM PEROXIDE, MIL-S-612A, Grade B, CBC Spec. E-035, Grade B, (Strontium Di | LOOKUP_NEEDED | $2,191 | 1 | 0012871 | — |
| 382 | BORON NITRIDE, 99.9% pure, < 10 microns average, BN | LOOKUP_NEEDED | $2,159 | 2 | Ergéa UK and Ireland Limited / SpaceX | — |
| 383 | CESIUM BROMIDE, 99.999% pure, beads, -10 mesh, CsBr | LOOKUP_NEEDED | $2,156 | 2 | ETH Zürich | — |
| 385 | SODIUM HYDROXIDE, ACS Reagent, pellets, (Caustic Soda), NaOH | LOOKUP_NEEDED | $2,127 | 5 | Friendship Oxygen Limited / Glanbia Nutritionals (NA), Inc / | ACS Reagent / Reagent |
| 388 | MAGNESIUM ACETATE, TETRAHYDRATE, 99% pure, -10 mesh,  Mg(OOCCH₃)₂.4H₂O | LOOKUP_NEEDED | $2,101 | 1 | Ametek, Specialty Metal | — |
| 392 | COPPER (II) CHLORIDE, DIHYDRATE, ACS Reagent, granular, (Cupric Chloride, Dihydr | LOOKUP_NEEDED | $2,052 | 2 | RWM Technologies / ES Laboratory, LLC | ACS Reagent / Reagent |
| 395 | ARSENIC (V) OXIDE, HYDRATE, 99.5% pure, -40 mesh,(Orthoarsenic Acid; Arsenic Pen | LOOKUP_NEEDED | $2,016 | 4 | Analytichem Canada Inc. / ESS | — |
| 399 | ZIRCONIUM METAL, POWDER, 97% pure, >99% -200 mesh, APS 2.5 +/- 1.0 mu, (Conformi | LOOKUP_NEEDED | $1,967 | 1 | Winn-Star Inc. | — |
| 400 | ZINC METAL, COARSE POWDER, 99.9% pure, ACS Reagent, -20 mesh, Zn | LOOKUP_NEEDED | $1,842 | 2 | Perma-Fix of Florida, Inc | ACS Reagent / Reagent |
| 402 | MERCURY (II) ACETATE, ACS Reagent, powder, (Mercuric Acetate), Hg(OOCCH₃)₂ | LOOKUP_NEEDED | $1,833 | 3 | ESS | ACS Reagent / Reagent |
| 403 | 90215 | LOOKUP_NEEDED | $1,808 | 2 | CJ Chemicals | — |
| 405 | TITANIUM (IV) OXIDE, RUTILE, 92% pure, -325 mesh,(Titanium Dioxide), TiO₂ | LOOKUP_NEEDED | $1,767 | 3 | Babcock & Wilcox Company / SpaceX | — |
| 406 | MAGNESIUM SALICYLATE, TETRAHYDRATE, USP, -20 + 80 mesh, (Magnesium Disalicylate) | LOOKUP_NEEDED | $1,749 | 1 | Professional Botanicals | USP |
| 407 | SODIUM METAPERIODATE, 99.9% pure, ACS Reagent, -100 mesh, (Sodium Periodate), Na | LOOKUP_NEEDED | $1,724 | 1 | Aqueous Solutions Global LLC | ACS Reagent / Reagent |
| 410 | ALUMINUM OXIDE, 99.5% pure, -100 +325 mesh, (Alumina), Al₂O₃ | 1344-28-1 | $1,699 | 3 | QC Electronics, Inc. / Corning Incorporated | — |
| 414 | AMMONIUM NITRATE, Reagent Grade, crystal, NH{4}NO{3} | LOOKUP_NEEDED | $1,657 | 3 | RSI Holdings Group, LLC / 0015002 | Reagent |
| 418 | CESIUM NITRATE, 99.995% pure, -6 mesh, CsNO₃ | LOOKUP_NEEDED | $1,560 | 2 | Testbourne Ltd | — |
| 419 | LITHIUM HYDROXIDE, ANHYDROUS, 99.9% pure, -10 mesh, (Lithium Hydrate), LiOH | LOOKUP_NEEDED | $1,556 | 1 | Bepex International LLC | Anhydrous |
| 423 | IRON (II) CHLORIDE, TETRAHYDRATE, Reagent, crystalline, (Ferrous Chloride, Tetra | LOOKUP_NEEDED | $1,494 | 7 | Reagents Holdings LLC / Chemsavers | Reagent |
| 424 | SURROGATE WASTE, PFOOS Simulant for Nuvision Engineering, solution path | LOOKUP_NEEDED | $1,492 | 3 | NuVision Engineering, Inc. | — |
| 425 | POTASSIUM CARBONATE, ANHYDROUS, 99.999% pure, -20mesh,  K₂CO₃ | LOOKUP_NEEDED | $1,484 | 1 | De Bruyn Spectroscopic | Anhydrous |
| 427 | VANADIUM OXYSULFATE, HYDRATE, Innophos Spec RV00SFP034OK, (Vanadyl Sulfate, Hydr | LOOKUP_NEEDED | $1,459 | 1 | Innophos, LLC | — |
| 428 | VANADIUM OXYSULFATE, HYDRATE, USP, V 19.5 - 23.0%, for Natural Alternatives Int' | LOOKUP_NEEDED | $1,456 | 1 | Natural Alternatives Int'l | USP |
| 429 | AMMONIUM CARBONATE, ACS Reagent, powder,  (NH₄)₂CO₃ (approx.) | LOOKUP_NEEDED | $1,439 | 5 | PT. Aik Moh Chemical Indonesia / Mallard Creek Polymers / BA | ACS Reagent / Reagent |
| 430 | POTASSIUM CARBONATE, 99% pure, powder, Special for Amplex - Rev. 3, K₂CO₃ | LOOKUP_NEEDED | $1,428 | 1 | Amplex Chemical Products Ltd. | — |
| 432 | SILVER SULFATE, 99.9% pure, ACS Reagent, -6 mesh, Ag₂SO₄ | LOOKUP_NEEDED | $1,412 | 2 | General Nano, LLC | ACS Reagent / Reagent |
| 433 | CALCIUM OXIDE, 99.9% pure, -400 mesh, CaO | LOOKUP_NEEDED | $1,401 | 2 | Heirloom Carbon Technologies | — |
| 434 | SODIUM METAVANADATE, Innophos Spec RNA0MVP239OK, (Sodium Vanadium Oxide), NaVO₃ | LOOKUP_NEEDED | $1,395 | 1 | Innophos, LLC | — |
| 435 | CALCIUM OXIDE, 98% pure, < 10 micron average, CaO | LOOKUP_NEEDED | $1,384 | 1 | Vibrantz Colores Y Esmaltes | — |
| 436 | ALUMINUM CHLORIDE, ANHYDROUS, 99.99% pure, -4/+14 mesh, (Aluminum Trichloride),  | LOOKUP_NEEDED | $1,372 | 1 | Engineered Power | Anhydrous |
| 440 | MANGANESE (II) SULFATE, MONOHYDRATE, 99.9% pure, -8 mesh, MnSO₄.H₂O | LOOKUP_NEEDED | $1,332 | 1 | 0014234 | — |
| 441 | MAGNESIUM OXIDE, 99.5% pure, ACS Reagent, -325 mesh, MgO | LOOKUP_NEEDED | $1,323 | 4 | Shanghai Hengbang Int'l Trade / Spectrum Chemical Mfg. Corp  | ACS Reagent / Reagent |
| 443 | IRON (III) OXIDE, ANHYDROUS, 95% pure, -200 mesh, (Ferric Oxide, Anhydrous), Fe₂ | LOOKUP_NEEDED | $1,312 | 2 | Babcock & Wilcox Company | Anhydrous |
| 444 | ZINC OXIDE, USP, -200 mesh, ZnO | LOOKUP_NEEDED | $1,306 | 2 | Fraser Laboratories | USP |
| 445 | CHALK MIXTURE, Developmental for Championship Billiard | LOOKUP_NEEDED | $1,290 | 3 | Championship, LLC | — |
| 446 | AMMONIUM THIOCYANATE, ACS Reagent, crystal, (Ammonium Sulfocyanide), NH₄SCN | LOOKUP_NEEDED | $1,282 | 5 | Calvary Industries, Inc. | ACS Reagent / Reagent |
| 447 | NIOBIUM (V) FLUORIDE, 98% pure, -100 mesh, (Niobium Pentafluoride), NbF₅ | LOOKUP_NEEDED | $1,270 | 1 | The Chemical  Co., Ltd | — |
| 448 | ZIRCONIUM OXIDE, 98.5% pure, -30 +60 mesh, (Zirconium Dioxide, Zirconia), ZrO₂ | LOOKUP_NEEDED | $1,268 | 3 | NeoGraf Solutions, LLC / Catholic University of America | — |
| 449 | NICKEL (II) CARBONATE, 99.9% pure, -100 mesh, (Nickelous Carbonate), NiCO₃ | LOOKUP_NEEDED | $1,242 | 3 | Hot Switch / A & C American Chemicals Ltd. | — |
| 450 | 11468 | LOOKUP_NEEDED | $1,213 | 2 | 0014241 | — |
| 451 | IRON (II,III) OXIDE, 99.5% pure, -325 mesh, <3 microns average, (Ferrosoferric O | LOOKUP_NEEDED | $1,207 | 2 | Hitemco / Southwest Research Institute | — |
| 453 | SODIUM PHOSPHATE TRIBASIC, DODECAHYDRATE, Chemically Pure, crystal, (Trisodium P | LOOKUP_NEEDED | $1,156 | 3 | Symcon, Inc. / Symcon, Inc | — |
| 455 | MERCURY (II) SULFATE, ACS Reagent, crystalline, (Mercuric Sulfate), HgSO₄ | LOOKUP_NEEDED | $1,146 | 1 | SCP Science | ACS Reagent / Reagent |
| 457 | CIP CONCENTRATED ANTI-FOAM, 10% Solution, C₆H₁₆O₂ | LOOKUP_NEEDED | $1,134 | 2 | Crazy Bottling Company, LLC. | — |
| 459 | CALCIUM GLUCONATE, MONOHYDRATE, U.S.P./N.F., powder, (Gluconic Acid, Calcium Sal | LOOKUP_NEEDED | $1,123 | 2 | 0014229 | — |
| 467 | COPPER (II) SULFATE, PENTAHYDRATE, ACS Reagent, crystal, (Cupric Sulfate, Pentah | LOOKUP_NEEDED | $1,050 | 1 | Fastenal | ACS Reagent / Reagent |
| 468 | LEAD (IV) OXIDE, ACS Reagent, -80 mesh, (Lead Peroxide, Lead Dioxide), PbO₂ | LOOKUP_NEEDED | $1,050 | 3 | Celanese Ltd | ACS Reagent / Reagent |
| 469 | ZINC SULFIDE, 99.99% pure, -100 mesh, phosphorescent grade, green,  ZnS | LOOKUP_NEEDED | $1,030 | 3 | Flinn Scientific Inc. | — |
| 470 | MOLYBDENUM (VI) OXIDE, 99.95% pure, -325 mesh, (Molybdenum Trioxide; Molybdic Ac | LOOKUP_NEEDED | $1,021 | 2 | SCI Engineered Materials, Inc. / General Opto Solutions, LLC | — |
| 472 | SODIUM TETRABORATE, ANHYDROUS, 99.5% pure, -12 mesh, (Borax, Anhydrous), Na₂B₄O₇ | LOOKUP_NEEDED | $1,015 | 2 | Friendship Oxygen Limited / Strem Chemicals, Inc. | Anhydrous |
| 474 | LEAD (II) CARBONATE, BASIC, ACS Reagent, powder, (White Lead, Dibasic Lead Carbo | LOOKUP_NEEDED | $1,003 | 3 | Haas Group International LLC / Thermo Fisher Scientific | ACS Reagent / Reagent |
| 477 | POTASSIUM HYDROXIDE, 99.5% pure, flake, KOH | LOOKUP_NEEDED | $985 | 3 | GenCell Inc / Alchemy Geopolymer Solutions / Catholic Univer | — |
| 478 | LITHIUM CARBONATE, 99.998% pure, -40 mesh, (Candamide, hypnorex, eskalith, lithi | LOOKUP_NEEDED | $981 | 1 | De Bruyn Spectroscopic | — |
| 479 | LITHIUM MOLYBDATE, 99.9% pure, -100 mesh, (Lithium Molybdenum Oxide), Li₂MoO₄ | LOOKUP_NEEDED | $974 | 1 | General Opto Solutions, LLC | — |
| 480 | BARIUM (II) NITRATE, 99% pure, crystal, Ba(NO₃)₂ | 10022-31-8 | $971 | 4 | IRB, Inc. / Cascade Columbia Distribution | — |
| 481 | ZIRCONIUM METAL, POWDER, 99.8% pure, -50 mesh, Zr | LOOKUP_NEEDED | $971 | 2 | 0014216 / Universidad Tecnica Federico | — |
| 482 | CALCIUM CARBONATE, 99.98% pure, -325 mesh,  CaCO₃ | LOOKUP_NEEDED | $971 | 2 | De Bruyn Spectroscopic / Ben-Gurion University | — |
| 484 | CITRIC ACID, ANHYDROUS, FCC Grade, crystalline powder, (Special for Baja Bobs),  | LOOKUP_NEEDED | $943 | 5 | Baja Bob | Anhydrous / FCC |
| 485 | ZIRCONIUM SILICATE, 99% pure, 325 mesh, ZrSiO₄ | LOOKUP_NEEDED | $942 | 1 | Bekeson Glass LLC | — |
| 486 | CESIUM ACETATE, 99% pure, 25 mm and smaller, CsOOCCH₃ | LOOKUP_NEEDED | $925 | 1 | Catalytic Combustion Corp | — |
| 488 | COBALT (II) ACETATE, TETRAHYDRATE, Purified, crystal,  Co(OOCCH₃)₂.4H₂O | LOOKUP_NEEDED | $921 | 2 | Vapor Point, LLC | — |
| 491 | STRONTIUM OXALATE, anhydrous, Mil-S-12210A Grade A, (SrC₂O₄) | LOOKUP_NEEDED | $912 | 1 | METSS Corporation | Anhydrous |
| 492 | NEODYMIUM (III) TITANATE, 99% pure, <5 microns average, (Neodymium Titanium Oxid | LOOKUP_NEEDED | $908 | 1 | TCI America | — |
| 493 | COBALT METAL, PIECES, 99.5% pure, random pieces, Co | LOOKUP_NEEDED | $906 | 1 | Universidad Tecnica Federico | — |
| 495 | MONOCHLOROBENZENE, ACS Reagent, liquid, (Chlorobenzene, Phenyl Chloride), C₆H₅Cl | LOOKUP_NEEDED | $904 | 1 | Reagents Holdings LLC | ACS Reagent / Reagent |
| 496 | BARIUM CARBONATE/ CALCIUM CARBONATE/ ALUMINIUM (III) OXIDE Dry Powder Blend, 79. | LOOKUP_NEEDED | $899 | 1 | Spectra-Mat Inc | — |
| 497 | SODIUM BICARBONATE, ACS Reagent, powder, (Sodium Hydrogen Carbonate, Carbonic Ac | LOOKUP_NEEDED | $894 | 1 | Reagents Holdings LLC | ACS Reagent / Reagent |
| 498 | 11679 | LOOKUP_NEEDED | $893 | 1 | 0014208 | — |
| 499 | POTASSIUM NITRATE, 99% pure, crystal, KNO₃ | LOOKUP_NEEDED | $886 | 1 | Bowers Distillery, Inc. | — |
| 502 | STRONTIUM MOLYBDATE, 99.9% pure, -200 mesh, (Strontium Molybdenum Oxide) SrMoO₄ | LOOKUP_NEEDED | $875 | 1 | Orica Sweden AB | — |
| 503 | LANTHANUM OXIDE, 99.9% pure, -200 mesh, (Lanthanum Sesquioxide), La₂O₃ | LOOKUP_NEEDED | $874 | 3 | Johns Manville / ENGI-Mat | — |
| 504 | MAGNESIUM OXIDE, 99.99% pure, -325 mesh, MgO | LOOKUP_NEEDED | $871 | 1 | Tethon 3D - Technology Assessment & Transfer, Inc. | — |
| 506 | MIXED ORGANICS SOLUTION, for Perma-Fix Environmental (03.21.23) | LOOKUP_NEEDED | $859 | 1 | Perma-Fix of Florida, Inc | — |
| 511 | 11684 | LOOKUP_NEEDED | $829 | 1 | Government Scientific | — |
| 513 | COPPER (II) CHLORIDE, ANHYDROUS, 99% pure, -20 mesh, (Cupric Chloride), CuCl₂ | LOOKUP_NEEDED | $815 | 1 | CustomPAK, Inc. | Anhydrous |
| 514 | COBALT METAL, POWDER, 99.9% pure, -100 mesh,  Co | LOOKUP_NEEDED | $814 | 3 | Universidad Tecnica Federico / Materion Advanced Materials | — |
| 517 | IRON (III) OXIDE, HYDRATE, 99% pure, -325 mesh, (Ferric Oxide, Hydrate), Fe₂O₃.x | LOOKUP_NEEDED | $772 | 1 | Leidos Inc. | — |
| 518 | BORON CARBIDE, 99.5% pure, <5 microns average, (Carbon Tetraboride), B₄C | 12069-32-8 | $770 | 1 | Leidos | — |
| 521 | CHROMIUM (III) NITRATE, NONAHYDRATE, 99.5% pure, -6 mesh,  Cr(NO₃)₃.9H₂O | LOOKUP_NEEDED | $757 | 1 | De Bruyn Spectroscopic | — |
| 523 | PHOSPHOMOLYBDIC ACID, HYDRATE, ACS Reagent, crystal, (Molybdophosphoric Acid, Hy | LOOKUP_NEEDED | $744 | 2 | UT Southwestern | ACS Reagent / Reagent |
| 525 | POTASSIUM ACETATE, ACS Reagent, crystalline,  KOOCCH₃ | LOOKUP_NEEDED | $732 | 2 | Noya | ACS Reagent / Reagent |
| 527 | LANTHANUM HYDROXIDE, 99.9% pure, -30 mesh,  La(OH)₃ | LOOKUP_NEEDED | $714 | 1 | NEI Corporation | — |
| 528 | 11563 | LOOKUP_NEEDED | $695 | 1 | Rapid Electroplating | — |
| 530 | ANTIMONY POTASSIUM TARTRATE, HEMIHYDRATE, 99% pure, powder, (Tartar Emetec, Pota | 28300-74-5 | $690 | 2 | KJC Nutra | — |
| 531 | YTTRIUM OXIDE, 99.99% pure, < 2 microns average, (Yttria), Y₂O₃ | LOOKUP_NEEDED | $679 | 2 | SCP Science / Materion Advanced Materials | — |
| 534 | MANGANESE (II) CHLORIDE, ANHYDROUS, 99% pure, -6 mesh, flake, (Manganese Dichlor | LOOKUP_NEEDED | $666 | 1 | Natural Ag Solutions | Anhydrous |
| 535 | BARIUM CARBONATE/ CALCIUM CARBONATE/ ALUMINIUM (III) OXIDE Dry Powder Blend, 79. | LOOKUP_NEEDED | $660 | 1 | Spectra-Mat Inc | — |
| 537 | AMMONIUM CITRATE DIBASIC, ACS Reagent, crystalline, (Citric Acid, Diammonium Sal | LOOKUP_NEEDED | $648 | 2 | LEGOR Extraordinary Matter / Rapid Electroplating | ACS Reagent / Reagent |
| 541 | TITANIUM METAL, POWDER, 99.5% pure, -325 mesh, Ti | LOOKUP_NEEDED | $629 | 3 | Universidad Tecnica Federico | — |
| 544 | POTASSIUM CHROMATE (VI), Vista Supply & Services, Spec No. O-CH-0001, Rev. 7, (C | LOOKUP_NEEDED | $615 | 1 | Vista Supply and Services, LLC | — |
| 547 | BARIUM CARBONATE/ CALCIUM CARBONATE/ ALUMINIUM (III) OXIDE/ SCANDIUM (III) OXIDE | LOOKUP_NEEDED | $601 | 1 | Spectra-Mat Inc | — |
| 551 | Iron (III) Oxide, A-A-59280 Type 1 Class II, (Iron Oxide Ferric Red Dry Type I S | LOOKUP_NEEDED | $574 | 3 | Nammo Perry Inc | — |
| 552 | IRON-CHROMIUM ALLOY, 99% pure, -200 mesh, (Ferrochrome), FeCr | LOOKUP_NEEDED | $573 | 1 | The Ohio State University | — |
| 554 | SODIUM SULFATE, ANHYDROUS, ACS Reagent, -40 mesh, Na₂SO₄ | LOOKUP_NEEDED | $569 | 1 | Nu-Check-Prep | ACS Reagent / Anhydrous / Reagent |
| 557 | CALCIUM CHLORIDE, DIHYDRATE, ACS Reagent, granular, Special for Barium & Chemica | LOOKUP_NEEDED | $549 | 1 | Barium & Chemicals, Inc. | ACS Reagent / Reagent |
| 558 | L- MALIC ACID, FCC Grade, crystalline powder, (Special for Baja Bobs), C₄H₆O₅ | LOOKUP_NEEDED | $546 | 5 | Baja Bob | FCC |
| 562 | IRON (III) CHLORIDE, HEXAHYDRATE, ACS Reagent, lump, (Ferric Chloride, Hexahydra | LOOKUP_NEEDED | $528 | 1 | LabChem Inc. | ACS Reagent / Reagent |
| 566 | NICKEL METAL, POWDER, 99.9% pure, -100 +325 mesh, Ni | LOOKUP_NEEDED | $515 | 2 | e2v Tecnologies | — |
| 568 | CERIUM (IV) OXIDE, 99.9% pure, -325 mesh, (Ceric Oxide), CeO₂ | LOOKUP_NEEDED | $509 | 2 | TRI/Austin, Inc. / Ben-Gurion University | — |
| 573 | Chromium (III) Potassium Sulfate, Dodecahydrate, Technical Grade, crystal, CrK(S | LOOKUP_NEEDED | $492 | 4 | Group O | Technical Grade |
| 576 | TITANIUM (IV) OXIDE, RUTILE, 99.9% pure, -325 mesh, (Titanium Dioxide), TiO₂ | LOOKUP_NEEDED | $488 | 1 | QorTek | — |
| 577 | STRONTIUM PEROXIDE, MIL-S-612A, Grade B | LOOKUP_NEEDED | $488 | 2 | METSS Corporation | — |
| 580 | BARIUM CARBONATE/ CALCIUM CARBONATE/ ALUMINIUM (III) OXIDE Dry Powder Blend, 74. | LOOKUP_NEEDED | $458 | 1 | Spectra-Mat Inc | — |
| 581 | ALUMINUM OXIDE, 99.99% pure, 1-5 mm pieces, sapphire, (Alumina), Al₂O₃ | LOOKUP_NEEDED | $455 | 2 | LANDAUER | — |
| 583 | CADMIUM METAL, SHOT, 99.999% pure, 2-4 mm,  Cd | LOOKUP_NEEDED | $434 | 2 | Analytichem Canada Inc. | — |
| 584 | IRON METAL POWDER, Atomized, 99% pure, -100 mesh Fe | LOOKUP_NEEDED | $433 | 1 | Ambri | — |
| 586 | SODIUM METASILICATE, PENTAHYDRATE, 99.9% pure, -20 +48 mesh, beads, Na₂SiO₃.5H₂O | LOOKUP_NEEDED | $430 | 1 | Alchemy Geopolymer Solutions | — |
| 588 | SODIUM NITRATE, 99.5% pure, -8 mesh,  NaNO₃ | LOOKUP_NEEDED | $424 | 2 | BioZyme, Inc. | — |
| 589 | 11282 | LOOKUP_NEEDED | $421 | 1 | Aero Clean Technologies | — |
| 590 | VANADIUM (III) OXIDE, 99.9% pure, -200 mesh, (Vanadium Trioxide, Vanadium Sesqui | LOOKUP_NEEDED | $407 | 2 | Technion-Israel Inst. of Tech. | — |
| 595 | BARIUM PEROXIDE, 99% pure (90% Assay), -80 mesh, (Barium Dioxide), BaO₂ | LOOKUP_NEEDED | $401 | 2 | NC State University | — |
| 596 | BARIUM CARBONATE/ CALCIUM CARBONATE/ ALUMINIUM (III) OXIDE/ SCANDIUM (III) OXIDE | LOOKUP_NEEDED | $398 | 1 | Spectra-Mat Inc | — |
| 597 | ZINC STEARATE, USP, -325 mesh, (Stearic Acid, Zinc Salt), Zn(C₁₈H₃₅O₂)₂ | LOOKUP_NEEDED | $398 | 3 | Retractable Technologies, Inc. | USP |
| 604 | SODIUM HYDROXIDE, 25% SOLUTION, Reagent, (Caustic  Soda), NaOH | LOOKUP_NEEDED | $365 | 4 | PGM of Texas LLC | Reagent |
| 605 | POTASSIUM PERCHLORATE, per METSS Corp, MIL-P-217A, Grade B, KClO₄ | LOOKUP_NEEDED | $356 | 1 | METSS Corporation | — |
| 606 | POTASSIUM CHLORATE, per METSS Corp, MIL-DTL-150E, Grade A, KClO₃ | LOOKUP_NEEDED | $355 | 1 | METSS Corporation | MIL-Spec |
| 607 | POTASSIUM SULFATE, per METSS Corp, MIL-P-193B, (Sulfuric Acid, Dipotassium Salt) | LOOKUP_NEEDED | $354 | 1 | METSS Corporation | — |
| 609 | BISMUTH SUBNITRATE, Reagent, USP, powder, (Bismuth Hydroxide Nitrate Oxide), Bi₅ | LOOKUP_NEEDED | $349 | 1 | PCCA | Reagent / USP |
| 610 | ZIRCONIUM METAL, POWDER, 99.8% pure, +50 mesh, Zr | LOOKUP_NEEDED | $343 | 1 | Universidad Tecnica Federico | — |
| 611 | IRON (III) NITRATE, NONAHYDRATE, ACS Reagent, crystal, (Ferric Nitrate, Nonahydr | LOOKUP_NEEDED | $338 | 3 | Reagents Holdings LLC / Chasm Advanced Materials, Inc | ACS Reagent / Reagent |
| 612 | CHROMIUM (III) CHLORIDE, HEXAHYDRATE, Reagent, crystal, (Chromic Chloride, Hexah | LOOKUP_NEEDED | $326 | 1 | SCP Science | Reagent |
| 614 | Magnesium Oxide, 98% Pure, -100 Mesh, Special for MakrMed | LOOKUP_NEEDED | $303 | 1 | MakrMed | — |
| 617 | HYDROXYLAMINE HYDROCHLORIDE, ACS Reagent, crystalline, (Oxammonium Hydrochloride | LOOKUP_NEEDED | $284 | 1 | Analytichem Canada Inc. | ACS Reagent / Reagent |
| 621 | CALCIUM PHOSPHATE, DIBASIC, ANHYDROUS, FCC, powder, (Dicalcium Phosphate), CaHPO | LOOKUP_NEEDED | $280 | 1 | Coastal Contract Packaging, Inc. | Anhydrous / FCC |
| 623 | YTTERBIUM OXIDE, 99.9% pure, -325 mesh,  Yb₂O₃ | LOOKUP_NEEDED | $269 | 1 | Ben-Gurion University | — |
| 626 | SODIUM CARBONATE, MONOHYDRATE, ACS Reagent, crystal,  Na₂CO₃.H₂O | LOOKUP_NEEDED | $252 | 1 | Friendship Oxygen Limited | ACS Reagent / Reagent |
| 627 | COPPER METAL, POWDER, 99.2% pure, -325 mesh, water atomized, Cu | LOOKUP_NEEDED | $250 | 1 | Parker Hannifin | — |
| 628 | ANTIMONY (III) OXIDE, 99.9% pure, powder (Antimony Trioxide), Sb₂O₃ | LOOKUP_NEEDED | $250 | 1 | Nan Ya Plastics | — |
| 629 | CALCIUM NITRATE, TETRAHYDRATE, 65% SOLUTION, Reagent,  Ca(NO₃)₂.4H₂O | LOOKUP_NEEDED | $250 | 1 | BioAg | Reagent |
| 630 | PHOSPHATE BUFFER, solution, for StatLab | LOOKUP_NEEDED | $250 | 1 | StatLab | — |
| 631 | ZINC CHLORIDE, USP, 62.5% solution, ZnCl₂ | LOOKUP_NEEDED | $248 | 3 | Tetra Technologies | USP |
| 632 | CESIUM NITRATE, 99.99% pure, -6 mesh, CsNO₃ | LOOKUP_NEEDED | $245 | 1 | Testbourne Ltd | — |
| 633 | COPPER METAL, POWDER, 99.9% pure, -325 mesh, Cu | LOOKUP_NEEDED | $244 | 1 | Lone Star Grease & Lubricants LLC | — |
| 634 | PHOSPHORIC ACID, 85%, ACS Reagent, liquid, (Orthophosphoric Acid; Phosphoric (V) | LOOKUP_NEEDED | $240 | 2 | Aggressive Hyraulics / 0014277 | ACS Reagent / Reagent |
| 635 | COPPER METAL, POWDER, 99.9% pure, -100 mesh,  Cu | LOOKUP_NEEDED | $240 | 1 | Lone Star Grease & Lubricants LLC | — |
| 637 | SODIUM CARBONATE, ANHYDROUS, 99.99% pure, -50 mesh,  Na₂CO₃ | LOOKUP_NEEDED | $234 | 1 | De Bruyn Spectroscopic | Anhydrous |
| 641 | MULLITE, -325 mesh | LOOKUP_NEEDED | $212 | 2 | 0015008 / Championship, LLC | — |
| 645 | POTASSIUM CARBONATE, ANHYDROUS, ACS Reagent, granular,  K₂CO₃ | LOOKUP_NEEDED | $197 | 1 | AMPAC Fine Chemicals | ACS Reagent / Anhydrous / Reagent |
| 650 | TUNGSTEN (VI) OXIDE, 99.9% pure, 1-4 mm, WO3 | LOOKUP_NEEDED | $185 | 1 | USA Analytical Technologies, Inc. | — |
| 653 | SODIUM SULFATE, DECAHYDRATE, ACS Reagent, crystal, Na{2}SO{4}.10H{2}O | LOOKUP_NEEDED | $166 | 2 | GFS Chemicals, Inc. | ACS Reagent / Reagent |
| 654 | ZIRCONIUM OXIDE, 99.9% pure, <  1 micron average, (Zirconium Dioxide, Zirconia), | LOOKUP_NEEDED | $165 | 1 | Government Scientific | — |
| 655 | CERIUM (IV) AMMONIUM SULFATE, DIHYDRATE, 99.5% pure, ACS Reagent, -50 mesh, (Cer | LOOKUP_NEEDED | $164 | 1 | METSS Corporation | ACS Reagent / Reagent |
| 657 | ZINC SULFATE, HEPTAHYDRATE, ACS Reagent, granular,  ZnSO₄.7H₂O | LOOKUP_NEEDED | $160 | 1 | California Academy of Sciences | ACS Reagent / Reagent |
| 658 | MAGNESIUM SULFATE, HEPTAHYDRATE, USP, crystal, MgSO₄.7H₂O | LOOKUP_NEEDED | $160 | 1 | Unique Corals, Inc. | USP |
| 659 | CHROMIUM (III) OXIDE, ANHYDROUS, 99.9% pure, 3-6 mm, Cr2O3 | LOOKUP_NEEDED | $160 | 1 | USA Analytical Technologies, Inc. | Anhydrous |
| 660 | COPPER (II) OXIDE, ACS Reagent, -200 mesh, black,(Cupric Oxide), CuO | LOOKUP_NEEDED | $158 | 1 | PiezoTech, LLC | ACS Reagent / Reagent |
| 665 | LITHIUM ORTHOSILICATE, 99.9% pure, -100 mesh, Li₄SiO₄ | LOOKUP_NEEDED | $150 | 1 | Rensselaer Polytechnic Institute | — |
| 666 | COBALT (II) CARBONATE, ANHYDROUS, 99.5% pure, -325 mesh,  CoCO₃ | LOOKUP_NEEDED | $146 | 1 | SCP Science | Anhydrous |
| 667 | CALCIUM CHLORIDE, DIHYDRATE, USP, flake, CaCl₂.2H₂O | LOOKUP_NEEDED | $140 | 1 | Unique Corals, Inc. | USP |
| 668 | MAGNESIUM CHLORIDE, HEXAHYDRATE, USP, powder, (Magnesium Dichloride, Hexahydrate | LOOKUP_NEEDED | $140 | 1 | Unique Corals, Inc. | USP |
| 669 | MANGANESE (II) SULFATE, MONOHYDRATE, 99.5% pure, -8 mesh, MnSO₄.H₂O | LOOKUP_NEEDED | $138 | 2 | 0014234 / 0014208 | — |
| 670 | ZIRCONIUM OXIDE, stabilized with 8% Yttrium Oxide, (99% pure, -325 mesh), ZrO₂/8 | LOOKUP_NEEDED | $138 | 2 | NC State University | — |
| 671 | CALCIUM RESINATE, MIL-C-20470A, Type II, C₄₀H₅₈CaO₄ | LOOKUP_NEEDED | $137 | 1 | Riverbend Energetics | — |
| 672 | SILICON (IV) OXIDE, FUMED, AMORPHOUS, 99% pure, -325 mesh, (Silicon Dioxide Fume | LOOKUP_NEEDED | $129 | 1 | Tetra Technologies | — |
| 673 | MAGNESIUM OXIDE, 98% pure, -30 mesh, MgO | LOOKUP_NEEDED | $127 | 1 | Surfatas | — |
| 675 | STRONTIUM NITRATE, ACS Reagent, crystal, Sr(NO₃)₂ | LOOKUP_NEEDED | $113 | 1 | METSS Corporation | ACS Reagent / Reagent |
| 678 | POTASSIUM SULFATE, MIL-P-193, Type II, (Sulfuric Acid, Dipotassium Salt), K₂SO₄ | LOOKUP_NEEDED | $108 | 1 | METSS Corporation | MIL-Spec |
| 680 | CALCIUM CARBONATE, ACS Reagent, -100 mesh,  CaCO₃ | LOOKUP_NEEDED | $106 | 1 | Analytichem Canada Inc. | ACS Reagent / Reagent |
| 681 | CALCIUM OXIDE, Technical Grade, powder, CaO | LOOKUP_NEEDED | $100 | 2 | Heirloom Carbon Technologies | Technical Grade |
| 682 | MAGNESIUM CHLORIDE, HEXAHYDRATE, Technical grade, flakes, MgCl₂.6H₂O | LOOKUP_NEEDED | $100 | 1 | 0014211 | Technical Grade |
| 684 | 11280 | LOOKUP_NEEDED | $100 | 1 | Saft America, Inc. | — |
| 685 | SODIUM SULFATE, ANHYDROUS, USP, flake, Na₂SO₄ | LOOKUP_NEEDED | $100 | 1 | Unique Corals, Inc. | Anhydrous / USP |
| 686 | MAGNESIUM CHLORIDE, HEXAHYDRATE, 75% SOLUTION, MgCl₂.6H₂O | LOOKUP_NEEDED | $100 | 1 | Natural Calm | — |
| 688 | STRONTIUM NITRATE, MIL-S-20322B, Grade B, Sr(NO₃)₂ | LOOKUP_NEEDED | $98 | 1 | METSS Corporation | MIL-Spec |
| 690 | COBALT (II) OXIDE, 99.5% pure, <10 microns average, (Cobaltous Oxide, Cobalt Mon | LOOKUP_NEEDED | $96 | 2 | Mo-Sci Corporation | — |
| 691 | LITHOPONE, Zinc Sulfide 30% / Barium Sulfate 70%,-325 mesh,  ZnS/BaSO₄ | LOOKUP_NEEDED | $93 | 1 | 0014235 | — |
| 693 | MAGNESIUM OXIDE,  99.995% pure, -1250 mesh (2.8 mic aps) [Developmental for Hera | LOOKUP_NEEDED | $90 | 1 | Heraeus Precious Metals NA | — |
| 694 | BARIUM SULFATE, Reagent grade, typically 0.7 micron average,  BaSO₄ | LOOKUP_NEEDED | $85 | 1 | Plating International Inc. | Reagent |
| 696 | LITHIUM TITANATE, 99% pure, -50 mesh, (Lithium Titanium Oxide), Li₂TiO₃ | LOOKUP_NEEDED | $82 | 1 | Rensselaer Polytechnic Institute | — |
| 697 | SURROGATE WASTE, AN-104 Envelope A3 Simulant Recipe #64mod for BNI | LOOKUP_NEEDED | $78 | 1 | EigenValue Solutions LLC | — |
| 700 | LANTHANUM OXIDE, 99.99% pure, -325 mesh, (Lanthanum Sesquioxide), La₂O₃ | LOOKUP_NEEDED | $73 | 1 | Ben-Gurion University | — |
| 701 | SODIUM FLUORIDE, 99.5% pure, ACS Reagent, -100 mesh,  NaF | LOOKUP_NEEDED | $73 | 1 | Celanese Ltd | ACS Reagent / Reagent |
| 702 | TUNGSTEN (VI) OXIDE, 99.99% pure, -325 mesh (yellow-green), (Tungsten Trioxide;  | LOOKUP_NEEDED | $68 | 1 | Ben-Gurion University | — |
| 703 | SODIUM PERCHLORATE, ANHYDROUS, 98.5% pure, granular, NaClO₄ | LOOKUP_NEEDED | $66 | 1 | METSS Corporation | Anhydrous |
| 704 | GADOLINIUM OXIDE, 99.9% pure, -325 mesh, Gd₂O₃ | LOOKUP_NEEDED | $55 | 1 | Ben-Gurion University | — |
| 705 | CALCIUM CARBONATE, 99% pure, -325 mesh, CaCO₃ | LOOKUP_NEEDED | $52 | 1 | Spectra-Mat Inc | — |
| 706 | MAGNESIUM NITRATE, HEXAHYDRATE, Soluble grade, flakes, Mg(NO₃)₂.6H₂O | LOOKUP_NEEDED | $51 | 1 | Partanna Global, Inc | — |
| 707 | SODIUM SULFATE, ANHYDROUS, Chemically Pure, powder,  Na₂SO₄ | LOOKUP_NEEDED | $49 | 1 | 0014237 | Anhydrous |
| 709 | 11395 | LOOKUP_NEEDED | $43 | 1 | Tosoh SMD, Inc. | — |
| 710 | POTASSIUM CHLORIDE, 99.9% pure, ACS Reagent, -4 mesh, KCl | LOOKUP_NEEDED | $42 | 1 | Tetra Technologies | ACS Reagent / Reagent |
| 712 | 11712 | LOOKUP_NEEDED | $35 | 1 | Tetra Technologies | — |
| 713 | 11431 | LOOKUP_NEEDED | $34 | 1 | Tosoh SMD, Inc. | — |
| 714 | BORON, ELEMENTAL, CRYSTALLINE, 99% pure, -325 mesh, typ. 10 micron average, B | LOOKUP_NEEDED | $33 | 1 | Epic Advanced Materials | — |
| 715 | THULIUM (III) OXIDE, 99.9% pure, -325 mesh, Tm₂O₃ | LOOKUP_NEEDED | $33 | 1 | Ben-Gurion University | — |
| 716 | LEAD (II) CARBONATE, BASIC, 99% pure, -325 mesh, (White Lead, Dibasic Lead Carbo | LOOKUP_NEEDED | $32 | 1 | 0014257 | — |
| 717 | BORON, ELEMENTAL, CRYSTALLINE, 99.5% pure, -325 mesh, typ. 10 mu avg.,  B | LOOKUP_NEEDED | $30 | 1 | Epic Advanced Materials | — |
| 718 | SULFURIC ACID, ACS Reagent, H₂SO₄ | LOOKUP_NEEDED | $28 | 1 | METSS Corporation | ACS Reagent / Reagent |
| 719 | AMMONIUM IRON (II) SULFATE, HEXAHYDRATE, ACS Reagent, crystal, (Ferrous Ammonium | LOOKUP_NEEDED | $26 | 1 | METSS Corporation | ACS Reagent / Reagent |
| 720 | 11283 | LOOKUP_NEEDED | $25 | 1 | L3Harris Technologies, Inc | — |
| 722 | POTASSIUM FERROCYANIDE, TRIHYDRATE, 99% pure, ACS  Reagent, crystal, (Potassium  | LOOKUP_NEEDED | $21 | 1 | Jacquard Products | ACS Reagent / Reagent |
| 724 | BORON, ELEMENTAL, CRYSTALLINE, >92% B-10 enriched, 99% pure, -325 mesh,  B | LOOKUP_NEEDED | $16 | 1 | Epic Advanced Materials | — |
| 727 | ASCORBIC ACID, FCC Grade, crystalline powder, (Special for Baja Bobs), C₆H₈O₆ | LOOKUP_NEEDED | $6 | 2 | Baja Bob | FCC |
| 728 | MAGNESIUM NITRATE, HEXAHYDRATE, 99% pure, flakes,Mg(NO₃)₂.6H₂O | LOOKUP_NEEDED | $6 | 1 | Chasm Advanced Materials, Inc | — |
| 729 | LEAD NITRATE, MIL-DTL-20549C, Pb(NO₃)₂ | LOOKUP_NEEDED | $4 | 1 | METSS Corporation | — |
| 734 | SILICON CARBIDE, ALPHA, 99.9% pure, <1 micron average, black,  SiC | LOOKUP_NEEDED | $-0 | 1 | 0014260 | — |
| 737 | POTASSIUM NITRATE, MIL-DTL-156D, KNO₃ | LOOKUP_NEEDED | $-1 | 1 | METSS Corporation | — |
| 738 | SODIUM BICARBONATE, 99.5% pure, powder, (Sodium Hydrogen Carbonate; Carbonic Aci | LOOKUP_NEEDED | $-1 | 2 | Enfusia / The Lavish Goat | — |
| 739 | ERBIUM OXIDE, 99.9% pure, -325 mesh,  Er₂O₃ | LOOKUP_NEEDED | $-1 | 1 | Ben-Gurion University | — |
| 741 | Manganese Blue Pigment, R&D | LOOKUP_NEEDED | $-7 | 3 | Rocking M Ventures LLC | — |
| 742 | SODIUM CARBONATE, ANHYDROUS, Technical Grade dense, Na₂CO₃ | LOOKUP_NEEDED | $-12 | 2 | Alchemy Geopolymer Solutions | Anhydrous / Technical Grade |
| 744 | CALCIUM METAL, GRANULES, REDISTILLED, 99.5% pure,3 mm and smaller,  Ca | LOOKUP_NEEDED | $-16 | 1 | 0014244 | — |
| 746 | IRON (II) SULFATE, HEPTAHYDRATE, NSF/ANSI 60, granular, (Ferrous Sulfate, Heptah | LOOKUP_NEEDED | $-23 | 1 | H&E USA Chemicals Corporation | NSF/ANSI 60 |
| 747 | SODIUM STANNATE, TRIHYDRATE, 99.5% pure, crystal,(Sodium Tin (IV) Oxide, Trihydr | LOOKUP_NEEDED | $-26 | 1 | Tri-Chem Industries | — |
| 749 | POLYETHYLENE GLYCOL, 3350, powder,  H(OCH₂CH₂)ₙOH | LOOKUP_NEEDED | $-33 | 1 | Perry Machine and Die INC | — |
| 750 | SODIUM CITRATE, DIHYDRATE, ACS Reagent, granular,(Trisodium Citrate, Dihydrate), | LOOKUP_NEEDED | $-37 | 1 | California Academy of Sciences | ACS Reagent / Reagent |
| 751 | CERIUM (III) CARBONATE, 99.9% pure, powder | LOOKUP_NEEDED | $-46 | 1 | Metals and Additives LLC | — |
| 752 | MAGNESIUM OXIDE, 98% pure, USP, -325 mesh, Special for MakrMed | LOOKUP_NEEDED | $-47 | 4 | MakrMed | USP |
| 754 | ZINC SULFIDE, 98% pure, super fine, typically 0.30 microns,  ZnS | LOOKUP_NEEDED | $-94 | 1 | Scan Pac Mfg. | — |
| 757 | ALUMINUM (III) ACETYLACETONATE, Avery Spec. No. 975-63, Avery Item Number A01873 | LOOKUP_NEEDED | $-222 | 6 | Avery Dennison | — |
| 760 | CERIUM (III) NITRATE, HEXAHYDRATE, 99.9% pure, -6mesh, (Cerous Nitrate, Hexahydr | LOOKUP_NEEDED | $-250 | 1 | Metals and Additives LLC | — |
| 762 | IRON METAL POWDER, 92-95% pure, -20/+50 mesh, Fe | LOOKUP_NEEDED | $-379 | 1 | Ambri | — |
| 764 | IRON (III) SULFATE, HYDRATE, Reagent, crystalline, (Ferric Sulfate, Hydrate), Fe | LOOKUP_NEEDED | $-430 | 1 | MP Biomedicals LLC | Reagent |
| 765 | COPPER METAL, POWDER, 99.5% pure, -325 mesh,  Cu | LOOKUP_NEEDED | $-477 | 2 | Ambri | — |
| 766 | CALCIUM CHLORIDE, ANHYDROUS, 99% pure, fine granular, CaCl₂ | LOOKUP_NEEDED | $-522 | 2 | 0014211 / Ambri | Anhydrous |
| 767 | STRONTIUM CHLORIDE, ANHYDROUS, 99.5% pure, -40 mesh,  SrCl₂ | LOOKUP_NEEDED | $-600 | 1 | Ambri | Anhydrous |
| 768 | MAGNESIUM HYDROXIDE, 91%+ pure, 10 micron average,  Mg(OH)2 | LOOKUP_NEEDED | $-623 | 2 | Environmental Energy Services | — |
| 769 | BARIUM CARBONATE, 99% pure, granular, BaCO₃ | LOOKUP_NEEDED | $-635 | 1 | Hollingsworth & Vose Fiber Company | — |
| 770 | Pail, 6.5 gallon, Life Latch New Gen Screw Top Containers | LOOKUP_NEEDED | $-858 | 20 | Biotron Laboratories, Inc. / Wagstaff Inc. / Thermo Fisher S | — |
| 771 | NICKEL (II) OXIDE, 99% pure, -325 mesh, black, (Nickelous Oxide), NiO | LOOKUP_NEEDED | $-998 | 2 | Babcock & Wilcox Company | — |
| 775 | POTASSIUM CHLORIDE, USP, 98.5% pure, -15 mesh,. KCl | 7447-40-4 | $-1,432 | 48 | Tetra Technologies / Ambri / HACH Company | USP |
| 777 | MAGNESIUM LACTATE, DIHYDRATE, powder, (Mg(C3H5O3)2 · 2H2O | LOOKUP_NEEDED | $-1,658 | 1 | ProTab Laboratories | — |
| 778 | Fiber drum, 20 gallon, Lok-Rim, Item DRFI03893NA20001 | LOOKUP_NEEDED | $-2,157 | 3 | Atlas Putty Products Company / International Battery Metals  | — |
| 783 | CITRIC ACID, ANHYDROUS, FCC Grade, crystalline powder, (2-Hydroxy-1,2,3-propanet | LOOKUP_NEEDED | $-23,586 | 5 | Gessi LLC / Enfusia / The Boyer Corporation | Anhydrous / FCC |
| 784 | SODIUM IODIDE, 99.9% pure, ACS Reagent, -4 mesh, granular,  NaI | LOOKUP_NEEDED | $-34,865 | 3 | Eckerd College / ScintiTech Inc. / Ajay North America, LLC. | ACS Reagent / Reagent |
