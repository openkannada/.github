# Open Kannada

Kannada should be as easy to use on a computer as English.

Free, open-source tools for Kannada, at [openkannada.org](https://openkannada.org).

Years of Kannada documents were typed in old fonts that computers can't search or read aloud, and many everyday tools still handle Kannada badly. We build the missing pieces, test them on real text, and send our fixes to the fonts and programs people already use.

## Tools

| Tool | What it does | Result |
|---|---|---|
| [kannadi](https://github.com/openkannada/kannadi) | Converts documents in the old Nudi, Baraha, Nudi B-Akshara, Kan-Eng, Akruti and Shree-Lipi fonts to Unicode and back: a Rust library, a command-line tool for whole folders (TXT, HTML, DOCX, DOC, RTF, PDF) and an [editor that runs in your browser](https://openkannada.org/editor/) | Checked on more than 1.8 million glyphs from public Karnataka documents, with every glyph it cannot place reported |
| [Kannada typing](https://openkannada.org/kannada-typing/) | Type Kannada with English letters; words turn into Kannada as you type. Part of kannadi | 89.19% top-1 on the Dakshina Kannada test set |
| [Neha Sans and Neha Serif](https://github.com/openkannada/noto-kannada-fork) | Our builds of Google's Noto Sans and Noto Serif Kannada, with shaping fixes and every weight. [Download v1.000](https://github.com/openkannada/noto-kannada-fork/releases/tag/v1.000) | All 2,146 Kannada shaping strings; Shaperglot 100% |
| [Gari](https://github.com/openkannada/gari-font) | A handwriting-style Kannada font built on Aravinda VK's Navilu, with modern shaping and new letters. [Download v1.300](https://github.com/openkannada/gari-font/releases/tag/v1.300) | 2,035 of 2,146 Kannada shaping strings |
| [font-health-action](https://github.com/openkannada/font-health-action) | Kannada shaping tests for any font repository, as a GitHub Action | 2,146 shaping strings and Shaperglot on every commit |
| [Spell check](https://openkannada.org/spell-check/) | A Kannada dictionary for the spell checkers in LibreOffice, Firefox and other programs, which understands word endings | Accepts 88.9% of held-out Kannada Wikipedia words |
| [English to Kannada dictionary](https://openkannada.org/dictionary/) | Look up an English word and get Kannada meanings, with Baraha spellings for typing | 3,798 English word pages |
| [OCR](https://openkannada.org/ocr/) | Reads old printed Kannada books with a Tesseract model fine-tuned for Kannada print | 6.0% characters wrong on old printed books, against 8.7% for stock Tesseract |
| [The Kannada token tax](https://openkannada.org/ai-benchmark/) | What Kannada costs in public AI tokenizers | 1.1 to 8.3 times the tokens of the same English text |

Install the command-line tool with `brew install openkannada/tap/kannadi`, or see [kannadi's install options](https://github.com/openkannada/kannadi#install).

Upstream so far: Kannada conjunct and arkavattu checks in [shaperglot](https://github.com/googlefonts/shaperglot/pull/192), the tool Google Fonts uses to test language support.

## How you can help

- **Have an old Nudi, Baraha or Shree-Lipi file that converts wrongly?** Open an issue on kannadi with a short sample. Every fixed case becomes a test.
- **Read Kannada well?** Help check converted text against the original.
- **Design type?** Several open Kannada fonts are missing letters and heavier weights.
- **Write code?** Read [CONTRIBUTING](https://github.com/openkannada/.github/blob/main/CONTRIBUTING.md). Code is MIT OR Apache-2.0, fonts are OFL, and every commit is signed off.

## Who we are

<a href="https://prasad.tech"><img src="https://raw.githubusercontent.com/openkannada/.github/main/profile/images/prasad.jpg" width="96" height="96" alt="Prasad Subrahmanya"></a>&nbsp;&nbsp;<a href="https://neha-prasad.com/"><img src="https://raw.githubusercontent.com/openkannada/.github/main/profile/images/neha.jpg" width="96" height="96" alt="Neha Prasad"></a>

Open Kannada was started by [Prasad Subrahmanya](https://prasad.tech) and [Neha Prasad](https://neha-prasad.com/), its founding members, and is supported by [DataRavel Inc. (dba Luminik)](https://www.luminik.io).

Contributors keep the copyright to their work and license it under the project's licenses. The Open Kannada and kannadi names and logos are covered by [TRADEMARKS.md](https://github.com/openkannada/.github/blob/main/TRADEMARKS.md).

Dedicated to [Veena and Subramanya](https://openkannada.org/about/#dedication).
