<a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico" src="assets/mosaico-github-hero.webp" width="100%"></a>

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img src="https://img.shields.io/github/stars/mosaico-labs/mosaico?style=flat-square&logo=github&label=mosaico&color=%23bd38b4" alt="mosaico on GitHub"></a>
  <a href="https://docs.mosaico.dev"><img src="https://img.shields.io/badge/docs-docs.mosaico.dev-%2301699a?style=flat-square&logo=readthedocs&logoColor=white" alt="docs"></a>
  <a href="https://pypi.org/project/mosaicolabs"><img src="https://img.shields.io/pypi/v/mosaicolabs?style=flat-square&label=pypi&color=%23f04b23" alt="pypi"></a>
  <a href="https://discord.gg/mwQtFnsckE"><img src="https://img.shields.io/discord/1413199575442784266?style=flat-square&logo=discord&logoColor=white&label=discord&color=%235865f2" alt="discord"></a>
</p>

**[Mosaico](https://github.com/mosaico-labs/mosaico)** is an open-source (Apache 2.0) data platform for robotics. It stores ROS bags, MCAP files and other sensor logs as a typed, indexed archive on your own machines. You can query recordings by their content and read only the time range you need, without parsing the whole file.

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="Explore mosaico" src="assets/explore-mosaico.svg" width="243"></a>
</p>

### Getting started

```bash
curl -fsSL https://get.mosaico.dev | sh                            # mosaicod + mosaicoctl, Linux & macOS
pip install mosaicolabs                                            # Python SDK
mosaicolabs.ros_injector --file run_042.mcap --sequence run_042    # load a recording
```

`mosaicod` is also available as a container image. The [install guide](https://docs.mosaico.dev/daemon/install) has a compose file that runs it with PostgreSQL.

```bash
docker pull ghcr.io/mosaico-labs/mosaicod:latest
```

Next steps: the [getting started guide](https://docs.mosaico.dev/getting_started) and the [Python SDK docs](https://docs.mosaico.dev/python-sdk/).

### Hackathons and challenges

<a href="https://discord.gg/mwQtFnsckE"><img alt="Hackathons and challenges: real robots, real data, against the clock" src="assets/hackathons.svg" width="100%"></a>

We run robotics hackathons and challenges. To practice, [mosaico-alchemy](https://github.com/mosaico-labs/mosaico-alchemy) and [mosaico-test-datasets](https://github.com/mosaico-labs/mosaico-test-datasets) have real datasets you can load, and [`llms-full.txt`](https://docs.mosaico.dev/llms-full.txt) has the full docs in a single file you can give to a coding agent. We announce events on [Discord](https://discord.gg/mwQtFnsckE), and the team answers SDK questions there.

### Repositories

<p>
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico: the platform, Rust daemon and Python SDK" src="assets/repo-mosaico.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-alchemy"><img alt="mosaico-alchemy: ingestion pipelines for public datasets" src="assets/repo-mosaico-alchemy.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-test-datasets"><img alt="mosaico-test-datasets: public ROS bags, ready to load" src="assets/repo-mosaico-test-datasets.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/refx"><img alt="refx: compile-time safe coordinate frames in C++" src="assets/repo-refx.svg" width="49%"></a>
</p>

### Contributing

Use [issues](https://github.com/mosaico-labs/mosaico/issues) for bugs and [discussions](https://github.com/mosaico-labs/mosaico/discussions) for questions, ideas and RFCs. Please read [CONTRIBUTING.md](https://github.com/mosaico-labs/mosaico/blob/main/CONTRIBUTING.md) before opening a PR. The C++ and Rust SDKs are still in development, and we'd like more sensor adapters.

<sub>[mosaico.dev](https://mosaico.dev) · [LinkedIn](https://www.linkedin.com/company/mosaico-labs)</sub>
