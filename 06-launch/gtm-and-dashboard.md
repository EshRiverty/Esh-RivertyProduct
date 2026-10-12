# GTM Launch Plan, Riverty business-unit case

| Field | Value |
|---|---|
| Feature | _(not filled in)_ |
| Goal | Awareness |
| Launch tier | M, Targeted |

## Goal & Audience
- **Goal:** Awareness, Awareness, defined as activated cardholders knowing reminders exist, keeping notifications switched on, and recognizing the Pay now action.
- **Target audience:** Primary: activated heavy German Riverty cardholders (five or more purchases a year) who shop mostly online.

## Launch Tier
- **M, Targeted**, Tier M is justified, but only just, because the reach is small and already inside the Riverty app (about 21,900 reminded users in year 1, assuming 70% opt-in), and direct revenue is negligible (roughly EUR 4 of interchange per card per year at 0.1%, so about EUR 1,250 a year if reminders lift repeat use by one point). The real risk of staying silent is that users who never allow notifications never see the feature, and that reminders arriving from a little-known brand raise opt-outs and support load.

## Channels
1. **Owned: Owned: in-app and email. Prompt to switch on reminders at card activation, explaining what the reminder does. A card-tab banner announcing it, plus a short email to activated cardholders. A help-center article and release notes. The reminder itself is the strongest owned channel.**
2. **Earned: Earned: ride the card’s launch story, not a standalone push. One product-blog post or case note inside the wider card launch. Feedback quotes from pilot users, with their consent. No separate press effort: reminders are a minor feature and the audience is existing users.**
3. **Paid: Paid: none recommended. The audience is reachable for free, and paid media would mostly reach people without a card. If Tier L requires a paid element, mention the feature inside the card’s acquisition campaign, with no separate buy and nothing before the A/B read.**

## Enablement & Assets
Enablement & Assets
Copy (German and English): reminder text from the fixed templates, the permission prompt, banner, email and FAQ. Legal and risk must approve the wording, with no SCHUFA, credit or fee claims.
Visuals: the three PRD screens (lock-screen reminder, invoice detail, confirmation) in real UI, plus a short screen recording. The prototype uses fictional data and is for internal use only.
Support: an FAQ and reply macros for the likely questions: why a reminder appeared, what Pay now does, how to turn reminders off, and what happens if the amount changed.
Merchant success note: reminders apply to card invoices only and do not change integrated checkout.
Measurement: the reminder events (sent, opened, action tapped, paid) live before any announcement.
Experiment hygiene: announce reminders to everyone, but keep Pay now out of all messaging until the A/B read, or the control arm will be contaminated.

## Ownership, Budget & Timeline
- **Ownership & budget:** Owners: product manager (feature and metrics), product marketing (messaging and calendar), CRM owner (in-app and email), design (assets), legal and risk (copy approval), support lead (FAQ and macros), analytics (events and dashboard), engineering (flags and events). 
Budget is capped at  100k euros
- **Timeline:** Timeline (relative, since no launch date is set, and T is the broad announcement):
Before T, weeks 1 to 4: legal and risk copy approval, support enablement, instrumentation check, and a baseline measurement.
Before T, weeks 5 to 6: finish assets and translation.
Pilot: the permission prompt and reminders go to the test cohort only.
Read date: 17 days after the last sampled user’s first reminder, and not before 4 weeks of enrollment.
T: broad announcement only after a ship decision.
T+2 and T+4 weeks: check awareness metrics and the bad signals.
T+8 weeks: review whether Tier L stays.

## Success Metrics
- **Metrics:** Metrics:
Opt-in: share of activated cardholders with notifications allowed (target set after a baseline, placeholder 70%).
Recall: one in-app question, “Did you know your card can remind you before payments are due?”, answered yes by at least 60% of reminded users (placeholder).
Open rate: opened over delivered reminders, targets set from the first two weeks.
Downstream: the A/B and PRD metrics, meaning the not-paid-by-due-date rate and second card purchase within 30 days.
- **Bad signal to watch for:** Opt-outs rising 2 or more points above the control group, or opt-in stalling because of the permission prompt. High opens but few Pay now taps (aware but not acting). Support contacts saying reminders felt like pressure, or asking about credit or SCHUFA effects. Control-arm users seeing Pay now messaging. Integrated checkout volume more than 5% below a matched group for two weekly checks.
- **Likely post-launch decision:** hold the broad announcement until the A/B read. Then, if the ship criteria are met, push the announcement to all activated cardholders and shift the goal from awareness to adoption. Low opt-in: fix the prompt before spending on any channel. Awareness high but action low: iterate on copy and lead time. Inconclusive: extend the test. Kill: keep reminders without Pay now. T+8 weeks: decide whether Tier L stays.
