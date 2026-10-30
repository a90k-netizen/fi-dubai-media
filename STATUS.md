stage: Live
summary: Public hosting repo for the "fi dubai." monthly videos. Metricool needs a public URL for each MP4, so the Dubai-WhatsOn pipeline pushes each month's 8 videos here (folders 2026-11 and nov-2026) and checks the raw.githubusercontent.com links. It holds media only, no code.
next: Nothing to do by hand. The Dubai-WhatsOn pipeline adds next month's videos here; give a session push access to this repo when it runs
blockers: None

Last reviewed: 30 October 2026, from the files and the Dubai-WhatsOn docs (docs/13-automation.md).

## Notes

- Keep this repo, and keep it public. Scheduled posts and Metricool may re-fetch these URLs.
- The November videos exist in two folders: `nov-2026/` (the first upload, including the v2 adults videos with the price fix) and `2026-11/` (the folder name the `host-media.sh` script uses; it has no families_en file). The repo does not say which folder the scheduled posts point to. Check Metricool before removing either.
- Large video files make the repo grow (about 350 MB so far). If it ever hits GitHub limits, move older months out once their posts have published.
