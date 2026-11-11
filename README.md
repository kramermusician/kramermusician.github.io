# Teaching hub

The front door for every Berklee course site: `https://kramermusician.github.io/`.
Repo `kramermusician/kramermusician.github.io` (a GitHub user site, so it serves at the root).
The course sites stay in their own repos and keep their own addresses under it
(`/lens101/`, `/berklee-esl/`, `/lhum400/`, `/daily-graphs/`), so no existing link breaks.

- One self-contained `index.html`, no build step.
- `img/` holds screenshots of each live site. Refresh them when a site changes a lot.
- New course or new semester: add a `<li>` door in `index.html` (copy one), add its screenshot to `img/`, push.
- Past semesters go in the "Also" row with the code "Archive".
