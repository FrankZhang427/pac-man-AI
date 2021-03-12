# pac-man-AI

This is a 2D Pac-Man game where two agents compete with each other.
One of the agents is controlled by the player (```WASD``` to move and ```space``` to teleport trap),
and the other one is controlled by game AI.
Simple enemies patrol the corridor area to catch both agents.
Each agent has two teleport traps, when used, the closest enemy or agent is selected, and immediately moved to a random room (agent),
or de-and-re-spawned (enemy). The AI agent is controlled through a [hierarchical task network (HTN)](https://en.wikipedia.org/wiki/Hierarchical_task_network).
The HTN design of AI agent is documented [here](https://frankzhang427.github.io/pdf/HTN.pdf).
More detailed game design can be found [here](https://frankzhang427.github.io/pdf/pac-man_AI.pdf).
