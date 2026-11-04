# LA-LQR project page

Static project website for *Activation Steering of Video Generation Models via Reduced-Order
Linear Optimal Control* (LA-LQR). Served with GitHub Pages from the repository root.

- `index.html`, `style.css`: the page (no build step, no external dependencies).
- `assets/video/`: unsteered / LA-LQR steered pairs shown on the page
  (`<model>_<category>_<n>_{unsteered,steered}.mp4`).
- `assets/img/lab_logo.png`: lab logo.

The page carries a content warning: the videos are generated from harmful benchmark
prompts. Unsteered videos are blurred until the reader clicks *Reveal* and every prompt is
collapsed by default.

To add a Wan2.1 example, copy one `.video-model-block` in `index.html`, point the two
`<video>` tags at new files under `assets/video/`, and paste the prompt into the
`<details class="prompt">` block.
