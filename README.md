# Home Credit LAP Voice Agent

A Retell AI voice agent designed to conduct preliminary qualification for Home Credit's Loan Against Property (LAP) offering.

## Project Overview

This project demonstrates how a conversational AI voice agent can interact with existing customers, collect property and financial information, perform preliminary eligibility checks, and identify the appropriate next step.

The agent is designed to communicate politely, handle natural conversations, capture answers given in different orders, and avoid repeating questions that have already been answered.

## Key Features

- Customer identity verification before discussing the offer.
- Conversational introduction to a potential LAP offer of up to ₹75 lakh.
- Preliminary qualification based on seven required information points.
- Handling of customer interruptions, unclear responses, and corrections.
- Callback preference collection when a customer is busy.
- Special handling for existing property loans and EMI reduction or loan-transfer requests.
- Routing of potentially eligible customers to a senior loan expert.
- Polite handling of ineligible customers.
- No invented interest rates or promises of final loan approval.

## Preliminary Eligibility Rules

The agent evaluates the following information:

1. **Property type:** Residential, commercial, and industrial properties are eligible for preliminary screening. Agricultural property is ineligible.
2. **Ownership:** Sole and joint ownership are accepted.
3. **Original property documents:** The customer must have the original property documents available.
4. **Loan amount:** The maximum amount considered by the agent is ₹75 lakh. Customers requesting more are asked whether they can accept the maximum amount.
5. **Occupation and income:** Salaried and self-employed customers can be considered, but income must be received through a bank. Cash-only income does not qualify.
6. **Estimated property value:** The agent records the customer's estimated market value without inventing a minimum threshold.
7. **Loan tenure:** The requested tenure must be between 3 and 15 years, inclusive.

These checks are preliminary only. Final eligibility, applicable interest rates, and loan approval are determined by the appropriate Home Credit representative.

## Special Case Handling

If a customer already has a property loan or requests EMI reduction or a loan transfer, the agent explains that a loan-transfer specialist will contact them and ends the current qualification flow.

If a customer is not interested, cannot meet an eligibility requirement, or has not provided enough information, the agent handles the outcome accordingly.

## Testing

The agent was tested using simulated customer conversations. Test scenarios included:

- Potentially eligible customer journey.
- Agricultural property.
- Original property documents unavailable.
- Loan amount above ₹75 lakh.
- Existing property loan or EMI reduction request.
- Customer responses provided in a different order.
- Loan amount clarification and other unclear responses.

Recordings and transcripts are maintained separately as project evidence.

## Technology

- Retell AI
- Large language model-based conversational agent
- Voice interaction and speech transcription
- Prompt-based qualification and conversation control

## Demo and Test Evidence

- **Published agent demo:** Add the working, shareable Retell agent link here.
- **Test recordings and transcripts:** [Open project evidence on Google Drive](https://drive.google.com/drive/folders/1vn0x8DH5GLo1zHllXIq3BShewawJwlln?usp=sharing)

## Limitations

This is a preliminary qualification assistant, not an automated loan approval system. It does not calculate or promise interest rates, guarantee approval, or replace review by a loan expert.
#links 
## Demo and Test Evidence

- **Published Retell AI agent demo:** [Try the voice agent](https://agent.retellai.com/orb/agent_c36ccc2eb4bf4ab39c2716f99d?token=f3b4e28870a44920f7b8334040ba76b8)
- **Test recordings and transcripts:** [Open Google Drive evidence folder](https://drive.google.com/drive/folders/1vn0x8DH5GLo1zHllXIq3BShewawJwlln?usp=drive_link)
- **Screen recording:** Available in the Google Drive folder above.



The implementation uses Retell AI configuration rather than a custom-coded voice platform.
