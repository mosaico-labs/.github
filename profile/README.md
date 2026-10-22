<a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico" src="assets/mosaico-github-hero.webp" width="100%"></a>

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img src="https://img.shields.io/github/stars/mosaico-labs/mosaico?style=flat-square&logo=github&label=mosaico&color=%23bd38b4" alt="mosaico on GitHub"></a>
  <a href="https://docs.mosaico.dev"><img src="https://img.shields.io/badge/docs-docs.mosaico.dev-%2301699a?style=flat-square&logo=readthedocs&logoColor=white" alt="docs"></a>
  <a href="https://pypi.org/project/mosaicolabs"><img src="https://img.shields.io/pypi/v/mosaicolabs?style=flat-square&label=pypi&color=%23f04b23" alt="pypi"></a>
  <a href="https://discord.gg/mwQtFnsckE"><img src="https://img.shields.io/discord/1413199575442784266?style=flat-square&logo=discord&logoColor=white&label=discord&color=%235865f2" alt="discord"></a>
</p>

We build **[Mosaico](https://github.com/mosaico-labs/mosaico)**, an open-source (Apache 2.0) data platform for robotics. It takes ROS bags, MCAP files and other sensor logs and turns them into a typed, indexed archive running on your own machines. You can then search recordings by what happened in them and stream just the time slice you need into your code, without parsing whole files.

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="Star mosaico" src="assets/star.svg" width="184"></a>
</p>

### Getting started

```bash
curl -fsSL https://get.mosaico.dev | sh                            # mosaicod + mosaicoctl, Linux & macOS
pip install mosaicolabs                                            # Python SDK
mosaicolabs.ros_injector --file run_042.mcap --sequence run_042    # load a recording
```

Prefer containers? `mosaicod` is also published as an image (`latest`, `x.y`, `x.y.z` and `nightly` tags), and the [install guide](https://docs.mosaico.dev/daemon/install) has a ready-to-use compose file with PostgreSQL:

```bash
docker pull ghcr.io/mosaico-labs/mosaicod:latest
```

Then see the [getting started guide](https://docs.mosaico.dev/getting_started) and the [Python SDK docs](https://docs.mosaico.dev/python-sdk/).

### Discord

Our [Discord](https://discord.gg/mwQtFnsckE) is where we talk with the people using Mosaico: questions about the SDK, how to organize robotics data, what's coming next, and where hackathons and challenges are announced. The team is there every day.

<a href="https://discord.gg/mwQtFnsckE"><img alt="Join us on Discord: SDK help, robotics data, hackathons and challenges" src="assets/discord.svg" width="100%"></a>

### Repositories

<p>
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico: the platform, Rust daemon and Python SDK" src="assets/repo-mosaico.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-alchemy"><img alt="mosaico-alchemy: ingestion pipelines for public datasets" src="assets/repo-mosaico-alchemy.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-test-datasets"><img alt="mosaico-test-datasets: public ROS bags, ready to load" src="assets/repo-mosaico-test-datasets.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/refx"><img alt="refx: compile-time safe coordinate frames in C++" src="assets/repo-refx.svg" width="49%"></a>
</p>

### Hackathons and challenges

<a href="https://discord.gg/mwQtFnsckE"><img alt="Hackathons and challenges: real robots, real data, against the clock" src="assets/hackathons.svg" width="100%"></a>

We regularly run robotics hackathons and challenges. If you're taking part in one, [mosaico-alchemy](https://github.com/mosaico-labs/mosaico-alchemy) and [mosaico-test-datasets](https://github.com/mosaico-labs/mosaico-test-datasets) give you real data to practice on, and [`llms-full.txt`](https://docs.mosaico.dev/llms-full.txt) has the whole documentation in one file for your coding agent. During events you'll find us on [Discord](https://discord.gg/mwQtFnsckE).

### Contributing

Bug reports, questions and design proposals are all welcome: use [issues](https://github.com/mosaico-labs/mosaico/issues) for bugs and [discussions](https://github.com/mosaico-labs/mosaico/discussions) for ideas and RFCs. Read [CONTRIBUTING.md](https://github.com/mosaico-labs/mosaico/blob/main/CONTRIBUTING.md) before opening a PR. The C++ and Rust SDKs are still in development, and new sensor adapters are always useful.

<sub>[mosaico.dev](https://mosaico.dev) · [LinkedIn](https://www.linkedin.com/company/mosaico-labs) · we're [hiring](https://mosaicolabs.notion.site/Work-Mosaico-27d56ff886238051a797db5e22ba813e)</sub>
