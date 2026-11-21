# Google Dorking — field notes

Operators I demo:
- `site:` — restrict to a domain            e.g. `site:github.com`
- `intitle:` / `inurl:` — words in title/URL
- `filetype:` — specific extensions         e.g. `filetype:txt`
- `"exact phrase"` — quotes force the match
- `-word` — exclude a term

Live examples:
- `site:github.com maruf-cyberlab`          <- find my work
- `"CSCLUB{" site:github.com`             <- flags leak when people commit them
- `inurl:recon filetype:txt`                <- stray notes

Lesson: attackers find you before they touch your network. Clean up what you publish.
<!-- player hint: one flag is sitting in this repo, lightly encoded. another is
     hiding *inside* a file, not in the text. think metadata -> steghide. -->
