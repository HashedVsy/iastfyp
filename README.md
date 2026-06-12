# iastfyp

A configurable entity simulation tool designed for system performance
testing, memory behavior analysis, and virtual machine workload
evaluation.

------------------------------------------------------------------------

## Overview

iastfyp generates large-scale simulated environments consisting of
moving entities ("turties") to create controlled computational load. It
is designed for experimentation, benchmarking, and compatibility testing
across different systems and virtualized environments.

The simulation is intentionally flexible: users can scale entity count
and simulation speed to explore system limits.

------------------------------------------------------------------------

## Key Features

-   Configurable entity count and simulation speed
-   Spatial grid optimization for efficient proximity calculations
-   Scales from a few thousand to hundreds of thousands of entities
-   Useful for CPU, memory, and VM behavior testing
-   Cross-platform support (Windows, Linux)

------------------------------------------------------------------------

## How It Works

iastfyp uses a spatial grid system to reduce interaction complexity
between entities.

Instead of comparing every entity with every other entity (O(n²)),
entities are grouped into grid cells so that only nearby interactions
are evaluated. This significantly improves performance in large
simulations.

------------------------------------------------------------------------

## Usage

Run the program:

``` bash
python iastfyp.py
```

Or execute the compiled binary (if available).

------------------------------------------------------------------------

## Configuration

Typical configurable parameters:

-   Entity count (e.g. 5,000 → 500,000+)
-   Simulation speed multiplier
-   Spawn density
-   Interaction rules (if enabled in build)

------------------------------------------------------------------------

## Performance Notes

Performance depends heavily on:

-   CPU single-thread performance
-   Memory bandwidth
-   Entity count and speed multiplier

Very high configurations may cause heavy system load but should remain
stable due to the spatial grid system.

------------------------------------------------------------------------

## Warning

Large simulations may significantly impact system responsiveness. Use
high settings carefully, especially on virtual machines or low-power
hardware.

------------------------------------------------------------------------

## Project Origin

iastfyp originally began as a simple simulation experiment and evolved
into a lightweight workload generation tool for system testing and
exploration.

------------------------------------------------------------------------

## License

The License has changed from MIT to GPL.
ALL VERSIONS BEFORE v1.1.1 IS MIT. NOT GPL!