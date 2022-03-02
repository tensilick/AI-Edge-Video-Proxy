# AI-Edge-Video-Proxy

![GitHub release (latest by date)](https://img.shields.io/github/v/release/tensilick/AI-Edge-Video-Proxy) 

AI-Edge Video Proxy efficiently ingests multiple RTSP camera streams and provides a common interface for performing AI operations on or near the Edge.

## Why use AI-Edge Video Proxy?

AI-Edge Video Proxy is a simple, user-friendly data collection mechanism from multiple cameras onto a single high-powered computer. 

For instance, a network of CCTV RTSP enabled cameras can be accessed through a simple GRPC interface, where Machine Learning algorithms can perform various Computer Vision tasks. In addition, captivating footage can be annotated, selectively streamed, and stored through an easy-to-use API for later analysis, computer vision tasks in the cloud, or for enhancing Machine Learning training samples.

<p align="center">
    <img src="https://storage.googleapis.com/chrysaliswebassets/chrysalis-video-edge-ai-proxy.png" title="Chrysalis Cloud" />
<p align="center">

## Documentation

For more extensive documentation, click [here](https://tensilick.github.io/api_doc/)

## Contents

* [Prerequisites](#prerequisites)
* [Quick Start](#quick-start)
* [Usage](#usage)
* [Examples](#examples)
  * [Prerequisites](#example-prerequisites)
  * [Running basic_usage.py](#example-prerequisites)
  * [Running opencv_display.py](#example-prerequisites)
  * [Running annotation.py](#example-prerequisites)
  * [Running storage_onoff.py](#example-prerequisites)
  * [Running opencv_inmemory_display.py](#example-prerequisites)
  * [Running video_probe.py](#example-prerequisites)
* [Custom configuration](#custom-configuration)
  * [Custom Redis Configuration](#custom-redis-configuration)
  * [Custom Chrysalis Configuration](#custom-chrysalis-configuration)
* [Building from source](#building-from-source)
[...(goes on with the rest of the README content)...]

# Authors

- **Tensilick** - Current maintainer
- **Igor Rendulic** - Initial work


# License

This project is licensed under Apache 2.0 License - see the `LICENSE` for details.


# Acknowledgments

<p align="left">
    <img src="https://storage.googleapis.com/chrysaliswebassets/logo_small.png" style="width: 300px;" title="Chrysalis Cloud" />