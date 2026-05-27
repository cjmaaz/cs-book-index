# CS Book Index

A reading-order index across 10 core Computer Science textbooks, organised by topic and within each topic ordered by difficulty with practical/lab rows interleaved alongside the matching theory.

**Live site (GitHub Pages):** [https://cjmaaz.github.io/cs-book-index/](https://cjmaaz.github.io/cs-book-index/)

## Books in scope

| Code | Title | Difficulty tier |
| --- | --- | --- |
| MakeElec | Make: Electronics (Charles Platt) - optional, practical | 1 |
| Code | Code: The Hidden Language of Computer Hardware and Software (Petzold, 2nd ed.) | 1 |
| Justice | How Computers Really Work (Matthew Justice) | 1 |
| DDCA | Digital Design and Computer Architecture (Harris) | 2 |
| COD6 | Computer Organization And Design, 6th Edition (Patterson/Hennessy) | 3 |
| ModArch | Modern Computer Architecture | 4 |
| CSAPP | Computer Systems: A Programmer's Perspective, 3rd Edition (Bryant/O'Hallaron) | 4 |
| OSTEP | Operating Systems: Three Easy Pieces (Arpaci-Dusseau) | 2 |
| HLW | How Linux Works (Brian Ward) | 2 |
| LKD | Linux Kernel Development (Robert Love) | 5 |
| Kurose | Computer Networking: A Top-Down Approach (Kurose/Ross) | 2 |

PDFs of the books are **not** included in this repo (copyright). The index points at printed page numbers and PDF reader page numbers so you can jump straight to the relevant pages in your own copies.

## Layout

Inside each of 37 topic sections (Number Systems, Logic Gates, ..., Network Security):

1. **Summary table** - one row per book that contributes, showing the page range and what the book teaches there.
2. **Concept blocks** - the topic is split into individual concepts (e.g. AND gate, OR gate, Flip-flop, IEEE 754). Inside each concept, rows are sorted theory-first then practical-first, by difficulty, so the natural reading path is "learn the theory, then do the matching hands-on experiment".
3. **Index keywords** - back-of-book index keywords are collected behind a per-topic "+ Show N keywords" sub-toggle so they don't drown out the structural reading material.

The HTML supports dark/light mode (follows the OS), live search + filters (book / difficulty / topic / exercises-only), and exports the filtered view to Markdown, CSV or JSON. Topic headers stay sticky to the top of the viewport while scrolling so a topic can be collapsed from any depth.

## Files

- `index.html` - the single-file viewer, opens in any browser
- `cs-books-master-index.md` - same content as printable Markdown
- `cs-books-master-index.json` - machine-readable list of all 17,560 entries
- `cs-books-master-index.canvas.tsx` - Cursor IDE Canvas source (only useful inside Cursor)

## Stats

- 17,560 entries (chapters, sections, subsections, subtopics, back-of-book index keywords)
- 11 books (~13,000 PDF pages of source material)
- 37 topic sections
- ~480 curated concept keywords
