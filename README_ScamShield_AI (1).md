# ScamShield AI

ScamShield AI is a Dialogflow ES chatbot concept that helps users recognize common online scams and learn safer next steps.

## Project objective

The chatbot provides general awareness and safety guidance for suspicious messages, links, calls, payment requests, fake job offers, OTP requests, and other common fraud patterns.

## Main features

- Scam-check guidance for suspicious messages
- Awareness of phishing, OTP, UPI/QR-code, fake job, fake refund, fake support, and delivery scams
- General account and password safety guidance
- Suggestions for preserving evidence and reporting suspected fraud
- Conversation handling for verification guidance and requests for further help

## Technology

- **Chatbot platform:** Dialogflow ES
- **Language:** English
- **Version control / documentation:** GitHub

## Dialogflow setup

1. Open the ScamShield AI agent in Dialogflow ES.
2. Check that the required custom entities exist before importing any intent files.
3. Import or configure the intent JSON files one at a time.
4. Review each intent's training phrases, parameters, required-slot prompts, and responses.
5. Save the agent and test it in the Dialogflow **Try it now** panel.

> Important: Dialogflow intent JSON files can depend on the custom entities configured in the agent. Verify each import and do not import duplicate intent names.

## Example test scenarios

| Scenario | Example user message | Expected behaviour |
|---|---|---|
| General scam check | “I received a suspicious message asking me to pay a fee.” | The bot should identify the relevant scam-check intent and offer safe next steps. |
| OTP safety | “Someone asked me to share my OTP.” | The bot should warn the user not to share OTPs or verification codes. |
| Suspicious link | “How can I check if this link is safe?” | The bot should advise independent verification and caution with unexpected links. |
| Fake job offer | “A recruiter wants a registration fee before an interview.” | The bot should explain that upfront fees can be a warning sign. |
| Payment request | “I received an unexpected UPI collect request.” | The bot should advise not approving unknown payment requests. |

## Safety note

ScamShield AI provides general educational guidance. It is not a bank, law-enforcement service, or substitute for professional support. Users should contact their bank or service provider through official channels if money, credentials, or account access may be at risk.

## Project status

The Dialogflow agent and its imported intents should be tested before describing the chatbot as fully working. Add screenshots of the agent, test results, and any required teacher-assessment evidence to this repository.

## Author

Student project — update this section with your name and class if your teacher requires it.
