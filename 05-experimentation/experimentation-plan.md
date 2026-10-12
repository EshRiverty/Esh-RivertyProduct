# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | One-tap “Pay now” action in the due-date reminder |
| Persona | Activated heavy German Riverty cardholders (five or more purchases a year) who shop mostly online |
| Expected outcome | More users pay their card invoice shortly after the reminder, with fewer taps |
| Primary success metric | Share of users whose first card invoice is paid within 24 hours of the reminder being delivered |
| Baseline rate | 40% (placeholder) |
| Guardrail metric | Integrated checkout volume per heavy user at partner merchants |
| Guardrail boundary | Variant no more than 5% below control |
| Second guardrail | · |
| Minimum Detectable Effect | +10 percentage points |
| Sample size per arm | About 390 users, so about 780 in total |
| Traffic split | 50/50 |
| Test duration | 4 weeks, two full 14-day invoice cycles |
| Significance threshold | p < 0.05 |

## Control vs. Variant
- **Control (A):** the reminder with one action, Open invoice. The user opens the invoice, taps Pay, then confirms (3 actions).
- **Variant (B):** the reminder with Pay now and Open invoice, Pay now goes straight to the confirm sheet (2 actions)
- **Held constant (isolation check):** send time (3 days before due, 09:00), title and body text, invoice screen, payment source, confirm sheet, and amount shown.

## Hypothesis
> I believe that One-tap “Pay now” action in the due-date reminder for Activated heavy German Riverty cardholders (five or more purchases a year) who shop mostly online will result in More users pay their card invoice shortly after the reminder, with fewer taps, as measured by a +10 percentage points change in Share of users whose first card invoice is paid within 24 hours of the reminder being delivered within 4 weeks, two full 14-day invoice cycles. We will protect Integrated checkout volume per heavy user at partner merchants throughout the test.

## Shipping criteria
> We will **ship** if Share of users whose first card invoice is paid within 24 hours of the reminder being delivered improves by ≥ +10 percentage points at p < 0.05 and Integrated checkout volume per heavy user at partner merchants does not reach Variant no more than 5% below control after 4 weeks, two full 14-day invoice cycles.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 4 weeks, two full 14-day invoice cycles, no results reviewed before this date.
