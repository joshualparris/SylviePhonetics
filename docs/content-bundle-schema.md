# Optional content bundle (`content/bundle.json`)

The app optionally fetches `./content/bundle.json` **after initial load**. If missing (e.g. `file://`) or invalid, bundled words are used unchanged.

## Root shape

| Field | Type | Required |
|-------|------|----------|
| `phonicWords` | array | yes |

Other keys are ignored today but may extend later (`letterLab`, …).

## `phonicWords[]` entries

Each object MUST include:

- `word` (string): lower-case target word (`"sun"`).
- `letters` (string[]): graphemes mapped to pronunciation for simple CVC work (`["s","u","n"]`).

Recommended:

- `emoji` (string): display glyph.
- `promptWord` (string): optional speech/display variant.
- `difficulty` (number): 1–18; filters by literacy age picker.

Example:

```json
{
  "phonicWords": [
    { "word": "sun", "emoji": "☀️", "letters": ["s", "u", "n"], "promptWord": "sun", "difficulty": 1 }
  ]
}
```

## Cultural safety

Treat every added row like curriculum content: culturally appropriate review by humans—not bulk LLM-fill. Respect Aboriginal and Torres Strait Islander perspectives; seek community guidance before publishing themed assets.
