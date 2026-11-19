# Project memory

## Product intent & audience

- Personal romantic birthday microsite built as a surprise gift for a girl named Manisha.
- Goal is to impress her with heartfelt, warm, intensified romantic messaging — explicitly avoiding the word "crush."
- Audience is a single recipient (Manisha); not a general-purpose product.

## Brand personality & voice

- Romantic, playful, heartfelt, and slightly intense — but kept sweet rather than over-the-top.
- Speaks directly to Manisha in second person; uses an affectionate nickname "Manishaaa."
- Never uses the term "crush"; refers to her as "the birthday girl" or by name.
- Phrasing leans emotional and poetic ("Some people are felt… you're the kind of feeling people spend a lifetime searching for").

## Visual design & UX direction

- Vite + React stack; content is centralized in a single config file that all components pull from.
- Site structure/sections inferred: Intro, Hero, Letter, Reasons, Wish, Cake, Final surprise/final message.
- Includes a personal photo asset (currently `pihu.jpeg`) displayed somewhere on the site; filename not user-facing but may be renamed for consistency.
- Editing copy in the central config file propagates across the whole site.

## Decisions, constraints & rationale

- Name changed universally to "Manisha" across headings, letter, wish, cake section, and final message.
- Romantic intensification applied across all sections while preserving the playful original tone.
- Avoided explicit "crush" label per user request; kept relationship framing understated but emotionally charged.
- Kept changes text-only; did not rename the underlying photo asset unless user requests it.

## Open questions & assumptions

- Asset `pihu.jpeg` still uses a prior name internally — user has been offered a rename but has not confirmed.
- Assuming romantic intensity level is appropriate; user may want further tonal tuning after review.
- No `.bolt/prompt` exists yet, so global instructions are currently absent.