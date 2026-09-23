# Nicholas Foley

PhD student in Computer Science at the University of Texas at San Antonio · Marine Corps veteran · San Antonio, TX

I'm in the Vision and AI Lab (VAIL) at UTSA, advised by Dr. Amanda Fernandez. My research is in geometric deep learning, mostly neural networks built on quaternion and other hypercomplex (Clifford) algebras. Current work covers attention over spherical lattices, spherical graph neural networks, and visual place recognition, with an eye toward layers that run efficiently on edge hardware.

Before the PhD I worked in the CloudSys Lab with Dr. Palden Lama on distributed inference: splitting CNNs across Raspberry Pi and Jetson clusters and measuring where a split actually pays off. I also take on applied ML contract work through Foresyth Foley LLC.

## Publications

- A. Masud, **N. Foley**, P. D. Rajarajan, P. Lama. [Where to Split? A Pareto-Front Analysis of DNN Partitioning for Edge Inference](https://arxiv.org/abs/2601.08025). *IEEE EdgeCom 2025*. [[code]](https://github.com/cloudsyslab/ParetoPipe)

Work on quaternion attention for vision is currently under review.

## Projects

- **[firmament](https://github.com/Foley-ops/firmament)** (Python): A hands-off world simulator with real physics, exact conservation, and bit-identical replay. Built in phases, each gated by its own acceptance tests.
- **[mtg-deck-builder](https://github.com/Foley-ops/mtg-deck-builder)** (Python, PyTorch Geometric): Builds Magic: The Gathering Commander decks from a graph neural network trained on real play data, then applies bracket rules, budget limits, and your own collection. CLI and browser UI.
- **[cutoffarr](https://github.com/Foley-ops/cutoffarr)** (Go): A small service that unmonitors Radarr/Sonarr items once they meet their quality profile, so indexers stop getting queried for upgrades that don't exist. Dry-run by default and never deletes anything.
- **[distributed-inference](https://github.com/Foley-ops/distributed-inference)** (Python, PyTorch): Pipelined DNN inference across a Raspberry Pi cluster over PyTorch RPC. Profiles each layer to pick split points and gets about 6.4x the throughput of a sequential baseline.

Earlier edge and cluster work: [distributed-dnn-inference-pi](https://github.com/Foley-ops/distributed-dnn-inference-pi), [DeepLabv3-VOS](https://github.com/Foley-ops/DeepLabv3-VOS), [YOLOv8-Vehicle-Analysis](https://github.com/Foley-ops/YOLOv8-Vehicle-Analysis), [raspberrypi-lab-setup](https://github.com/Foley-ops/raspberrypi-lab-setup), [Pi-Cluster-SSH-Manager](https://github.com/Foley-ops/Pi-Cluster-SSH-Manager).

## Tools

**Languages:** Python, Go, Rust, Bash, SQL, LaTeX  
**ML:** PyTorch, PyTorch Geometric, Weights & Biases, Ollama  
**Infrastructure:** Linux, Docker, Ansible, GitHub Actions, Grafana, Unraid  
**Databases:** PostgreSQL, MySQL, SQLite  
**Hardware:** NVIDIA Jetson, Raspberry Pi, Arduino  
**Other:** Flask, Qiskit, Neovim

## Education

- **Ph.D., Computer Science**, University of Texas at San Antonio (2026 to present)
- **B.S., Computer Science**, University of Texas at San Antonio (2025)
- UTSA School of Data Science Undergraduate Research Fellowship, inaugural cohort (2025)

## Contact

[LinkedIn](https://www.linkedin.com/in/nicholasmfoley)
