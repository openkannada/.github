# Open Kannada

Kannada should be as easy to use on a computer as English.

Free, open-source tools for Kannada, at [openkannada.org](https://openkannada.org).

Years of Kannada documents were typed in old fonts that computers can't search or read aloud, and many everyday tools still handle Kannada badly. We build the missing pieces, test them on real text, and fix things upstream where they belong.

## Projects

- **[kannadi](https://github.com/openkannada/kannadi)**: convert documents typed in the old Nudi, Baraha, Nudi B-Akshara, Kan-Eng, Akruti and Shree-Lipi fonts to Unicode, and back. A Rust library, a command-line tool for whole folders of TXT, HTML, DOCX and PDF files, and an editor that runs in your browser at [openkannada.org](https://openkannada.org).

On the way, and opening up one by one: fixed and extended Kannada fonts (Neha Sans, Neha Serif and Gari), a spell checker that understands Kannada word endings, OCR for old printed books, an open specification for the old font encodings, an English to Kannada dictionary, and a test suite for how well AI models handle Kannada.

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
