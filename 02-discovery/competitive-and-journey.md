# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Role: Salaried Germans aged 25 to 40, like Lena, who use BNPL on most non-trivial purchases, hold two or more pay-later providers, and at least sometimes want to pay later in a store.

What defines them: They use BNPL mainly to pay only after they've decided to keep the item, and they pick whichever option appears at checkout.
What separates them from the wider base: They manage several providers' due dates themselves, which makes them the heavy, multi-provider users the hook is about. Users who only buy online with one provider aren't the target.
Best embodiment: P6 (31, Stuttgart) holds three providers and uses BNPL in stores, so they combine both halves of the hook. P4 is the secondary case, for the in-store gap.
- **Goal, what is this user ultimately trying to achieve?:** Goal: To buy what they want, online or in a store, and have money leave their account only for what they've decided to keep, without having to track it all by hand.

The core motive: The leading reason for using BNPL in the research is paying only after deciding to keep the item (52%), ahead of spreading the cost (31%). The goal is control over timing, not credit as such.
The side goal: They want that control without extra effort. P6's calendar workaround and the 49% who would move more spend for one due date across all purchases point to wanting one clear view of what's due.
Not the goal: They aren't trying to get a Riverty card. The card is only the means, and the research doesn't show users asking for one.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Friction: The user has to run their own system to keep control. Because they hold several providers, each with its own reminders, they put every due date into a personal calendar or notes. Nothing gives them a single view of what's due, so the control they want depends on manual tracking they can't fully trust.

The moment: P6 enters every due date in their own calendar because they can't trust three apps to remind them properly. The pain is the unpaid work of managing the product's gap, plus the worry that something slips.
How common it is: In the synthetic survey, 44% track due dates outside the apps, and 29% missed or nearly missed a due date in the last six months.
Why it blocks the goal: Paying only for what they keep requires knowing what's due and when. Without a single view, the control they wanted turns into upkeep.
Secondary friction: At a till with no pay-later option (P4), they fall back on debit and lose the deferral entirely.
- **External tools, the outside platforms or tools the user is forced to use:** Only two outside tools are documented in the research. The rest are my guesses and need checking.

Documented

A personal calendar. P6 enters every due date there because they can't trust three apps to remind them. The survey's 44% tracking outside the apps supports this, but it doesn't say which tools those users rely on.
A debit card at the till. P4 used it twice when pay-later wasn't available in a store. It's the only external payment tool named in the data, and it removes the deferral the user wanted.
Competitor apps used in parallel. Participants hold Klarna and PayPal alongside Riverty (74% use two or more providers). Each is a separate system with its own due dates and reminders, so the user bridges between them by hand.

Likely but not in the data

Notes apps or spreadsheets, screenshots of confirmations, email receipts, and the banking app to check what's coming out. These are plausible, but nobody in the research mentions them.

Why they're forced into it
No single product shows what's due across providers, and Riverty and its competitors give no pay-later option at the till. The calendar and the debit card cover those two gaps.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Only the calendar step is documented. The rest is my reconstruction from the research and needs checking in discovery.

Accept whatever option appears at checkout. The user doesn't compare providers and just taps the one shown (68% in the synthetic survey).
Find the due date in that provider's app or confirmation. Each provider shows its own schedule, so the user has to look it up (inferred).
Copy the date into a personal calendar. P6 does this for every purchase because the apps' reminders can't be trusted (documented).
Repeat for every purchase and every provider. No provider shows the others' dates, so the user keeps the combined view by hand (inferred from the multi-provider figures).
Check the calendar against the return window. The user decides what to keep and looks at what is about to come out of the account (inferred from the "decide first, pay after" motive).
- **Core frustration, the exact moment the process feels most “broken”:** The most broken moment is when the user's own tracking system lets a due date nearly slip by. The user built the calendar because they don't trust the apps, and this is the point where they realize the calendar didn't save them either.

What's documented: P6 enters every due date by hand because they can't trust three apps to remind them. In the synthetic survey, 29% missed or nearly missed a due date in the last six months.
What's inferred: the felt moment itself, a sudden "wait, that's due today?" with a payment about to come out of an account with little cushion. No participant describes it, and "nearly missed" could mean anything from a minor scare to a late fee, since the data doesn't say.
Why this moment and not another: the calendar workaround is steady background effort, and the debit fallback at the till is a one-off annoyance. A near-miss is where the effort fails, and where the user's control, the thing they came to BNPL for, is lost.
- **The evidence, a specific quote or behavior from the research that proves this:** The research supports the workaround and how common the near-misses are, but it doesn't directly prove the felt moment.

The quote (P6, 31, Stuttgart): "I put every due date in my calendar because I can't trust three apps to remind me properly."

What it proves: the user runs their own system because the apps' reminders aren't trusted. That is behavior, not just opinion.

The survey figures (n=420):

44% track due dates outside the apps, which shows P6 is not a one-off.
29% missed or nearly missed a due date in the last six months, which shows the system sometimes fails.
74% use two or more providers, which explains why: each provider only shows its own dates.

What it doesn't prove

The 29% combines "missed" and "nearly missed," so the data can't separate real misses from minor scares.
No participant describes the near-miss itself or what it cost them.
All of this is synthetic data that I wrote, so it can illustrate the hypothesis but can't confirm it. Real evidence would be a first-hand account from a user who nearly missed a payment, or their calendar and banking app showing how often it happens.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** Your "Strategy" line still read "[Pick a strategy block above]", so I built this on your value proposition. This is the future state for a card that doesn't exist yet. Internal states are inferred, since the research doesn't show how any of this would feel.1. **Activate**
   - User Action: Adds virtual card to phone wallet -> ready for stores and online at once.
   - Internal State: Wary of a fourth card -> won over by one place for pay-later.
   - Pain Point Addressed: Wallet crowding and low brand trust -> a reason to carry Riverty.

2. **Pay anywhere**
   - User Action: Taps card at the till, chooses pay later -> deferral works outside partner shops.
   - Internal State: Relieved -> pay-later feels the same in stores as online.
   - Pain Point Addressed: No pay-later at tills -> no forced debit fallback.

3. **Track**
   - User Action: Opens one view of card purchases and due dates -> no manual calendar entries.
   - Internal State: Calm -> trusts one reminder source instead of double-checking her calendar.
   - Pain Point Addressed: Scattered due dates and near-misses -> fewer surprises on card purchases.

4. **Settle**
   - User Action: Keeps or returns items within the window -> pays only for what she keeps.
   - Internal State: In control -> money moves after her decision, not before.
   - Pain Point Addressed: Money leaving before the keep-or-return decision -> timing follows her choice.

**Three competitive advantages over the manual workaround**
1. One view replaces calendar entries -> no manual upkeep for card purchases, fewer missed dates.
2. Pay-later at any till -> deferral survives where the manual workaround falls back to debit.
3. Payment timing follows the keep-or-return decision -> money leaves only for what she keeps.

Three limits on this future state:
- **Stage 3 covers card purchases only.** Klarna and PayPal due dates stay outside the view unless Lena moves most of her spend onto the card, so advantage 1 depends on that shift.
- **Stage 4 is a hypothesis.** Payment timing that follows return windows is untested, and the consumer credit rules from 20 November 2026 may limit how it can work, so it needs a risk and regulatory check.
- **Stage 1 is the weakest.** Wallet crowding was the biggest barrier in the research, and nothing here shows the card overcomes it.
