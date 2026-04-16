<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# Agro Field Tracking Video Sample Annotated

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#use-cases-for-farmers">Use cases for farmers</a> •
  <a href="#download">Download</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/agro-field-tracking-video-sample-annotated)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/agro-field-tracking-video-sample-annotated.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/agro-field-tracking-video-sample-annotated.png)](https://supervisely.com)

</div>

## Overview

This is an annotated sample project featuring drone footage of agricultural fields with tracked field boundaries, crop zones, roads, and tractor tracks. The project demonstrates object tracking capabilities with pre-annotated masks, polilines created using the automated annotation tools [Serve Segment Anything 2.1](https://dev.internal.supervisely.com/ecosystem/apps/serve-segment-anything-2?id=330) and [AutoTrack](https://docs.supervisely.com/labeling/labeling-toolbox/videos-3.0#auto-tracking), eliminating the need for manual frame-by-frame annotation. While this example focuses on agro field monitoring, the annotation methodology is universal and can be applied to any aerial or ground-level agricultural video — from crop health assessment to precision farming and field boundary detection.

<img src="https://github.com/supervisely-ecosystem/agro-field-tracking-video-sample-annotated/releases/download/v1.0.0/agro-field.png" />

## Use cases for farmers

This type of annotation is directly applicable to real-world precision agriculture workflows. Farmers and agri-tech teams can use similar labeled data to:

- **Monitor field boundaries** — automatically detect and track the edges of cultivated plots across seasons to control land use and identify encroachments
- **Analyze tractor routes** — track machinery paths to optimize coverage, reduce fuel consumption, and detect missed or overlapping passes
- **Assess road and access conditions** — identify dirt roads and field access routes to plan logistics and maintenance
- **Detect crop zone changes** — track vegetation patterns over time to spot areas of poor growth, waterlogging, or pest damage early
- **Support precision farming systems** — feed annotated video data into AI models for autonomous machinery guidance, yield prediction, and soil health analysis

Using the Supervisely platform, farmers and agronomists can:

- Upload drone footage directly and annotate it with [Segment Anything 2.1](https://dev.internal.supervisely.com/ecosystem/apps/serve-segment-anything-2?id=330)
- Use [AutoTrack](https://docs.supervisely.com/labeling/labeling-toolbox/videos-3.0#auto-tracking) to automatically propagate annotations across video frames, significantly reducing labeling time
- Train and deploy custom CV models on their own field data using [Supervisely training pipelines](https://docs.supervisely.com/neural-networks/overview)
- Build end-to-end labeling and model deployment workflows without leaving the platform

<img src="https://github.com/supervisely-ecosystem/agro-field-tracking-video-sample-annotated/releases/download/v1.0.0/agro-field-demo.gif" />

All annotations are stored in Supervisely format, compatible with the platform's video annotation tools and export options.

## Download

This project sample in Supervisely format: [Download ZIP archive](https://github.com/supervisely-ecosystem/agro-field-tracking-video-sample-annotated/releases/download/v1.0.0/project.zip)
