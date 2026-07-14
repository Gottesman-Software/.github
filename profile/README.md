# Gottesman Software

**Research software for photonic quantum circuit design, quantum error-correction evidence, and lab-facing control prototypes.**

Gottesman Software is a university research-group initiative building a connected software stack for moving photonic quantum ideas from simulation, to decoder evidence, to controlled laboratory validation.

The work is organized around one principle:

> A quantum-computing claim is not mature until the artifact, decoder path, benchmark, and validation boundary can be inspected.

## Software Stack

| Layer | Repository | Role | Current Focus |
| --- | --- | --- | --- |
| Design and simulation | [SchroSIM](https://github.com/Gottesman-Software/SchroSIM) | Photonic circuit design, backend-aware simulation, tracing, and validation | Continuous-variable photonic circuits, runtime artifacts, benchmark gates |
| Decoding and evidence | [LiDMaS+ / lidmas_cpp](https://github.com/Gottesman-Software/lidmas_cpp) | Quantum error-correction simulation, decoder benchmarking, hardware-to-decoder replay | Surface-code, GKP, hybrid CV-DV, decoder comparison, paper-run workflows |
| Lab control boundary | [Photon-QDrivers](https://github.com/Gottesman-Software/photon-qdrivers) | Photonic workload control across emulators, native runtimes, FPGA paths, and hardware adapters | Runtime jobs, mailbox contracts, Red Pitaya loopback, detector-emulator validation |

## Research Areas

- Photonic quantum circuit simulation
- Continuous-variable and hybrid CV-DV quantum error correction
- GKP digitization and surface-code threshold studies
- Decoder comparison and hardware-to-decoder replay
- FPGA and Red Pitaya based laboratory control boundaries
- Reproducible research software for quantum experiments

## Collaboration

We welcome research collaboration with universities, laboratories, photonics groups, quantum hardware teams, semiconductor groups, and research-software engineers.

Useful collaboration paths include:

- co-writing grant proposals around a defined software or validation artifact;
- hosting visiting researchers or student research modules;
- contributing benchmark datasets, detector traces, or hardware-style records;
- supporting postdoctoral, graduate, undergraduate, or research-software roles;
- reviewing claims, documentation, and reproducibility packages.

## Boundary

> Gottesman Software is currently a research-group software effort. Public repositories, papers, and demonstrations should not be read as claims of complete photonic quantum hardware access unless a result is explicitly labeled as partner-lab hardware evidence.

## Contact

For collaboration, research roles, or proposal discussions:

**Dennis Wayo**  
`dwayo3@gatech.edu`
