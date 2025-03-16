# Astropy Observing Plan

This demonstrates the use of the [Astropy library](https://www.astropy.org/) in Python to calculate the [altitude and azimuth](https://www.timeanddate.com/astronomy/horizontal-coordinate-system.html) of several bright objects during an [observing program at the Garber Nature Center](https://preblecountyparks.org/events) in Lewisburg, Ohio on April 5, 2025.

You can view the notebook [here](altitude_azimuth.ipynb).

## Setup

Install [uv](https://docs.astral.sh/uv/), if you haven't already.  After cloning, create a virtual environment and sync the packages:

```bash
uv venv

uv sync
```

You'll need a Jupyter environment in order to work with the altitude_azimuth.ipynb notebook.  The quickest way to do this is with [VS Code](https://code.visualstudio.com/) and the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).
