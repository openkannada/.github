# Open Kannada

Kannada should be as easy to use on a computer as English.

Free, open-source tools for Kannada, at [openkannada.org](https://openkannada.org).

Years of Kannada documents were typed in old fonts that computers can't search or read aloud, and many everyday tools still handle Kannada badly. We build the missing pieces, test them on real text, and send fixes to the projects people already use.

## Tools

| Tool | What it does | Result |
|---|---|---|
| [kannadi](https://github.com/openkannada/kannadi) | Converts documents in the old Nudi, Baraha, Nudi B-Akshara, Kan-Eng, Akruti and Shree-Lipi fonts to Unicode and back. Rust library, command-line tool for whole folders (TXT, HTML, DOCX, DOC, RTF, PDF) and the [editor](https://openkannada.org/editor/) | 96.9% of 2,210 Nudi and Baraha lines from Karnataka government PDFs convert to the text the page shows |
| [Kannada typing](https://openkannada.org/kannada-typing/) | Type Kannada with English letters; words turn into Kannada as you type. Part of kannadi | 89.19% top-1 on the Dakshina Kannada test set |
| [Neha Sans and Neha Serif](https://github.com/openkannada/noto-kannada-fork) | Kannada fonts built from Google's Noto Sans and Noto Serif Kannada, with shaping fixes and every weight | [Download v1.000](https://github.com/openkannada/noto-kannada-fork/releases/tag/v1.000) |
| [Gari](https://github.com/openkannada/gari-font) | A handwriting-style Kannada font built on Aravinda VK's Navilu, with modern shaping and new letters | [Download v1.300](https://github.com/openkannada/gari-font/releases/tag/v1.300) |
| [font-health-action](https://github.com/openkannada/font-health-action) | Kannada shaping tests for any font repository, as a GitHub Action | |
| [Spell check](https://openkannada.org/spell-check/) | A Kannada Hunspell dictionary for LibreOffice and Firefox that understands word endings | Accepts 88.9% of held-out Kannada Wikipedia words |
| [Dictionary](https://openkannada.org/dictionary/) | English to Kannada, built from Alar, with sound-alike and inflected-form search | 3,798 English word pages |
| [OCR](https://openkannada.org/ocr/) | A Tesseract model fine-tuned for Kannada print, especially old books | 6.0% characters wrong on old printed books, against 8.7% for stock Tesseract |
| [AI benchmark](https://openkannada.org/ai-benchmark/) | What Kannada costs in AI tokenizers, and a Kannada test suite with answer keys | Kannada takes 1.1 to 8.3 times the tokens of the same English text |

Install the command-line tool with `brew install openkannada/tap/kannadi`, or see [kannadi's install options](https://github.com/openkannada/kannadi#install).

Upstream so far: Kannada conjunct and arkavattu checks in [shaperglot](https://github.com/googlefonts/shaperglot/pull/192), the tool Google Fonts uses to test language support.

## How you can help

- **Have an old Nudi, Baraha or Shree-Lipi file that converts wrongly?** Open an issue on kannadi with a short sample. Every fixed case becomes a test.
- **Read Kannada well?** Help check converted text against the original. This is the work that turns our results into verified ones.
- **Design type?** Several open Kannada fonts are missing letters and heavier weights.
- **Write code?** Read [CONTRIBUTING](https://github.com/openkannada/.github/blob/main/CONTRIBUTING.md). Code is MIT OR Apache-2.0, fonts are OFL, and every commit is signed off.

## Who we are

Open Kannada was started by [Prasad Subrahmanya](https://prasad.tech) and [Neha Prasad](https://neha-prasad.com/), its founding members, and is supported by [DataRavel Inc. (dba Luminik)](https://www.luminik.io).

Copyright stays with the authors, and the names belong to the project, not to DataRavel Inc.

Dedicated to Veena and Subramanya.
