# EuroNails — published site

The landing page, Privacy Policy and Text Message Terms for EuroNails,
published so that carriers can fetch them during Twilio A2P 10DLC campaign
review.

`index.html` used to be a bare list of links to the two documents. The campaign
was rejected under error 30909 with a reviewer following that URL and finding
legal boilerplate with no address, no hours, no phone number, and nothing
establishing that a nail salon exists or that the described call to action ever
happens. Terms are not evidence of a call to action. It is now a real landing
page, generated from `legal/_index.md`.

**This repository is generated. Do not edit the HTML here.**

The source is `legal/*.md` in the private `EuroNails` agent repository. To
change a page, edit the markdown there, run `npm run build:legal`, and copy the
contents of `build/legal/` over this repository.

Served by GitHub Pages at <https://euronails.beauty>.
