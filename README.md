### Hi, I'm Christian 👋

I'm a Research Software Engineer at the [Princeton Neuroscience Institute](https://pni.princeton.edu/), where I write and maintain the software and infrastructure behind the NIH-funded [BRAIN CoGS](https://github.com/BrainCOGS) project. Before that I did a Ph.D. in Chemical Engineering at Penn, writing CUDA/C++ and MPI code for polymer simulations.

**What I'm working on**

- 🧠 **BRAIN CoGS data pipelines.** These are [DataJoint](https://github.com/datajoint/datajoint-python) pipelines for Neuropixels ephys and two-photon imaging: Kilosort 4 with DREDge motion correction, suite2p running on the cluster's GPUs through Slurm, and NWB export. I'm also moving the scheduling over to Airflow 3. All of this sits on a few hundred terabytes of storage that I keep in order.
- 🐭 **Lab tools.** These are the tools the lab uses every day: a Streamlit app with SSO for scheduling technicians and training rigs, the code that runs the [ViRMEn](https://github.com/BrainCOGS/ViRMEn) virtual-reality rigs, and a Raspberry Pi GUI for water delivery.
- 🗺️ **[PixelMap](https://github.com/m-beau/pixelmap).** It's a browser-based tool for designing Neuropixels channel maps. I handle the packaging, Docker, and hosting at [pixelmap.pni.princeton.edu](https://pixelmap.pni.princeton.edu), and co-authored the JOSS paper. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22850327.svg)](https://doi.org/10.5281/zenodo.22850327)
- 💰 **[Actual Budget](https://github.com/actualbudget/actual).** I'm a core contributor. I built the Budget Analysis report (category and group filters, stacked bars, CSV export), and I review PRs and triage issues.
- 🔒 **Keeping research code maintainable.** I add uv packaging, pre-commit hooks, CI, Dependabot, and secret scanning to lab repos that have never had tests.
- ⚡ **GPU ports.** I help researchers move CPU code to GPUs. At the Princeton Open Hackathons, the teams I mentored got roughly 100x speedups with Numba and 1000x with CuPy.

I also send fixes upstream to the tools I depend on, including [datajoint-python](https://github.com/datajoint/datajoint-python), [element-array-ephys](https://github.com/datajoint/element-array-ephys), [react-spectrum](https://github.com/adobe/react-spectrum), and [phy](https://github.com/cortex-lab/phy).

**Before Princeton**

At Penn I worked with a researcher at Sandia to port my lab's particle-mesh (TILD) routines into [LAMMPS](https://github.com/tabedzki/lammps). I also restructured our in-house CUDA code so we could keep adding features to it, and taught lab workshops on Rust, CUDA/Thrust, and Git.

**Tools I use most**

`Python` · `C++` · `CUDA` · `MPI` · `Slurm` · `DataJoint` · `Streamlit` · `Docker` · `GitHub Actions` · `uv` · `Linux`

**Outside of work** I row, run, and self-host more services than I strictly need (Immich, Vaultwarden, Nextcloud, TrueNAS, and so on). I'm also a member of [US-RSE](https://us-rse.org/) and helped run logistics for US-RSE'25.

📫 [LinkedIn](https://linkedin.com/in/tabedzki) · tabedzki@alumni.upenn.edu
