# Plane on Conveyour Belt
 Like the classic question

Simulation step size is variable. Render is made in post processing to play solution in "real time" (not simulated live but renders data at wall clock speed)

This simulation has:
- Integration of acceleration ODEs to solve for positions and velocities
- A terminal event that ends integration before the t_final (crash)