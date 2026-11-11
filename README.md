# Lekh assets

Static files the Lekh apps download at runtime, published by GitHub Pages from
`main` at https://assets.lekh.app/:

- `stencils/vN/`: the shape libraries. A released folder is never edited; a change
  makes the next `vN`.
- `fonts/noto/`: the Noto script fonts the web PDF export downloads on demand.

A push to `main` publishes. Run the checks in `tools/README.md` before every push.
