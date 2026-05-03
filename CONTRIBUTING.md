# Contributing

## Optional word lists (`content/bundle.json`)

Adding `phonicWords` through the optional JSON bundle speeds up authoring, but cultural and Australian education context matters: **never bulk-generate culturally specific content unchecked**. Rows that reference Aboriginal or Torres Strait Islander stories, landmarks, naming, children’s images, or community practices require appropriate human review alongside families and educators familiar with context.

Validate before PR or commit:

```bash
node scripts/validate-content.mjs content/bundle.json
```
