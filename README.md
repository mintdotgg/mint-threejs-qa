# Mint Three.js QA

Use these skills to reproduce rendering defects and verify Three.js scenes before sharing them. The debugger walks through loading, lighting, resize, input, animation, and measured performance. The release verifier covers the primary journey, loading and error states, asset paths, and the production build.

Try asking Claude to reproduce a blank model viewer, diagnose an animation that disappears after resize, or verify the primary journey in an interactive world. The skills work on your local project and operate within the QA scope you request.

The skills can run your project's build and test commands. With your approval, the optional canvas inspector uses the project's `@playwright/test` and `pngjs` dependencies to open the URL you supply. It saves a screenshot and a JSON report with canvas measurements and browser errors in `artifacts/canvas-inspection` by default. The plugin includes no telemetry client or upload step.

Source skills are from [Mint Three.js Skills](https://github.com/mintdotgg/mint-threejs-skills/tree/de7af448ee6f90ab54c53b6a18d58581bbc56a90). For examples to explore, see [Mint Playground's Three.js examples](https://play.mint.gg/threejs-examples).
