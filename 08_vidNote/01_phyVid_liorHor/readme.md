# phySim

* https://open.spotify.com/episode/31XK4kvmLKBWNt3NM8iHPN?si=c52b8c3256e34664

Omniverse gives you the stage; Sensor RTX supplies realistic sensor feeds; PhysX ECS (and soon Newton) supply high-fidelity, GPU-scaled dynamics; OpenUSD keeps every layer coherent; Edify SimReady automates asset prep. Together they form NVIDIA’s blueprint for building, training and validating the next wave of robotics and industrial AI systems entirely in simulation before hitting real hardware.


Omniverse
* Cross-industry platform that glues together OpenUSD, RTX real-time ray tracing and PhysX in one SDK/cloud service.
* Becomes the “operating system” for digital-twin and robotics workflows.


Sensor RTX (EA)
* Cloud APIs that stream physically-accurate camera, lidar and radar data straight from Omniverse scenes.
* Lets AV/robot dev teams create limitless, photoreal sensor datasets instead of collecting them in the real world.

PhysX ECS
* PhysX 5 rebuilt as an Entity-Component-System running inside USD/Fabric/OmniGraph.
* Treats every rigid body, articulation or fluid as a USD component, scaling physics across GPUs and simplifying scripting. 

OpenUSD
* Universal scene graph at the heart of the stack.
* Guarantees that geometry, materials, dynamics and AI annotations stay in sync across every tool and service.

Newton engine
* open-source, differentiable physics core co-developed with DeepMind & Disney; plugs into USD.

SimReady
* Gen-AI model that auto-labels 3D assets with physical materials.
* Turns “pretty mesh” into “simulation-ready part” in seconds, feeding the layers above. 