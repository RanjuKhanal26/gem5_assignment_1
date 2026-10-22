# Assignment 1: GitHub Account Creation, Installing and Building gem5

## Overview
This assignment documents the setup, build, and basic simulation of the gem5
computer-system simulator, as well as the use of GitHub for version control.

## Directory contents
- `hello-world.py` : gem5 standard-library configuration script for the Hello World workload
- `environment.md` : environment / prerequisite documentation
- `build.md`       : build instructions and verification
- `logs/`          : captured terminal outputs, build logs, and simulation artifacts

## Quick start
```bash
# Build gem5 (ALL ISA target)
scons build/ALL/gem5.opt -j2

# Run the Hello World simulation
./build/ALL/gem5.opt gem5_assignment_1/hello-world.py
```

## References
- gem5 project: https://www.gem5.org/
- gem5 GitHub repository: https://github.com/gem5/gem5
- gem5 standard-library Hello World tutorial: https://www.gem5.org/documentation/gem5-stdlib/hello-world-tutorial
