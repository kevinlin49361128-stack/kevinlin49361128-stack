# Kevin Lin

> Domain-rigorous apps across **astronomy, music, and finance** — where the
> underlying physics, music theory, or market data is real, not faked.

Software engineer based in Taiwan. Amateur violinist. I build tools for the
domains I actually care about and ship them with the same finish as commercial
products: notarized installers, live demos, test suites, real release tags.

---

## Featured projects

### 🪐 [Solar System 3D](https://github.com/kevinlin49361128-stack/solar-system-3d) &nbsp;·&nbsp; browser 3D astronomy simulator

Real NASA J2000 orbital mechanics with a Newton-Raphson Kepler solver and an
optional Yoshida-4 N-body integrator. Three viewing tiers (solar system → 50 ly
neighbourhood → galactic disc) with seamless transitions. Observer mode renders
the sky with Hosek-Wilkie atmospheric scattering, applies stellar proper motion
+ annual aberration, and computes magnetic declination so the AR gyro compass
shows true north. INDI / ASCOM telescope bridge for amateur scopes.

**Live demo:** <https://solar-system-3d-kappa.vercel.app/>
**Stack:** Three.js · TypeScript · Vite · WebGL2 · 327 tests, MIT

---

### 🎼 [Score Arranger](https://github.com/kevinlin49361128-stack/score-arranger) &nbsp;·&nbsp; intelligent orchestral-score arranger (macOS)

Desktop app that arranges full orchestral scores into smaller ensembles —
string quartet, violin + piano, solo piano, etc. Constraint-based voice
allocation + a directed-repair loop, plus playability checks (range,
double-stops, bow patterns) that a real musician would actually catch.
Human-AI collaboration; not full automation. Apple-notarized `.dmg`.

**Project page:** <https://kevinlin49361128-stack.github.io/score-arranger-web/>
**Stack:** Electron · React · TypeScript · Python (music21) · OSMD · GPLv3

---

### 📈 [Stock Analyzer + MCP](https://github.com/kevinlin49361128-stack/stock-analyzer-mcp) &nbsp;·&nbsp; Taiwan + US market research

macOS app + MCP server with 81 tools covering Taiwan (TWSE / TPEx) and US
markets — institutional flow, chip data, technical indicators, backtests,
DCF, sentiment. Local SQLite, BYOK LLM. First MCP server with full
Taiwan-market coverage.

**Stack:** Electron · TypeScript · Python · SQLite · MCP

---

## A note on the through-line

Astronomy, music, and finance look unrelated, but they share a constraint:
**the domain rigor has to be real**. A toy demo that fakes the orbits, the
playability rules, or the market microstructure breaks at first use. I prefer
to do the work that makes the domain part actually correct, then ship the
polish around it.

The music projects come from being an amateur violinist — Score Arranger and
[Concerto Manager Lite](https://github.com/kevinlin49361128-stack/concerto-manager-lite)
are tools I wished existed for the rehearsals and chamber-music groups I play in.

---

## Currently shipping

- **Solar System 3D `v0.8.0`** — see the [release notes](https://github.com/kevinlin49361128-stack/solar-system-3d/releases/tag/v0.8.0)
- **Score Arranger** — public macOS release; web landing for download
- More on [my repositories →](https://github.com/kevinlin49361128-stack?tab=repositories)

## Contact

Open an issue or discussion on any of the projects above — that's the fastest
way to reach me. Email is on my GitHub profile.
