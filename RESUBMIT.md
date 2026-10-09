# Twilio A2P 10DLC campaign resubmission text

Campaign CM6542ae991d24abba89dba0381228efa2 (use case SOLE_PROPRIETOR), number (854) 254-5107. Registered brand name: Will Weathersbee (brand BN3dcbb678bddcf531cd4f92842126988b).
Updated Oct 8, 2026, after the second Error 30909 rejection (MESSAGE_FLOW). Opt-in is now only through the web form. Paste each section into the matching Twilio field. Every message starts with "Will Weathersbee:" and matches the site word for word.

## Campaign description

Will Weathersbee (sole proprietor) runs a low-volume personal assistant text line at (854) 254-5107. People who sign up on the web form at https://unclebill-spec.github.io/sms-policy/optin.html can text the line and get automated replies, such as schedule info, weather, and lookups, plus messages relayed for Will Weathersbee and reminders. No marketing or promotional messages are sent, and no one is messaged unless they have signed up.

## Message Flow / Call-to-action

Opt-in is only via web form: https://unclebill-spec.github.io/sms-policy/optin.html. User enters mobile number and checks a required, unchecked box: "I agree to receive text messages from Will Weathersbee at the phone number above, including replies to my texts, schedule info, messages relayed for Will Weathersbee, and reminders. Message frequency varies. Message and data rates may apply. Reply STOP to opt out, HELP for help. Consent is not a condition of purchase. See our Privacy Policy and Terms & Conditions." Sign up opens a pre-filled text with START to (854) 254-5107; sending it completes sign-up (double opt-in). Confirmation: "Will Weathersbee: You're signed up for texts: replies to your texts, schedule info, messages relayed for Will Weathersbee, and reminders. Msg frequency varies. Msg & data rates may apply. Reply HELP for help, STOP to opt out." Screenshot: https://unclebill-spec.github.io/sms-policy/optin-screenshot.png Privacy: https://unclebill-spec.github.io/sms-policy/privacy.html Terms: https://unclebill-spec.github.io/sms-policy/terms.html

## Opt-in message

Will Weathersbee: You're signed up for texts: replies to your texts, schedule info, messages relayed for Will Weathersbee, and reminders. Msg frequency varies. Msg & data rates may apply. Reply HELP for help, STOP to opt out.

## Opt-out message

Will Weathersbee: You are unsubscribed and will receive no further messages. Reply START to resubscribe.

## Help message

Will Weathersbee: For help, email unclebill@gmail.com or visit https://unclebill-spec.github.io/sms-policy/. Msg frequency varies. Msg & data rates may apply. Reply STOP to opt out.

## Sample message 1

Will Weathersbee: Tomorrow's schedule: dentist at 9:30 AM, then soccer practice at 5:00 PM at Riverside Park. Reply STOP to opt out.

## Sample message 2

Will Weathersbee: Message relayed from Will: "Running 15 minutes late, I'll pick you up at 6:15." Reply HELP for help, STOP to opt out.

## Keywords

- Opt-in keywords: START
- Opt-out keywords: STOP, STOPALL, UNSUBSCRIBE, CANCEL, END, QUIT, OPTOUT, REVOKE
- Help keywords: HELP, INFO

## Before resubmitting

- Replace the old opt-in message ("You're now subscribed to Will Weathersbee's assistant...") with the one above.
- Set the Messaging Service's Advanced Opt-Out replies (opt-in, opt-out, help) to match the three messages above exactly.
- Embedded links: Yes (the help message). Embedded phone numbers: No. Age-gated: No. Direct lending: No.
