# UI Copy — In-Product Words

Patterns for every string that ships inside the product: buttons, empty
states, errors, confirmations, forms, and notifications. All the global
rules from SKILL.md apply (second person, contractions, title casing,
terminology). This file adds the per-surface shapes.

## Contents

- [Buttons & CTAs](#buttons--ctas)
- [Empty states](#empty-states)
- [Error messages](#error-messages)
- [Confirmations & toasts](#confirmations--toasts)
- [Forms & inputs](#forms--inputs)
- [Push notifications](#push-notifications)
- [In-app badges & labels](#in-app-badges--labels)

## Buttons & CTAs

The verb matters. A button is a promise — its label must match the screen
you land on. Use concrete first- or second-person verbs.

| Situation | Use | Why |
|---|---|---|
| Free-to-watch title | `Watch Free` | Names the deal. No card required — say so nearby |
| Resume playback | `Resume S2 E4` | Specific episode beats generic "Continue" |
| Start a series | `Start Episode 1` | Concrete first step |
| Guild signup | `Join Guild — $20/mo` | Price on the button when the screen is about paying |
| Post-watch contribution | `Pay It Forward` | The named mechanic is the CTA |
| Theatrical window | `Get Tickets` | What actually happens |
| Save for later | `Add to Watchlist` | Names the destination |

**Never:** "Learn More" (lazy — say what they'll learn), "Click Here"
(web 1.0), "Unlock" (jargon), "Experience" as a verb, "Subscribe Now!"
(exclamation points never; and it's *join*, not *subscribe* — members,
not subscribers).

Buttons are almost always fewer than 6 words → Title Case, no period.

## Empty states

An empty state is an invitation, not an apology. Shape:

1. **One line on what this space is for** — warm, specific, no scolding.
2. **One specific action to fill it** — a real CTA, not "browse around."

Never apologize for emptiness ("Nothing to see here, sorry!"), never
scold ("You haven't added anything yet" reads as blame — prefer framing
around what the space will hold).

**Example — empty watchlist:**

> **Your Watchlist Is Waiting**
> Save shows here and they'll be ready when you are.
> `Browse Shows`

**Example — no downloads:**

> **Take Stories With You**
> Download episodes to watch on the road, no signal needed.
> `Find Something to Download`

## Error messages

Shape: **reassure → explain → fix.** Warmth here means calm confidence and
never blaming the member — not softness or cuteness.

1. **Reassure:** open with what's still safe or true. Scale it to the
   stakes — a payment error earns a full reassurance line; a playback
   hiccup may only need a calm headline.
2. **Explain:** one plain sentence on what happened. Be honest and
   specific. "Your card was declined" is more respectful than "something
   went wrong."
3. **Fix:** one concrete next step, usually as the CTA.

**Example — failed Guild payment:**

> **Your Guild Membership Is Safe**
> We couldn't process your payment — your card was declined. Update your
> card and we'll try again right away.
> `Update Payment Method`

**Example — playback error:**

> **Let's Get You Back to the Story**
> Playback hit a snag on our end. It usually clears on a retry.
> `Try Again`

**Example — offline:**

> **You're Offline**
> Your downloads still work. Everything else needs a connection.
> `Go to Downloads`

Notes:
- Own our failures ("on our end") and state member-side facts without blame
  ("your card was declined" — factual, not accusatory).
- Never "Oops", never shrug emoji, never a joke about losing the member's
  money or progress.
- If we genuinely don't know the cause, say what to try, not "unknown
  error."

## Confirmations & toasts

Quiet and specific. Say what just happened in the member's terms, then get
out of the way. No celebration theatrics, no exclamation points.

- `Added to your watchlist` — not "Awesome! Saved!"
- `Payment updated — you're all set through March` — the receipt is the
  reassurance.
- `Download complete: S1 E3` — specific beats generic.

Destructive confirmations name the consequence plainly:

> **Cancel Guild Membership?**
> You'll keep member access through March 14. After that, you'll stop
> funding new seasons and lose early access.
> `Keep Membership` / `Cancel Membership`

State the facts; no guilt trip, no begging. The mechanic ("you fund new
seasons") is honest information, not a shame lever.

## Forms & inputs

- Labels: short, Title Case (`Card Number`, `Email`).
- Placeholder text is an example, not an instruction (`jane@example.com`).
- Validation errors follow the error shape, compressed: what happened +
  fix in one line. "That email's missing an @ — double-check it?" is too
  cute; "Enter a valid email, like jane@example.com" is right.
- Never blame: "Enter your card's security code" not "You forgot the CVC."

## Push notifications

A push is an interruption — earn it. One specific sentence; front-load the
subject so it survives truncation.

- `New episode: David S2 E5 is live` — the show name is the hook.
- `Your gift landed — someone's watching free tonight` — Pay It Forward
  receipt, specific and warm.
- `Guild vote closes Sunday: pick the next pilot` — the member's role,
  a real deadline (a fact, not fake urgency).

Never send a push that's pure marketing pressure ("Don't miss out!") or
vague ("Something new for you 👀"). If there's no specific noun in it, it
shouldn't ship.

## In-app badges & labels

- Status labels are facts, not hype: `Free`, `Guild Early Access`,
  `In Theaters`, `Leaving Mar 14`.
- Never "Exclusive!" or "Hot 🔥". Specificity is the badge.
