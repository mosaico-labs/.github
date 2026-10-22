<a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico" src="assets/mosaico-github-hero.webp" width="100%"></a>

<h1 align="center">Stop scrubbing through rosbags.</h1>
<p align="center"><b>Query your robot data by what actually happened.</b></p>

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img src="https://img.shields.io/github/stars/mosaico-labs/mosaico?style=flat&logo=github&label=mosaico&color=%23bd38b4" alt="mosaico on GitHub"></a>
  <a href="https://docs.mosaico.dev"><img src="https://img.shields.io/badge/docs-docs.mosaico.dev-%231a99c3?logo=readthedocs&logoColor=white" alt="docs"></a>
  <a href="https://pypi.org/project/mosaicolabs"><img src="https://img.shields.io/pypi/v/mosaicolabs?label=pypi&color=%23f04b23" alt="pypi"></a>
  <a href="https://discord.gg/mwQtFnsckE"><img src="https://img.shields.io/discord/1413199575442784266?logo=discord&logoColor=white&label=discord&color=%235865f2" alt="discord"></a>
</p>

**[Mosaico](https://github.com/mosaico-labs/mosaico)** is the open-source data platform for robotics and physical AI. Throw your ROS bags and MCAP files at it and get back a typed, indexed archive on your own machines. Ask for every hard brake, every IMU spike over 15 m/s², every run recorded in the rain, and stream exactly those slices into your training code. No bag parsers, no CSV dumps, no vendor cloud.

**Rust daemon. Python SDK. Apache 2.0.**

<p align="center">
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="Star mosaico on GitHub" src="assets/star.svg" width="340"></a>
</p>

## From bag to query in three commands

```bash
curl -fsSL https://get.mosaico.dev | sh    # mosaicod, Linux & macOS
pip install mosaicolabs                    # Python SDK
mosaicolabs.ros_injector --file run_042.mcap --sequence run_042
```

**→** [Getting started](https://docs.mosaico.dev/getting_started) · [Python SDK](https://docs.mosaico.dev/python-sdk/) · [Docs for your coding agent](https://docs.mosaico.dev/llms-full.txt)

## Talk to us

<a href="https://discord.gg/mwQtFnsckE"><img alt="Join us on Discord: SDK help, robotics data, hackathons and challenges" src="assets/discord.svg" width="100%"></a>

## What we ship

<p>
  <a href="https://github.com/mosaico-labs/mosaico"><img alt="mosaico: the platform, Rust daemon and Python SDK" src="assets/repo-mosaico.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-alchemy"><img alt="mosaico-alchemy: ingestion pipelines for public datasets" src="assets/repo-mosaico-alchemy.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/mosaico-test-datasets"><img alt="mosaico-test-datasets: public ROS bags, ready to load" src="assets/repo-mosaico-test-datasets.svg" width="49%"></a>
  <a href="https://github.com/mosaico-labs/refx"><img alt="refx: compile-time safe coordinate frames in C++" src="assets/repo-refx.svg" width="49%"></a>
</p>

## Hackathons & challenges

<a href="https://discord.gg/mwQtFnsckE"><img alt="Hackathons and challenges: real robots, real data, against the clock" src="assets/hackathons.svg" width="100%"></a>

We run robotics hackathons and challenges, and we like showing up prepared. So should you: [mosaico-alchemy](https://github.com/mosaico-labs/mosaico-alchemy) and [mosaico-test-datasets](https://github.com/mosaico-labs/mosaico-test-datasets) put real recordings in a local instance before the clock starts, and [`llms-full.txt`](https://docs.mosaico.dev/llms-full.txt) puts the whole documentation in your agent's context.

## Build it with us

Rust daemon, Python SDK, C++ and Rust SDKs on the way, sensor adapters always wanted. Open an [issue](https://github.com/mosaico-labs/mosaico/issues), start a [discussion](https://github.com/mosaico-labs/mosaico/discussions), read [CONTRIBUTING.md](https://github.com/mosaico-labs/mosaico/blob/main/CONTRIBUTING.md) and send the PR.

<sub>[mosaico.dev](https://mosaico.dev) · [LinkedIn](https://www.linkedin.com/company/mosaico-labs) · we're [hiring](https://mosaicolabs.notion.site/Work-Mosaico-27d56ff886238051a797db5e22ba813e)</sub>
