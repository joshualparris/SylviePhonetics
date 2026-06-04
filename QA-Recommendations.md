# SylviePhonetics QA Recommendations

This document records the QA audit findings for SylviePhonetics and the recommended changes to align the app with early childhood learning, neurodiversity-aware design, and family co-play goals.

## Key Audit Findings
- Missing scaffolded feedback on wrong answers.
- No session timer or natural closing ritual.
- No movement or breathing breaks between games.
- Phonological tasks and grapheme tasks are mixed too early.
- Parent co-play prompts are not built into gameplay.
- Some interactions are too small on mobile and keyboard mode can confuse young children.

## Recommendations
1. Add scaffolded error feedback.
   - Gentle hint after an incorrect response.
   - Model the target phoneme without adding a schwa.
   - Invite the child to try again.
   - **Acceptance**: every wrong answer triggers a specific hint before the correct answer is shown.

2. Add a session timer and closing ritual.
   - After 10–12 minutes, show a calm transition screen.
   - Prompt the child to share progress with a parent and move to offline play.
   - **Acceptance**: the app pauses and offers a friendly end-of-play animation after the timer.

3. Insert movement or breathing breaks.
   - Every 5–7 minutes, present a short interstitial screen.
   - Use simple movement instructions or breathing prompts.
   - **Acceptance**: the app invites the child to pause, move, or breathe before continuing.

4. Separate phonological awareness from letter tasks.
   - Keep rhyme and sound games free of letters until phoneme isolation is secure.
   - Avoid mixing letters and pictures in early levels.
   - **Acceptance**: each mini-game targets one learning stage only.

5. Add in-context parent co-play prompts.
   - Encourage adults to say words, listen together, or act out sounds.
   - Make prompts visible in game screens rather than hidden settings.
   - **Acceptance**: each game includes at least one caregiver prompt.

## Implementation Notes
- Use locally stored audio and avoid external streaming.
- Improve mobile tap areas for selectable answers and feedback controls.
- Consider an optional audio/caption mode for accessibility.

## Suggested Roadmap
- `P1`: scaffolded hints, timer, closing ritual
- `P2`: movement/breathing breaks, parent prompts
- `P3`: sound-only phonological sequence, accessibility mode

## Status
- [ ] Add scaffolded hints and error coaching
- [ ] Add session timer and closing ritual
- [ ] Add movement/breathing breaks
- [ ] Separate sound tasks from letter tasks
- [ ] Add visible parent prompts
