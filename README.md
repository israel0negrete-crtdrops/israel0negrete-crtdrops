# Israel Negrete Lepe · lab notebook

Electronics engineer. Twenty-five years making different systems work together
under real conditions: from the sensor, the vehicle or the transaction to the
backend, the data, security and operations. Today, increasingly, edge AI.

**This account is a lab notebook.** Everything here is experimental: small
setups on modest hardware (a Raspberry Pi 5, a Pi Zero 2 W, an Intel N100),
each one with its code, its raw data and a note that explains what was
measured and what wasn't. Nothing here is production code, and nothing comes
from a client.

## Experiments

| Repository | What it measures | Note |
|---|---|---|
| [geofence-on-the-fly](https://github.com/israel0negrete-crtdrops/geofence-on-the-fly) | A simulated week of a truck against geofences: false alerts and missed entries for five ways of deciding inside or outside | [The geofence on the fly](https://crtdrops.mx/notas/the-geofence-on-the-fly.html) |
| [latency-percentiles](https://github.com/israel0negrete-crtdrops/latency-percentiles) | p50, p95 and p99 per phase, with timeouts treated as censored, over 90,604 real inferences on a Pi 5 and an N100 | [The average that never happened](https://crtdrops.mx/notas/the-average-that-never-happened.html) |
| [ghosts-in-the-frame](https://github.com/israel0negrete-crtdrops/ghosts-in-the-frame) | 2001 window filters in C against two vision models running locally on an N100, looking for the same disk in haunted frames | [Ghosts in the frame](https://crtdrops.mx/notas/ghosts-in-the-frame.html) |
| [night-shift](https://github.com/israel0negrete-crtdrops/night-shift) | A local Gemma model reads the lab's logs at night and writes a 7 a.m. report; where it makes things up | [Night shift](https://crtdrops.mx/notas/night-shift.html) |
| [cube-state-solver](https://github.com/israel0negrete-crtdrops/cube-state-solver) | Whether a 3 × 3 cube state can exist, and two ways to solve it: two-phase (20 moves or fewer) and in stages, the way a person does it | [The tool, live](https://crtdrops.mx/taller/cubo/) |

*One new experiment a week. Notes in English and Spanish at
[crtdrops.mx](https://crtdrops.mx/notas/).*

## Rules of the notebook

- Measured on real hardware, or it says it wasn't.
- The raw data goes with the code.
- What isn't verified is said.

I take on projects by the hour or by deliverable:
[israel0negrete@gmail.com](mailto:israel0negrete@gmail.com).
