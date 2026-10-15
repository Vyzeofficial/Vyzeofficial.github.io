# SyraTHS

Live site: https://vyzeofficial.github.io/

SyraTHS is a free website that helps people read laptop listings before they buy. Listings are written to sell, and the words on them often do not match the hardware in the box. A "gaming laptop" may have no graphics card, a "12th generation processor" may be the slowest one in its family, and a crossed-out list price may never have been charged. This site explains what a listing says, points out what it leaves out, and shows whether a laptop can run the games and programs a buyer cares about.

The site earns nothing from the laptops it links to. It has no ads and no analytics.


## What is on the site

| Page | What it does |
| --- | --- |
| Home | Introduces the problem with an example listing and the claims in it that need a second look. |
| Decoder | Explains a spec or a phrase from a listing in plain words, such as what "up to 18 hours" or a processor name means in daily use. |
| Checker | Reads a pasted listing and flags claims that are vague, inflated or missing, with the reason for each. It also reads the specs it finds, shows what the laptop can run, and compares two listings side by side. |
| Can it run? | Shows the minimum and recommended specs for 50 games and 50 programs and compares them with a pasted listing or a saved laptop. The answer is red, yellow or green. It also suggests laptops from Top laptops that would run the title. |
| Top laptops | Laptops that review sites rated well for school, coding, creative work, gaming and travel, with specs, prices and the source for each. |
| Evidence | Court cases, regulator findings and reviewer tests showing that misleading laptop listings are common. Visitors can send a report. |
| My laptops | An optional page where a visitor signs in with Google and keeps a private list of their own laptops. |
| About, Privacy policy, Terms | Who the site is for, where its data comes from, and how it handles information. |

## How the answers are produced

- **Laptop picks** are not tested by us. Each one was named by a review site, and the price and specs come from the review linked under it.
- **Game and program requirements** come from each publisher's own page. Every entry lists its source.
- **Processor and graphics strength** comes from PassMark benchmark scores. Some scores are estimates, and the page says so.
- **Results are estimates.** A benchmark score shows how hardware compares on paper. It cannot promise a frame rate, and the tools do not check the operating system or free disk space.
- **The Checker reads text only.** It can tell when a listing is vague or missing something, but it cannot tell whether the claims are true.

## Data and privacy

There is no account to make and nothing to install. Reading the site, including the Decoder and Checker, sends nothing about the visitor anywhere.

Three features use Firebase, and only when the visitor chooses to use them:

- Signing in with Google on My laptops, which stores that visitor's own laptop list.
- The "Was this right?" question under results, which stores the answer, an optional note and, if the box is left ticked, the listing text.
- The report form on the Evidence page.

The full details are in the privacy policy page. Setup steps for the Firebase rules are in `FIREBASE-SETUP.md`.

## Built with

- HTML, CSS and JavaScript, with no framework
- Firebase Authentication and Firestore for sign-in, saved laptops, feedback and reports
- Chakra Petch and Inter fonts from Google Fonts
- Visual Studio Code for development and GitHub Pages for hosting
- Figma for the early layout and wireframes

## Logos and trademarks

Game and program logos and cover art belong to their owners. They are shown only to identify each title. SyraTHS is not connected to or endorsed by any of these companies.

## Contact

Found a mistake or a listing the Checker gets wrong? Email syrathsdev@gmail.com, use the "Was this right?" question under a result, or send a report from the Evidence page.

