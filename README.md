# Plume

**Seed life under the ice. Could a probe tell?**

### ▶ [Play it free in your browser](https://etcyl.github.io/plume-play/)

![Enceladus, its south-pole plume and Saturn, from the opening of Plume](docs/splash.jpg)

Plume is a free strategy game about one of the biggest open questions in planetary science: if
something lived in the ocean under an icy moon, could a spacecraft flying through its spray
actually detect it?

You release Earth microbes at hydrothermal vents on the seafloor of Enceladus, help them adapt by
evolving traits and steering their mutations, and try to make their chemical signal strong enough
in the plume for a passing probe to report life. That report has to hold up when a review panel
asks whether rock chemistry alone could explain it.

No download or account needed. Plume runs in a desktop browser (Chrome, Edge, Firefox or Safari)
with a mouse and keyboard.

## The science behind it

Plume is inspired by research published in *Science Advances* in September 2026:

- **Helmbrecht et al. (2026).** A methane-making microbe from deep-sea vents,
  *Methanothermococcus okinawensis*, grew in a lab recreation of Enceladus's ocean at up to pH 11,
  living on hydrogen from simulated rock–water reactions.
  [doi:10.1126/sciadv.aei0167](https://doi.org/10.1126/sciadv.aei0167)
- **Postberg et al. (2026).** Cassini's dust analyser shows the plume's ice grains freeze slowly
  and separate by composition, so a single grain could carry a concentrated signal.
  [doi:10.1126/sciadv.aee7256](https://doi.org/10.1126/sciadv.aee7256)
- News coverage: Ian Sample,
  [Earth microbes survive simulated conditions of Saturn moon's ocean](https://www.theguardian.com/science/2026/sep/25/earth-microbes-survive-conditions-enceladus-saturn-moon-ocean-study),
  *The Guardian*, 25 September 2026.

Neither paper is evidence of life on Enceladus. The game asks what it would take to detect it if
it were there.

Under the hood, the ocean runs a real chemical reaction network: every reaction is checked for
atom and charge balance, and microbes only grow where the reaction releases enough energy. The
probe reads the same clues scientists have proposed for Enceladus: methane relative to hydrogen,
missing hydrogen, carbon isotopes, methane versus ethane, and cells in ice grains. The in-game
**Science notes** say what is modelled from real data and what is simplified for play.

## What you'll do

![Gameplay: vents, colonies, the probe's instruments and the next-step guide](docs/gameplay.jpg)

- **Seed** cultures at warm, hydrogen-rich vents.
- **Evolve** traits with points from sample bubbles, and steer which mutations win.
- **Survive** phages that hunt your most common strain, vents that fade, and ice-methane bursts
  that can fool the probe.
- **Get detected:** push the probe's confidence to 70% by the flyby, then face the review panel.

Four missions (Enceladus, Europa and two hypothetical oceans), plus a Sandbox Lab where you design
your own metabolism, Survival Trials on a realistic Europa, and Plume Studio for building and
sharing scenarios.

| | |
|---|---|
| ![The UV lamp makes methanogens glow from their F420 coenzyme](docs/uv.jpg) | ![The live reaction network](docs/network.jpg) |
| UV lamp: methanogens glow (F420 fluorescence) | The reaction network running underneath |
| ![How it works: the chain from vent to probe](docs/how-it-works.jpg) | ![The flyby mass spectrum](docs/spectrum.jpg) |
| How it works (press G) | The flyby's mass spectrum |

## Tips

- New players get a short tutorial, and a **Next step** banner always says what to do and why.
- Press **G** for a live diagram of the whole chain, from vent to probe.
- Press **H** for help, **Esc** for the menu and settings.
- Slow? Press **F3** to see your frame rate and which graphics card the browser is using. Settings
  has graphics quality and automatic resolution.

## Credits

Made by [instructions unclear](https://github.com/etcyl). Built with Unity.

- Enceladus map: Cassini global mosaic (NASA/JPL-Caltech/Space Science Institute, compiled by
  USGS Astrogeology; public domain). Europa and Ganymede maps: NASA/JPL-Caltech (public domain).
- Saturn, its rings, Jupiter and Neptune: [Solar System Scope](https://www.solarsystemscope.com/),
  CC BY 4.0.

This repository hosts the playable web build only.
