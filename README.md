# JFT Simulation

JFT-Basic simulation exams, built manually one by one by Muse — aiming for the
world's best JFT simulation website.

## Exams

| # | Theme | Status |
|---|-------|--------|
| 1 | First weeks in Japan | Done, verified 50/50 → estimated 250/250 (A2.2) |
| 2 | Health, home, and the neighborhood | In progress |
| 3–100 | One theme each | Planned |

Each exam: 50 questions in the official split (14 Vocabulary / 12 Conversation /
12 Listening / 12 Reading), 60 minutes, fixed section order, no return to a
previous section, listening one-way with max 2 plays per clip, 3 options per
question.

## Honest notes

- **Scores are estimates.** The Japan Foundation scores JFT-Basic with a
  statistical method called equating and does not publish its conversion. The
  results screen maps raw score to the 10–250 scale proportionally and labels it
  an estimate, with the official bands (A1 145–174, A2.1 175–199, A2.2 200–250).
- **Listening voices are synthetic TTS**, not native-speaker studio recordings.
  This is disclosed on the results screen.
- **Level guardrails:** A2/N4 ceiling, kanji sparing, no furigana (matching the
  official model), no business keigo, no trade-certification depth. Everyday
  life words (hospital, library, city hall procedures) are in scope even where
  their kanji is individually above N4 — they are correct JFT vocabulary.

## How an exam is built

Hand-authored content → custom illustrations → TTS audio → playable player →
QA gates (split exact, key balance ~17/17/16, banned-pattern screen, listening
panels test visible content only, never day/time/price distinctions) → deploy.
Exams land in batches of 5 for review.
