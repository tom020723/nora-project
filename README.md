# NORA

NOhyeong, Jeju — Reinforcement-learning Autonomous driving in SUMO

[Visit the NORA project page](https://tom020723.github.io/nora-project/)

## NORA language pages

- `index.html`: Korean (default landing page).
- `index.en.html`: English.
- Use the language menu at the top right to switch between pages.
- Edit each HTML file separately when updating translated text. Keep section IDs consistent between the two files.
- Both pages share `static/css/index.css`, `static/js/index.js`, and the same media assets under `static/`.
- GitHub Pages serves `index.html` by default; no redirect or build step is needed.

## Content sources

- Project text, metrics, and report figures follow the [`final3` snapshot `584919d`](https://github.com/tom020723/Artificial-Intelligence-and-Control-for-Autonomous-Driving/tree/584919da260bed37cc2bc48a307274393002df7e).
- `static/images/final3-*.png` are copied from that snapshot's `docs/report/figures/`; source links are included on both pages.
- Headline results count junction collisions: BC 90.79%, BC → Anchored PPO 96.84%, each over 7,050 test cases. Training data statistics describe the repository's final BC dataset, independently of the contents currently hosted on Hugging Face.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
