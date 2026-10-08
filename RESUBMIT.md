# Twilio A2P 10DLC campaign resubmission text

Campaign: CM6542ae991d24abba89dba0381228efa2 (STARTER), number +18542545107 / (854) 254-5107.
Rejected Oct 8, 2026 with Error 30909 (Message Flow/CTA doesn't show enough about how users consent). Each section below is ready to paste into the matching Twilio field.

## Campaign description

Will Weathersbee Automated Assistant is a low-volume, non-marketing automated AI assistant text line run by sole proprietor Will Weathersbee. A small group of invited family contacts who have opted in text (854) 254-5107. They receive automated replies to their texts (schedule info, weather, lookups), messages relayed for Will Weathersbee, and reminders they ask for. The line never sends marketing or promotional messages and never messages anyone who has not opted in by texting START. Opt-in details: https://unclebill-spec.github.io/sms-policy/

## Message Flow / Call-to-action

```
End users are invited family contacts of sole proprietor Will Weathersbee. All three opt-in paths end with the user texting START from their own phone to (854) 254-5107.

1) Web form: https://unclebill-spec.github.io/sms-policy/optin.html. User enters their mobile number and checks a required, unchecked-by-default box: "I agree to receive text messages from Will Weathersbee Automated Assistant at the phone number above, including replies to my texts, schedule info, messages relayed for Will Weathersbee, and reminders. Message frequency varies. Message and data rates may apply. Reply STOP to opt out, HELP for help. Consent is not a condition of purchase. See our Privacy Policy and Terms & Conditions." On submit, the page opens a text to (854) 254-5107 with the body START; the user sends it to confirm (double opt-in). Screenshot: https://unclebill-spec.github.io/sms-policy/optin-screenshot.png

2) In person: Will Weathersbee reads: "Would you like to get texts from Will Weathersbee Automated Assistant at (854) 254-5107? It sends replies to your texts, schedule info, messages relayed for me, and reminders. Message frequency varies. Message and data rates may apply. Reply STOP to opt out, HELP for help. If you agree, text START to (854) 254-5107 to confirm." The user is opted in only after texting START.

3) Text START to (854) 254-5107, as published at https://unclebill-spec.github.io/sms-policy/.

After START, the user receives: "Will Weathersbee Automated Assistant: You're opted in to replies to your texts, schedule info, messages relayed for Will Weathersbee, and reminders. Msg frequency varies. Msg & data rates may apply. Reply HELP for help, STOP to opt out."

Privacy: https://unclebill-spec.github.io/sms-policy/privacy.html
Terms: https://unclebill-spec.github.io/sms-policy/terms.html
```

(1,819 characters, under Twilio's 2,048 limit.)

## Opt-in confirmation message

Will Weathersbee Automated Assistant: You're opted in to replies to your texts, schedule info, messages relayed for Will Weathersbee, and reminders. Msg frequency varies. Msg & data rates may apply. Reply HELP for help, STOP to opt out.

## HELP reply

Will Weathersbee Automated Assistant: For help, email unclebill@gmail.com or visit https://unclebill-spec.github.io/sms-policy/. Msg frequency varies. Msg & data rates may apply. Reply STOP to opt out.

## STOP (opt-out) reply

Will Weathersbee Automated Assistant: You are unsubscribed and will receive no further messages. Reply START to rejoin.

## Sample message 1

Will Weathersbee Automated Assistant: Tomorrow's schedule: dentist at 9:30 AM, then soccer practice at 5:00 PM at Riverside Park. Reply STOP to opt out.

## Sample message 2

Will Weathersbee Automated Assistant: Message from Will Weathersbee: "Running 15 minutes late, I'll pick you up at 6:15." Reply HELP for help, STOP to opt out.

## Keywords

- Opt-in keywords: START, UNSTOP, YES
- Opt-out keywords: STOP, STOPALL, UNSUBSCRIBE, CANCEL, END, QUIT, OPTOUT, REVOKE
- Help keywords: HELP, INFO

## Other campaign settings

- Embedded links: Yes (HELP reply links to the policy site). Embedded phone numbers: No. Age-gated content: No. Direct lending: No.
- Opt-in, opt-out, and help messages above should match the Advanced Opt-Out replies configured on the Messaging Service, so the texts users actually get match what is submitted.
