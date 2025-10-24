---
title: "MEIcoder: Decoding Visual Stimuli from Neural Activity by Leveraging Most Exciting Inputs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - admin
    - Luca Baroni
    - Ján Antolík

# Author notes (optional)
# author_notes:
# #   - "First author"
#   - "Equal contribution"
#   - "Equal contribution"
#   - "Equal contribution"
# #   - "Equal contribution"

date: "2025-09-18T00:00:00Z"
# doi: "10.5220/0012317000003636"

# Schedule page publish date (NOT publication"s date).
publishDate: "2025-09-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Accepted"]

# Publication name and optional abbreviated publication name.
publication: "*Conference on Neural Information Processing Systems (**NeurIPS 2025**)*"
# publication_short: ""

abstract: Decoding visual stimuli from neural population activity is crucial for understanding the brain and for applications in brain-machine interfaces. However, such biological data is often scarce, particularly in primates or humans, where high-throughput recording techniques, such as two-photon imaging, remain challenging or impossible to apply. This, in turn, poses a challenge for deep learning decoding techniques. To overcome this, we introduce MEIcoder, a biologically informed decoding method that leverages neuron-specific most exciting inputs (MEIs), a structural similarity index measure loss, and adversarial training. MEIcoder achieves state-of-the-art performance in reconstructing visual stimuli from single-cell activity in primary visual cortex (V1), especially excelling on small datasets with fewer recorded neurons. Using ablation studies, we demonstrate that MEIs are the main drivers of the performance, and in scaling experiments, we show that MEIcoder can reconstruct high-fidelity natural-looking images from as few as 1,000-2,500 neurons and less than 1,000 training data points. We also propose a unified benchmark with over 160,000 samples to foster future research. Our results demonstrate the feasibility of reliable decoding in early visual system and provide practical insights for neuroscience and neuroengineering applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2510.20762
# - name: Poster
#   url: https://neurips.cc/virtual/2025/poster/117726
- name: OpenReview
  url: https://openreview.net/forum?id=V3WQoshcZe

# url_pdf: "https://openreview.net/forum?id=V3WQoshcZe"
# url_code: "https://github.com/HugoBlox/hugo-blox-builder"
# url_dataset: "https://github.com/HugoBlox/hugo-blox-builder"
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: "https://github.com/HugoBlox/hugo-blox-builder"
# url_video: "https://youtube.com"

# Featured image
# To use, add an image named `featured.jpg/png` to your page"s folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project"s folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck"s filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---




<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication"s **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
