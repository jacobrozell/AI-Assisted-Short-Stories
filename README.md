# AI-Assisted Short Stories

A single repository for static HTML short fiction, with **one directory per story**.

Published for [GitHub Pages](https://jacobrozell.github.io/AI-Assisted-Short-Stories/) (project site root: `index.html` lists every piece).

## Stories

| Story | Folder | Main HTML |
| --- | --- | --- |
| The Sovereign's Silence | [`sovereigns-silence/`](sovereigns-silence/) | [`sovereigns-silence/index.html`](sovereigns-silence/index.html) |
| The Anniversary | [`the-anniversary/`](the-anniversary/) | [`the-anniversary/the-anniversary.html`](the-anniversary/the-anniversary.html) |

Companion outlines and alternate drafts live beside each story in the same folder.

## How these were made

1. **Outline from the world** — Recent events fed into an LLM for a genre outline.
2. **Scrub** — Identifiable real-world detail removed so the fiction stands alone.
3. **Draft** — Story drafted from the cleaned outline.
4. **Pass** — Proofing and tightening in another model or pass.
5. **Iterate** — Plot and structure revised by hand until the draft settles.

Pipeline in short: **world → scrubbed outline → draft → proof → human iteration**.

## Local preview

From this folder:

```bash
python -m http.server 8080
```

Open `http://localhost:8080/`.

## License / use

Unless you add a `LICENSE` file, default GitHub terms apply to repo metadata only; clarify reuse of **story text** if that matters.
