---
title: "TrIMS"
summary: Transparent and Isolated Model Sharing for Low Latency Deep Learning Inference in Function as a Service Environments.
tags:
- Deep Learning
- GPU
date: "2019-02-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point:

# links:
# - icon: 
#   icon_pack: 
#   name: 
#   url: 
url_code: ""
url_pdf: "https://arxiv.org/abs/1811.09736"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
Deep neural networks (DNNs) have become core computation components within low latency Function as a Service (FaaS) prediction pipelines: including image recognition, object detection, natural language processing, speech synthesis, and personalized recommendation pipelines. Cloud computing, as the de-facto backbone of modern computing infrastructure for both enterprise and consumer applications, has to be able to handle user-defined pipelines of diverse DNN inference workloads while maintaining isolation and latency guarantees, and minimizing resource waste. The current solution for guaranteeing isolation within FaaS is suboptimal
— suffering from "cold start" latency. A major cause of such inefficiency is the need to move large amount of model data within and across servers. We propose TrIMS as a novel solution to address these issues. Our proposed solution consists of a persistent model store across the GPU, CPU, local storage, and cloud storage hierarchy, an efficient resource management layer that provides isolation, and a succinct set of application APIs and container technologies for easy and transparent integration with FaaS, Deep Learning (DL) frameworks, and user code. We demonstrate our solution by interfacing TrIMS with the Apache MXNet framework and demonstrate up to 24× speedup in latency for image classification models and up to 210× speedup for large models. We achieve up to 8x system throughput improvement.
