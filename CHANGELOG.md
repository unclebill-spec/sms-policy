# Changelog

## 2026-10-08 (second resubmission)
- Simplified to a single opt-in path: the web form at `optin.html` (START text is its double opt-in confirmation step). Removed the in-person script and standalone text-START path.
- Brand name in messages and pages now matches the registered sole proprietor brand: "Will Weathersbee". All messages start with "Will Weathersbee:".
- Form page lists the message types and shows the exact confirmation text; Privacy and Terms are linked on the form. Terms list the exact opt-in, STOP, and HELP replies.
- Regenerated `optin-screenshot.png` (checkbox checked, sample number). Rewrote `RESUBMIT.md`.

## 2026-10-08
- Added `optin.html`: web sign-up form with a phone number field and a required, unchecked-by-default consent checkbox with full SMS disclosures. Submitting it opens a START text to (854) 254-5107 so the user confirms by text (double opt-in). No backend; the number is never transmitted.
- `index.html` now lists all three opt-in paths (web form, texting START, in-person script) and links to the form.
- Privacy policy and terms updated to cover the web form, the in-person invitation, and reminders/relayed messages.
- Regenerated `optin-screenshot.png` to show the new form and its disclosures.
- Added `RESUBMIT.md` with paste-ready Twilio A2P 10DLC campaign text after the Error 30909 rejection.

## 2026-10-07
- Initial SMS privacy policy, terms, opt-in page, and opt-in screenshot for the A2P 10DLC campaign.
