# Attention — Kickoff Page Notes

Notes for the opening section of the internal project codenamed **Attention** — the two most famous attention artifacts.

## Source 1 — The internet's favorite attention bait: Rick Astley, "Never Gonna Give You Up"

- **Source link:** https://www.youtube.com/watch?v=dQw4w9WgXcQ
- **Source id (logging tag):** `yt_dQw4w9WgXcQ`
- **Full title (exactly as it comes back together with the transcript):** Rick Astley - Never Gonna Give You Up (Official Video) (4K Remaster) - YouTube
  (the transcript tool returns the title line as `# Rick Astley - Never Gonna Give You Up (Official Video) (4K Remaster) - YouTube`; the video's own title is *Rick Astley - Never Gonna Give You Up (Official Video) (4K Remaster)* — the trailing `- YouTube` is the site suffix appended by the tool)
- **Opening lyric line (verbatim from the transcript):** "We're no strangers to love"
  (the transcript renders the line as `♪ We're no strangers to love ♪`)

## Source 2 — The paper that made 'attention' the word of the decade: "Attention Is All You Need"

- **Source link:** https://arxiv.org/abs/1706.03762
- **Source id (logging tag):** `arxiv_1706.03762`
- **Architecture (one sentence, from the abstract):** "We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely."
- **WMT 2014 English-to-German BLEU (from the abstract):** 28.4 BLEU (improving over the existing best results, including ensembles, by over 2 BLEU)
- **WMT 2014 English-to-French BLEU (from the abstract):** 41.8 (a new single-model state-of-the-art BLEU score, after training for 3.5 days on eight GPUs)

## Publishing note

These notes were intended for a GitHub gist (`attention-kb-notes.md`). Gist creation failed with `403 Resource not accessible by personal access token` — the current GitHub token lacks the gist scope — so the file is published here in the org repo instead, where the team can comment via issues and PRs. If a true gist is required, the token needs the `gist` scope.
