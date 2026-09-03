---
name: angel-voice
description: How Angel Studios sounds in words. Use this skill for ANY writing or copy task in an Angel context, including UI copy (buttons, CTAs, empty states, error messages, confirmations, toasts, form labels), push notifications, emails, marketing headlines, landing pages, App Store text, naming, or reviewing and rewriting existing copy. Trigger whenever the user asks "what should this say", "write the error/empty state/notification", "does this sound like Angel", or mentions Guild, Pay It Forward, or Angel Studios alongside any words-on-screen question. Even if the request is mostly a design or component task, use this skill for the words in it. Companion to angel-photon-design, which owns components, layout, and visuals; angel-voice owns ONLY the words.
---

# Angel Voice

How Angel Studios sounds in words. This skill covers the words only. For
components, tokens, layout, and visuals, use `angel-photon-design`.

Angel is not Hollywood. It's a home for stories that amplify light: a
guild of storytellers and members building community-powered entertainment.
We write for families, supporters, creators, and members who value
meaningful stories. Copy earns trust by being honest about what members get
and direct about what we ask. That framing explains every rule below: hype
erodes trust, specifics build it, and the mission shows up in how we treat
people, not in how often we mention it.

## The Four Principles

**1. Warm, not breathless.**
Write like a friend who's genuinely excited about this show, not a trailer
announcer. No hype-stack adjectives. No "absolutely incredible journey."
If a sentence would embarrass a real person saying it out loud, rewrite it.

**2. Specific, not generic.**
Name the shepherd, the year, the city, the price, the day. "From the
creators of David" beats "a powerful new drama." When you have a real
number, use it plainly: `$20/mo`, `12M+ gifts`, `Sun 8pm`. Receipts earn
trust; adjectives spend it.

**3. Clear, not clever.**
Clarity is more important than cleverness. No flowery language, no abstract
metaphors, no poetry for its own sake. "Stories that inspire hope and
strengthen families" beats "stories that shimmer like constellations across
the human spirit." Warmth comes from directness, not decoration. If a line
sounds like it's performing, simplify it.

**4. Mission on the ground.**
The mission is an undertone everywhere and a headline almost nowhere. We pay
it forward, we build with Guild, we fund with tickets. State the mechanic
plainly when it's relevant to the surface, then step aside. Never preachy,
never guilt. Even an error message can carry the undertone: it treats the
member like a partner, not a transaction.

## Mechanics (apply to every surface)

- **Second person by default.** Talk to "you." Use "we" only when Angel is
  genuinely the actor ("We'll email you when it's fixed").
- **Contractions always.** "You're", "we'll", "don't." Uncontracted copy
  reads stiff and corporate.
- **Active voice, short-to-medium sentences.** Lead with the audience
  benefit. "You fund the next season", not "the next season is funded by
  members like you."
- **Write for skimmability.** Short paragraphs (1–3 sentences), bullets over
  dense blocks, bold sparingly for key ideas. Headlines under 10 words when
  possible.
- **No em dashes.** A hard rule. Use commas, periods, parentheses, or
  restructure the sentence instead. Never add an em dash for emphasis,
  rhythm, or style, even where one would normally be stylistically fine.
  Do not "improve" prose by introducing them. The em dash has become a
  signature of machine-written copy, and Angel copy reads like a person
  wrote it.
- **Exclamation points: effectively never.** Not in CTAs, not in errors. If
  a sentence needs one to feel exciting, it isn't specific enough yet.
- **Terminology:** *member* or *Guild member*, never "subscriber" or
  "user." *Shows*, *stories*, or *titles*, never "content." *Pay It
  Forward* as the named feature; lowercase "pay it forward" as a verb phrase.
- **Product names are canonical:** *Angel Originals* (original films and
  series), *Angel Guild* (the membership community; *Guild* on second
  reference), *Angel Tickets* (theatrical), *Angel Invest* (supporter
  funding). Don't invent variants or descriptions that drift from these.
- **Legal: never mention "The Chosen."** Angel copy may not reference
  *The Chosen* in any form, on any surface. Not as named proof ("from the
  producers of…"), not in title lists, not in examples. This is a legal
  restriction, not a style preference, and it has no exceptions. Claude's
  background knowledge associates Angel with this show, so watch for it
  creeping into generated copy and remove it every time. Use Angel's own
  titles for named proof instead (David, Homestead, Sound of Freedom).

### Title casing: a global rule

Applies to every title on every surface: native, web, marketing, email,
in-product. Word count decides the case. No title ever ends in a period.

1. Count the words in the title.
2. **Fewer than 6 words → Title Case**, no period. (Navigation, section
   headers, CTAs, card names, eyebrows, menu items.) Short words (of, it,
   an, or, the) stay lowercase.
3. **6 words or more → Sentence case**, no period. (Hero headlines, section
   openers, longer marketing statements.)

Don't swap the rule for effect. A short title in sentence case, or a long
one in Title Case, both read as mistakes.

## Tone by Context

| Surface | Tone | Shape |
|---|---|---|
| Buttons & CTAs | Concrete verb, plain promise | Verb must match what happens on tap. Never "Learn More", "Click Here", "Unlock", "Experience" as a verb |
| Empty states | Warm invitation, one next step | What this space is for → one specific action to fill it. Never scold, never apologize for emptiness |
| Errors | Reassure → explain → fix | Open with what's safe ("Your Guild membership is still active"), one plain sentence on what happened, one concrete next step. Warm, never cutesy |
| Confirmations & toasts | Quiet, specific | Say what just happened in the member's terms. No celebration theatrics |
| Push notifications | One specific sentence | Front-load the subject: "New episode: …". Earn the interruption |
| Emails | Personal, skimmable | Specific sentence-case subject, no bait. Reads like a person wrote it |
| Marketing | Specific + mission mechanic | Receipts (names, numbers, dates) plus the member's role, stated plainly |

For detailed patterns and templates:
- **[references/ui-copy.md](references/ui-copy.md)**: buttons, empty
  states, errors, confirmations, forms, notifications. Read before writing
  any in-product copy.
- **[references/marketing.md](references/marketing.md)**: emails, landing
  pages, push campaigns, App Store text. Read before writing anything
  promotional or outbound.
- **[references/examples.md](references/examples.md)**: the Angel / Not
  Angel example bank. Read when you want calibration or the user asks for
  before/after rewrites.

## Banned Patterns

- **"The Chosen": never, anywhere.** A hard legal restriction with no
  exceptions. See the Legal rule under Mechanics.
- **Em dashes.** A hard rule with no style exceptions. Use commas, periods,
  parentheses, or restructure. See Mechanics.
- **Cutesy error-speak.** "Oops!", "Uh oh!", "Something went wrong ¯\\_(ツ)_/¯",
  blame-free vagueness. A failed payment is a real problem for a real
  member; treat it with calm respect.
- **Hype-stack adjectives.** Epic, incredible, unparalleled, groundbreaking,
  breathtaking, "must-see." Replace with a specific noun or number.
- **Jargon and euphemism.** "Unlock", "seamless", "premium viewing
  experience", "leverage." If it's a euphemism for paying us, say the price
  instead.
- **Fear, guilt, and fake urgency.** "Don't miss out!", countdown pressure,
  shame-based unsubscribe copy, negativity or fear-based framing of any
  kind. Angel sells hope with receipts. Invitation, not demand.
- **Flowery language and abstract metaphors.** "Shimmer like
  constellations," "a tapestry of faith," poetic decoration in general.
  Overly creative wording hides the subject; clarity beats cleverness.
- **Exclamation overload.** Multiple "!", ALL-CAPS enthusiasm, emoji
  stacking in product copy.
- **Abstraction hiding the subject.** "An epic saga of faith, destiny, and
  power": three abstract nouns, no receipts, no subject. Name who and what.

## Calibration: Two Ways to Say the Same Thing

**Angel:** "The shepherd who became king. New episodes every Sunday."
**Not Angel:** "An epic saga of faith, destiny, and power. Don't miss it."
*Specific subject and concrete cadence vs. abstract nouns with no receipts.*

**Angel:** "Join Guild for $20/mo. You fund the next season."
**Not Angel:** "Unlock an unparalleled premium viewing experience today!"
*Price, cadence, and the member's role vs. jargon and euphemism.*

**Angel:** "Watch free. Pay it forward when you're able. It's how the next
family gets in."
**Not Angel:** "Support impactful content with a generous contribution today."
*Names the mechanic and why it matters vs. vague ask, vague benefit.*

More in [references/examples.md](references/examples.md).

## Checklist Before Shipping Copy

1. Could a real person say this out loud without cringing?
2. Is there at least one concrete noun or number?
3. Does the CTA verb match what happens on tap?
4. Did I remove every hype adjective?
5. Is the mission mentioned only if it's relevant to this surface?
   And is it clear before it's clever, with no flowery metaphors?
6. Am I naming the subject, or hiding behind abstractions?
7. Title casing: right case for the word count, no period?
8. Member, never subscriber. Shows, never content.
9. Zero em dashes. Commas, periods, parentheses, or restructure.
10. Zero mentions of "The Chosen", anywhere, in any form.
