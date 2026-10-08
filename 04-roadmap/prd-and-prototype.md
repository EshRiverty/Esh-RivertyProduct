# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** _(not filled in)_
- **My finalized Must-Haves (after overriding the AI):** Scheduled reminder per card invoice. A push notification at a fixed lead time before the due date, showing merchant, amount and due date. This is the tracking half of the misery. Without it there is no feature.
Deep link to that specific invoice. The reminder opens that invoice with the amount and due date already shown. Without it the user has to hunt for the invoice, which is the manual tracking we're removing.
One-tap Pay now. A single pay action in the reminder, pre-filled from the linked bank account. If strong customer authentication is required, that adds a biometric step but no extra screens. This is the minimum "one-tap action."
Reminder state kept in sync with payment. Once an invoice is paid, no further reminders go out and the status updates. A reminder for something already paid would destroy trust in every future reminder.
- **What I demoted from Must → Should/Won’t, and why:** Postpone reminder

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The PRD limits reminders to card invoices only and leaves reminders for integrated-checkout invoices untouched, which a vague brief ("add due-date reminders") would not have said. That choice protects the guardrail, since shifting the same purchases onto the card swaps a 1.54% merchant fee for 0.1% interchange and takes contribution margin from 1.3% to -0.1%.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** The prototype exposed five gaps. The first two matter most, and the last three are smaller.

Dead end when no reminder is sent. The PRD's three screens all start from the reminder. In the notifications-off and merchant-missing scenarios, the phone showed an empty lock screen with nothing to tap and no way to reach the invoice. For those users the feature does nothing, and the missing-merchant user is never told. The PRD should either add an in-app way into unpaid invoices or state that these users are out of scope for the metric.
Speed and safety conflict when the amount changes. The PRD says Pay now opens the confirm sheet immediately, and also says the on-screen amount always wins. With a changed amount, a user could confirm €94.90 after being notified of €89.90. In the prototype I put a notice inside the sheet, but that was my call. If the PRD instead sends the user through Screen 2 first, that adds an action and breaks the 2-action target.
The 2-action target is ambiguous. FR4 and Story 2 say 2 actions, but tapping the reminder body takes 3 (tap, Pay, confirm). Any retry after a failure also pushes a run over 2. The PRD needs to say which path the target covers and whether failed attempts count.
Reminder copy goes stale. A notification can't be edited after delivery, so "Payment due in 3 days" can sit on the lock screen after the due date, or after the user paid elsewhere. In the past-due scenario, the reminder and the invoice contradicted each other. Showing the absolute due date in the notification would avoid this.
Two smaller points.
A deliberate Cancel shows the same "Payment not made" error as a failure, though the user chose it.
Some measures can't be tested in a prototype with no timers: the 09:00 send time (FR1) and the 1-second status update (FR6). The scenario switcher only simulates them, so they need engineering tests.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://github.com/EshRiverty/Esh-RivertyProduct/blob/main/04-roadmap/riverty_card_reminders_prototype.html
