![Mechanical design and simulation. A schematic cross-section shows the clearance between a shaft and bore.](assets/engineering-banner.svg)

## About me

I'm Isath, a student interested in mechanical engineering and vehicle design. In Formula 1, I'm especially interested in how aerodynamics affect vehicle performance and how parts behave under load.

I use SOLIDWORKS to model parts and assemblies, and Python to test design assumptions with calculations and simulation. Right now I'm working on dimensional tolerance analysis and rover terrain traversal.

## Selected achievements

- **NASA Space Apps 2026, Periapsis.** Implemented backend ranking for 196,608 Mars grid cells. My terrain screening and planning-run reporting contributions also merged into the team repository. [Cell ranking](https://github.com/AbhimanthaW/Periapsis/pull/18) · [Terrain screening](https://github.com/AbhimanthaW/Periapsis/pull/24) · [Run reporting](https://github.com/AbhimanthaW/Periapsis/pull/36)
- **StackOpt.** Built a dimensional tolerance CLI with read-only CAD extraction and offline replay. All 84 tests passed on Windows and Ubuntu across Python 3.11, 3.12 and 3.13. [Test run](https://github.com/isathinsitha/stackopt/actions/runs/44128744463)
- **Edexcel International GCSEs.** Completed Mathematics, Physics, Chemistry, Biology, English Language, Commerce and Computer Science.

## Design and analysis

### [StackOpt](https://github.com/isathinsitha/stackopt)

A Python tool for checking worst-case clearance and choosing among specified drawing tolerances. It reads bound dimensions from SOLIDWORKS or FreeCAD and saves the inputs for offline replay.

In the synthetic bore-and-shaft example, tightening just the bore tolerance from **±25 µm to ±15 µm** recovers **10.0092 µm of upper clearance margin**. The next check is to use it on a representative assembly with a real drawing decision. [Worked example](https://github.com/isathinsitha/stackopt/tree/main/examples/acceptance-v1) · [Solver architecture](https://github.com/isathinsitha/stackopt/blob/main/ARCHITECTURE.md)

## Rover engineering

### [Periapsis · NASA Space Apps](https://github.com/AbhimanthaW/Periapsis)

A team project on Mars rover mission planning. It brings landing-area screening and traverse planning into the same workflow.

I'm also working on a separate [rover CAD and simulation project](https://github.com/isathinsitha/RoverSimulation) focused on terrain traversal.

## Motorsport data

### [Apex Pulse](https://github.com/isathinsitha/Apex-Pulse-F1-viewer)

An OpenF1 dashboard for replaying driver positions and comparing historical lap and telemetry data.
