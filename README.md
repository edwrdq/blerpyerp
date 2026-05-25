# blerpyerp

An open source constructed language, free forever.

## Structure

- `data/dictionary.json` — full word entries with English translations
- `data/morphemes.json` — roots, prefixes, and suffixes
- `data/idioms.json` — phrases with non-literal meanings

## Contributing

Want to add a word? Open a PR against `data/dictionary.json`.

Each entry follows this format:

\```json
{
  "word": "huxpl",
  "english": "there's",
  "pronunciation": "HUCKS-pul",
  "part_of_speech": "contraction",
  "definition": "Contraction meaning 'there is/there's'.",
  "morphemes": { "hux": "there", "pl": "'s / is" },
  "example": "Huxpl un problem.",
  "example_translation": "There's a problem.",
  "tags": ["contraction"],
  "added": "2026-05-25"
}
\```

Keep entries alphabetized by `word`.

## License

Public domain. Use it however you want.