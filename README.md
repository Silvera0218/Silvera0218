### Hi, I'm Silvera.

I am a Master's student in Mathematics at the University of Macau, specializing in **Elliptic Equations (PDEs)**, specifically focusing on problems of the **De Giorgi type**. My path to mathematics was interdisciplinary; **before my undergraduate studies in math**, I studied **Food Science, Biology, and Bioinformatics**.

Beyond my core research, I am an enthusiast of **Fluid Dynamics, Differential Geometry, and General Relativity**. My main passion is bridging the gap between complex mathematical theory and real-time, interactive visualization.

-  I’m interested in physically-accurate simulations of astrophysical phenomena and science fiction concept realizations.
-  I’m self-learning **GLSL** and **ModernGL** to trace light through curved spacetime.
-  How to reach me: [mc45151@um.edu.mo]

<br />

---

### Featured Astrophysical Simulations

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">1. Interactive Kerr Black Hole Simulator</h3>
      <br />
      <a href="https://github.com/Silvera0218/BlackHole-Simulation">
        <img src="https://raw.githubusercontent.com/Silvera0218/BlackHole-Simulation/main/gif/blackhole_recording0.gif" alt="Kerr Black Hole Simulator" />
      </a>
      <br />
      <p>
        A real-time simulation of both Schwarzschild (static) and Kerr (rotating) black holes. It accurately demonstrates key General Relativity phenomena by performing numerical integration (4th-Order Runge-Kutta) on the GPU:
      </p>
      <ul>
        <li><b>Gravitational Lensing</b>: Distorts the background starfield.</li>
        <li><b>Frame-Dragging</b>: The "spacetime vortex" effect of the rotating Kerr hole.</li>
        <li><b>Relativistic Doppler Beaming</b>: The bright approaching vs. dim receding disk.</li>
        <li><b>The Photon Ring</b>: Delicate, nested rings of light at the shadow's edge.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">2. Real-time 3D Wormhole Ray-Tracer</h3>
      <br />
      <a href="https://github.com/Silvera0218/Real-time-3D-Wormhole-from-Visualizing-Interstellar-s-Wormhole-">
        <img src="https://raw.githubusercontent.com/Silvera0218/Real-time-3D-Wormhole-from-Visualizing-Interstellar-s-Wormhole-/main/gif_wh.gif" alt="3D Wormhole Ray-Tracer" />
      </a>
      <br />
      <p>
        A real-time traversable wormhole (Morris-Thorne metric) simulator. It performs "reverse ray-tracing" in a GLSL fragment shader for every pixel to accurately simulate the exotic visual distortions of passing through a wormhole.
      </p>
      <ul>
        <li><b>Physically-Accurate</b>: Based on the analytic model from arXiv:1502.03809.</li>
        <li><b>First-Person Traversal</b>: Full 6-DOF (six-degrees-of-freedom) camera control.</li>
        <li><b>Connects Two Universes</b>: Links two distinct "universes" (skyboxes).</li>
        <li><b>Multiple Images</b>: Renders the multiple "ghost images" visible inside the throat.</li>
      </ul>
    </td>
  </tr>
</table>

<br />

---

### Featured Computational Physics Simulations

<table>
  <tr>
    <td width="100%" valign="top">
      <h3 align="center">3. 2D Incompressible Fluid Dynamics Simulator</h3>
      <br />
      <a href="https://github.com/Silvera0218/Fluid-Dynamics-Silulation">
        <img src="https://raw.githubusercontent.com/Silvera0218/Fluid-Dynamics-Silulation/main/assets/unsteady_t11.4.png" alt="Navier-Stokes FEM Solver" />
      </a>
      <br />
      <p>
        A robust MATLAB-based solver for the 2D incompressible Navier-Stokes equations, applied to channel flow around multiple obstacles. This project demonstrates the application of advanced numerical methods to solve complex, non-linear PDEs in fluid dynamics.
      </p>
      <ul>
        <li><b>Finite Element Method</b>: Utilizes stable Taylor-Hood (P2-P1) elements for spatial discretization.</li>
        <li><b>Multiple Steady-State Solvers</b>: Implements and compares Oseen, Stokes (Picard), and Approximate Newton linearization schemes.</li>
        <li><b>Unsteady Simulation</b>: Employs a full Newton solver within each time step to accurately capture time-dependent flow.</li>
        <li><b>Captures Classic Phenomena</b>: Successfully simulates the von Kármán vortex street for low-viscosity flows.</li>
        <li><b>Globalization Strategy</b>: Integrates a backtracking line search with the Armijo condition to ensure robust convergence.</li>
      </ul>
    </td>
  </tr>
</table>

<br />

