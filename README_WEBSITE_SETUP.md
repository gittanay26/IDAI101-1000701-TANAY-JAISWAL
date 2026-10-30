# ScamShield AI Website

Static website for the ScamShield AI Dialogflow ES project.

## Files
- `index.html` — public landing page and Dialogflow Messenger embed
- `styles.css` — responsive styling

## Deploy to Vercel
1. Upload both files (`index.html` and `styles.css`) to the **root** of the GitHub repository.
2. Commit the changes to the `main` branch.
3. In Vercel, keep **Root Directory** as `./`.
4. In Build and Deployment, use the **Other** framework preset if Vercel asks for a framework. Leave Build Command and Output Directory empty/default for a plain static HTML site.
5. Redeploy. Open the production domain and test on desktop and mobile.

## Dialogflow Messenger
The page includes the Dialogflow Messenger widget using the agent ID currently supplied for this project:
`32a3f857-bc90-4db0-952b-3380f6fd76ea`

Confirm this exact agent ID in Dialogflow > Integrations > Dialogflow Messenger. If it differs, replace the `agent-id` value in `index.html`. The integration must be enabled and the agent must have a working Default Welcome Intent.

## Rubric alignment
- Problem understanding: homepage explains scam-awareness problem, intended users and project purpose.
- Dialogflow: public chatbot widget; the actual intent/entity/slot-filling configuration remains in the Dialogflow agent.
- Testing: page includes five realistic scenarios as a **test plan**. Run them in the live widget, record actual outputs and pass/fail, and fix issues before claiming testing is complete.
- GitHub/documentation: repository should include this README, the website source, a clear intent/entity inventory, and the verified live website URL.

## Important limitations
The Messenger widget returns configured Dialogflow responses. It does not automatically perform forensic analysis of arbitrary pasted messages or live URL reputation checks. Those require a secure webhook/backend or trusted external service.

Do not ask visitors to submit passwords, OTPs, PINs, account numbers, or other sensitive information.
