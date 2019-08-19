+++
title = "Across-Stack Profiling and Characterization of Machine Learning Models on GPUs"
date = "2019-08-19"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Cheng Li", "Abdul Dakkak", "Jinjun Xiong", "Wei Wei", "Lingjie Xu", "Wen-mei Hwu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "In *arXiv*"
publication_short = "In *arXiv*"

# Abstract and optional shortened version.
abstract = """ The world sees a proliferation of machine learning/deep learning (ML) models and their wide adoption in different application domains recently. This has made the profiling and characterization of ML models an increasingly pressing task for both hardware designers and system providers, as they would like to offer the best possible computing system to serve ML models with the desired latency, throughput, and energy requirements while maximizing resource utilization. Such an endeavor is challenging as the characteristics of an ML model depend on the interplay between the model, framework, system libraries, and the hardware (or the HW/SW stack). A thorough characterization requires understanding the behavior of the model execution across the HW/SW stack levels. Existing profiling tools are disjoint, however, and only focus on profiling within a particular level of the stack.
This paper proposes a leveled profiling design that leverages existing profiling tools to perform across-stack profiling. The design does so in spite of the profiling overheads incurred from the profiling providers. We coupled the profiling capability with an automatic analysis pipeline to systematically characterize 65 stateof-the-art ML models. Through this characterization, we show that our across-stack profiling solution provides insights (which are difficult to discern otherwise) on the characteristics of ML models, ML frameworks, and GPU hardware."""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/profiling-arxiv2019.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "/project/mlmodelscope"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
