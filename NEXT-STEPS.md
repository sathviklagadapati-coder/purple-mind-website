# Next steps (paused 2026-10-09)

## Priority: booking a strategy call
Booking calls is the main goal. Quiz responses are secondary and can be stored quietly.

Planned change:
- Every "Book a strategy call" button goes to a dedicated booking page.
- The quiz becomes a side link: "Not sure yet? Take the 2-minute assessment."

Booking method (not decided yet):
- **Option A (recommended): scheduler.** Prospects pick a time on your calendar.
  - Cal.com: generous free plan, embeds cleanly and can match site colors.
  - Calendly: best known. Free plan covers one event type; paid is about $10–12/month.
  - To do: create the account, connect your calendar, create a 30-minute "Strategy call" event, then send the booking link.
- **Option B: request form** through Formspree. Simpler, but you reply by email to schedule.

## Quiz responses (secondary)
- Use Formspree (free for 50 submissions/month): formspree.io → New form → copy the `https://formspree.io/f/...` endpoint.
- Paste it into `FORM_ENDPOINT` near the top of the script in `quiz.html`.
- In the Formspree settings, set "Restrict to domain" to `sathviklagadapati-coder.github.io`.
- Until then, quiz submissions are not sent anywhere. The page tells visitors this.

## Design rules to keep
- Purple is used only as a small accent: primary buttons, one headline phrase, progress lines, the selected quiz answer and the score ring. Everything else is neutral charcoal or grey.
- The "pm." logo keeps its original plum (#221236) and lavender (#D8C3FB).
- No client testimonials and no made-up stats. Keep the 988 crisis line in the footer.
