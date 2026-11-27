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

## HTML formatting

Run `npm ci` once, then `npm run format` to format both HTML pages with Prettier. Use `npm run format:check` to check formatting. Shared rules are in `.prettierrc.json`.

## Interaction section

The original `nora_interaction_section` materials (GIFs, captions, and section markup) were created by [YJK (@kimyoonjai000-bit)](https://github.com/kimyoonjai000-bit). They are integrated into both pages under `id="interactions"`; shared GIFs are stored in `static/images/interactions/`. The temporary source and preview folder was removed after integration.

## Project resources

- [Code and report (main)](https://github.com/tom020723/Artificial-Intelligence-and-Control-for-Autonomous-Driving/tree/main).
- [Nohyeong-AV on Hugging Face](https://huggingface.co/datasets/skku-av-team7/Nohyeong-AV): 10,000,262 PPO transitions, 62,457 episodes, 32 batches; CC BY 4.0.
- The BC pretraining set contains 98,759,227 IDM state–action pairs. It is separate from the public PPO rollouts.
- The selected PPO checkpoint is iteration 60: 97.21% success on 7,050 test cases, with junction collisions counted (BC: 90.79%).

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
