# NetSysLab
netsys = "networks + distributed systems" lab = a place for experiments, examples, and tools

## Repository Structure

This repository serves as a meta repository for network infrastructure management and system administration tools:

```
NetSysLab/
└── tunnel/ (submodule)
    ├── newt/          # Submodule: Network configuration and management tools
    ├── pangolin/      # Submodule: Pangolin tunnel configuration and utilities
    └── cloudflare/    # Directory: Cloudflare tunnel configurations and scripts
```

## Getting Started

To clone this repository with all submodules:
```bash
git clone --recursive https://github.com/hellbruh/NetSysLab.git
```

Or if already cloned, initialize submodules:
```bash
git submodule init && git submodule update
```
