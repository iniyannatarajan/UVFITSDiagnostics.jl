# UVFITSDiagnostics.jl

This repository contains notebooks for generating diagnostic plots from UVFITS files. For maximum interactivity, use [Pluto.jl](https://plutojl.org/).

## Quickstart

Clone this repository from GitHub and start Julia REPL from within by:

```bash
julia # option 1: if Pluto.jl is already installed in your default environment (or)
julia --project=. # option 2: if you do not want to install Pluto.jl in your default environment
```

For option 2 above, the following step is needed once inside the REPL:
```julia
] instantiate
```
This can be skipped for option 1.

Once `Pluto.jl` has been installed, running the following steps will open a browser tab from which a new or existing notebook can be opened:
```julia
using Pluto
Pluto.run()
```