# Polygondwanaland Annotated Database

This repository provides access to an annotated music database built around *Polygondwanaland*, the 2017 album by **King Gizzard & The Lizard Wizard**.

The database brings together audio, symbolic music representations, and musical annotations for all ten tracks of the album. The annotations combine **algorithmic and manual analyses** and are provided in **Dezrann (`.dez`) format**, allowing the results to be visualized and explored through a clear and accessible representation.

The database was developed as part of the research conducted at **IRMA (University of Strasbourg)** and **LIP6 (Sorbonne University)** within the PhD work of **Mathys Daniel**.

## Why *Polygondwanaland*?

*Polygondwanaland* is particularly interesting as a research corpus for several reasons.

### 1. A rich and complex musical corpus

Beyond being a remarkable album from a musical perspective, *Polygondwanaland* makes extensive use of **polymetric structures**. The coexistence and interaction of different metric patterns throughout the album make it a particularly rich corpus for the study of **musical structure, rhythm, meter, and temporal organization**.

This extensive use of polymetry provides an especially interesting challenge for computational music analysis and Music Information Retrieval (MIR), as musical structures cannot always be adequately described through a single, uniform metric framework.

### 2. An openly available album

A second major advantage of *Polygondwanaland* as a research corpus is its **open licensing**. The album was released by King Gizzard & The Lizard Wizard under a **Creative Commons license**, allowing it to be freely shared and reused under the conditions of that license.

This makes the album particularly suitable for the development and dissemination of an open research corpus, while facilitating the reproducibility and accessibility of research results.

The combination of **musical complexity** and **open availability** makes *Polygondwanaland* an especially valuable case study for computational musicology and Music Information Retrieval.

These aspects are discussed in greater detail in:

> **Mathys DANIEL; Paul LASCABETTES; Moreno ANDREATTA; Isabelle BLOCH.**
> *MUSICAL PATTERN DISCOVERY AT REGULAR TIME INTERVALS THROUGH MATHEMATICAL MORPHOLOGY: AN APPLICATION TO POLYMETRIC STRUCTURE ANALYSIS.*
> **Proceedings of the Sound and Music Computing Conference (SMC 2026)**, Zagreb, 2026.
> [HAL: hal-05710365](https://hal.science/hal-05710365)

---

## Contents

Each folder in this repository corresponds to one track from *Polygondwanaland*:

1. `CrumblingCastle`
2. `Polygondwanaland`
3. `CasteInTheAir`
4. `DesertedDunes`
5. `Innercell`
6. `Loyalty`
7. `Horology`
8. `Tetrachromacy`
9. `Searchin`
10. `FourthColor`

The repository contains the following types of files:

* **MP3** — audio files used for reference and analysis
* **MIDI** — symbolic representations of the music
* **MusicXML** — symbolic music notation
* **DEZ** — musical annotations in Dezrann format

---

## Annotations

The main contribution of this repository is the collection of musical annotations stored in **`.dez` files**.

These annotations result from a combination of:

* **algorithmic analyses**, produced using computational music analysis methods;
* **manual analyses**, used to complement, correct, and refine the automatically obtained results.

The annotations are designed to provide structured information about the musical content and organization of the tracks.

The `.dez` files can be opened and explored using **Dezrann**, a platform for the visualization and annotation of symbolic music. Dezrann provides an interactive representation of the annotations, making the results easier to inspect, understand, and reuse.

---

## Audio Files

MP3 versions of the tracks are provided in this repository for convenience and to facilitate access to the database.

FLAC files are **not included in this repository** because of their larger file size and GitHub's storage limitations.

Higher-quality versions of the album, including FLAC and other formats, are available from the official Bandcamp release:

**[King Gizzard & The Lizard Wizard — Polygondwanaland](https://kinggizzard.bandcamp.com/album/polygondwanaland)**

---

## MIDI Files

The MIDI files included in this repository originate from the work of **8-bit Escapades**, who created an 8-bit version of *Polygondwanaland*.

Their work provides a symbolic representation of the album that serves as the basis for the MIDI data used in this database.

The original 8-bit album is available here:

**[8-bit Escapades — Polygondwanaland](https://8-bitescapades.bandcamp.com/album/polygondwanaland)**

---

## MusicXML Files

MusicXML versions of the symbolic data are also provided.

MusicXML is a widely used open format for representing musical notation and symbolic music information. These files can therefore be imported into compatible music notation and analysis software.

---

## Dezrann

The annotation files are provided in **Dezrann (`.dez`) format**.

Dezrann allows symbolic music and musical annotations to be represented in an interactive and accessible way. It is particularly useful for exploring hierarchical and time-based musical information.

The use of Dezrann in this repository makes it possible to move beyond raw annotation files and provide a visual representation of the analytical results.

For more information about Dezrann, please refer to the [Dezrann project](https://www.dezrann.net/).

---

## Research Context

This database was developed as part of research conducted at the **Research Institute of Advanced Mathematics (IRMA), University of Strasbourg** and **Computer Science Laboratory (LIP6), Sorbonne University** in the context of the PhD thesis of **Mathys Daniel**.

The database is intended to support research in areas including:

* Music Information Retrieval (MIR)
* computational musicology
* symbolic music analysis
* music structure analysis
* algorithmic music analysis
* music annotation
* musicological research

The annotations presented here are part of a broader research effort investigating computational approaches to the analysis and representation of musical structure.

---

## Related Publication

The methodology and results associated with this work are presented in a paper published at the **Sound and Music Computing Conference (SMC 2026)** in Zagreb.

The publication discusses the musical characteristics of *Polygondwanaland*, its interest as a research corpus, and the computational approaches used to analyze its musical structures.

**[HAL — hal-05710365](https://hal.science/hal-05710365)**

Please refer to the publication for a detailed description of the methods, analyses, and results underlying this database.

---

## Repository Structure

A simplified representation of the repository structure is:

```text
Polygondwanaland_AnnotatedDatabase/
│
├── CrumblingCastle/
│   ├── *.mp3
│   ├── *.mid
│   ├── *.musicxml
│   └── *.dez
│
├── Polygondwanaland/
│   ├── *.mp3
│   ├── *.mid
│   ├── *.musicxml
│   └── *.dez
│
├── CasteInTheAir/
│   └── ...
│
├── DesertedDunes/
│   └── ...
│
├── Innercell/
│   └── ...
│
├── Loyalty/
│   └── ...
│
├── Horology/
│   └── ...
│
├── Tetrachromacy/
│   └── ...
│
├── Searchin/
│   └── ...
│
├── FourthColor/
│   └── ...
│
├── LICENSE
└── README.md
```

Each track folder contains the available resources associated with that particular piece.

---

## How to Use the Database

The database can be used in several complementary ways.

### Listening

The MP3 files provide a lightweight audio reference for each track.

For higher-quality audio formats, please use the official Bandcamp release:

https://kinggizzard.bandcamp.com/album/polygondwanaland

### Symbolic Analysis

The MIDI and MusicXML files can be imported into compatible music analysis, notation, or sequencing software.

### Annotation Analysis

The `.dez` files contain the core musical annotations produced through the research process.

They can be explored using Dezrann to obtain an interactive representation of the annotated musical structures.

This makes it possible to compare:

**audio → symbolic representation → annotation → visual representation**

and to use the database for further computational or musicological analyses.

---

## Track List

| #  | Track                             | Repository folder  |
| -- | --------------------------------- | ------------------ |
| 1  | Crumbling Castle                  | `CrumblingCastle`  |
| 2  | Polygondwanaland                  | `Polygondwanaland` |
| 3  | The Castle in the Air             | `CasteInTheAir`    |
| 4  | Deserted Dunes Welcome Weary Feet | `DesertedDunes`    |
| 5  | Inner Cell                        | `Innercell`        |
| 6  | Loyalty                           | `Loyalty`          |
| 7  | Horology                          | `Horology`         |
| 8  | Tetrachromacy                     | `Tetrachromacy`    |
| 9  | Searching...                      | `Searchin`         |
| 10 | The Fourth Colour                 | `FourthColor`      |

---

## Citation

If you use this database in academic work, please cite the associated publication:

```bibtex
@inproceedings{daniel2026polygondwanaland,
  author    = {Mathys Daniel, Paul Lascabettes, Moreno Andreatta, Isabelle Bloch},
  title     = {MUSICAL PATTERN DISCOVERY AT REGULAR TIME INTERVALS THROUGH MATHEMATICAL MORPHOLOGY: AN APPLICATION TO POLYMETRIC STRUCTURE ANALYSIS},
  booktitle = {Proceedings of the Sound and Music Computing Conference (SMC)},
  year      = {2026},
  address   = {Zagreb, Croatia},
  url       = {https://hal.science/hal-05710365}
}
```

Please also cite the original sources of the audio and MIDI materials where appropriate.

---

## Acknowledgements

We would like to acknowledge:

* **King Gizzard & The Lizard Wizard**, for the original musical material;
* **8-bit Escapades**, for the 8-bit version of *Polygondwanaland* and the MIDI material derived from this work;
* **IRMA** and **LIP6**, for supporting the research within which this database was developed;
* the **Dezrann** project, for providing a platform for the visualization and exploration of musical annotations.

---

## License

The code and original material authored specifically for this repository are distributed under the terms of the **MIT License**, as indicated by the repository license.

However, the repository also contains or provides links to third-party material, including audio and MIDI files. These materials remain subject to their respective authors' and rights holders' terms.

In particular, the open licensing of *Polygondwanaland* should not be interpreted as meaning that all material in this repository is automatically covered by the MIT License.

Users are responsible for respecting the applicable licenses and rights associated with third-party material.

---

## Contact

For questions, comments, or further information about the database and its annotations, please refer to the repository or contact **Mathys Daniel** (mathys.daniel@ircam.fr).
