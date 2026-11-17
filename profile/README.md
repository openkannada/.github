# Open Kannada

Free, open-source tools that make Kannada work properly on computers.

Years of Kannada documents were typed in old fonts that computers can't search or read aloud, and many everyday tools still handle Kannada badly. We build the missing pieces, test them on real text, and fix things upstream where they belong.

## Projects

- **[kannadi](https://github.com/openkannada/kannadi)**: convert documents typed in the old Nudi, Baraha, Nudi B-Akshara, Kan-Eng, Akruti and Shree-Lipi fonts to Unicode, and back. A Rust library, a command-line tool for whole folders of TXT, HTML, DOCX and PDF files, and an editor that runs in your browser.

On the way: fixed and extended Kannada fonts, a spell checker that understands Kannada word endings, OCR for old printed books, an English to Kannada dictionary, and a test suite for how well AI models handle Kannada.

Upstream so far: Kannada conjunct and arkavattu checks in [shaperglot](https://github.com/googlefonts/shaperglot/pull/192), the tool Google Fonts uses to test language support.

## How you can help

- **Have an old Nudi, Baraha or Shree-Lipi file that converts wrongly?** Open an issue on kannadi with a short sample. Every fixed case becomes a test.
- **Read Kannada well?** Help check converted text against the original. This is the work that turns our results into verified ones.
- **Design type?** Several open Kannada fonts are missing letters and heavier weights.

## Who we are

Open Kannada was founded by [Prasad Subrahmanya](https://prasad.tech) and [Neha Prasad](https://neha-prasad.com/), and is supported by [DataRavel Inc. (dba Luminik)](https://www.luminik.io).

Dedicated to Subramanya and Veena.
