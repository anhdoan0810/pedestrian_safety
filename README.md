Only Head --> can't find the model of legform (lower, upper) 
Child, aldult --> regulation and evaluation protocol

# pedestrian_safety
Dynamic_relaxation

- is a useful feature for achieving a quasi-static solution in a dynamic simulation. It helps to bring a structure to equilibrium under applied loads before starting the actual transient or dynamic analysis. This is especially handy when you're simulating problems where initial load application causes unwanted vibrations or kinetic energy.

-💡 What is Dynamic Relaxation?
- DYNAMIC_RELAXATION is a numerical damping technique. It lets the model "settle" into a static equilibrium state by artificially damping out kinetic energy over time. It's commonly used to:

- Stabilize contact before the actual simulation begins

- Preload a structure before dynamic analysis

- Avoid transients from initial load application
- Appication:

- Seating simulations: Let contact forces stabilize before head/leg impact.

- Crash simulations with initial preload or bolt tension.

- Geometric nonlinearities: Let initial deformation equilibrate.
