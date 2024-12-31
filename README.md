# Plane on Conveyour Belt
Like the classic question.

All work is currently in the design.ipynb notebook while I develop out the main pieces.

This simulation has:
- Solving ODEs derived from Newton's 2nd Law to solve for positions and velocities
- Variable time steps
- Algrebraic states are calculated again in post processing to not burden the integration loop with logging of them during solving
- A terminal event that ends integration before the t_final (crash)
- An animation made in post processing to play the solution at wall clock speed