# Changelog

## 2026-10-08
- Added `optin.html`: web sign-up form with a phone number field and a required, unchecked-by-default consent checkbox with full SMS disclosures. Submitting it opens a START text to (854) 254-5107 so the user confirms by text (double opt-in). No backend; the number is never transmitted.
- `index.html` now lists all three opt-in paths (web form, texting START, in-person script) and links to the form.
- Privacy policy and terms updated to cover the web form, the in-person invitation, and reminders/relayed messages.
- Regenerated `optin-screenshot.png` to show the new form and its disclosures.
- Added `RESUBMIT.md` with paste-ready Twilio A2P 10DLC campaign text after the Error 30909 rejection.

## 2026-10-07
- Initial SMS privacy policy, terms, opt-in page, and opt-in screenshot for the A2P 10DLC campaign.
