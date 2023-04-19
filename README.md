# Smoothed Particle Hydrodynamics (SPH) Two-Phase Bubble Fluid Simulation with WebGL

**See a live demo here:** https://sweet-pixie-695a4b.netlify.app/

- For COMP 559 @ McGill University.
- Implementation of a two-phase SPH fluid, with buoyancy, cohesion and drag forces on the light air.
- By default, it simulates turbulent airflow and the creation of bubbles in water (bottom fluid).
- Based on https://cg.informatik.uni-freiburg.de/publications/2011_GRAPP_airBubbles.pdf by Markus Ihmsen et al.
- Responds to mouse movement on desktop, and touch input on mobile.
- Please use a browser that supports WebGL (like Google Chrome).

If you'd like to run the code locally on your computer, follow these steps on a command line interface:
- `git clone https://github.com/RiccLQL/COMP559-Bubble-SPH`
- `cd COMP559-Bubble-SPH`
- `npm install http-server -g`
- Make sure you are in the folder of the index.html file, and run `http-server` in the terminal.

Alternatively, you can use the Live Server extension on VS Code.


**Credits:** Templated from a one-phase SPH fluid simulation from https://github.com/mjwatkins2/WebGL-SPH.
