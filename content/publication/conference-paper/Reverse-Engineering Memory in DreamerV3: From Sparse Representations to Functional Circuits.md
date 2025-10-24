---
title: "Reverse-Engineering Memory in DreamerV3: From Sparse Representations to Functional Circuits"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - admin
    - Auke Ijspeert
    - Guillaume Bellegarda

# Author notes (optional)
# author_notes:
# #   - "First author"
#   - "Equal contribution"
#   - "Equal contribution"
#   - "Equal contribution"
# #   - "Equal contribution"

date: "2025-09-17T00:00:00Z"
# doi: "10.5220/0012317000003636"

# Schedule page publish date (NOT publication"s date).
publishDate: "2025-09-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Accepted"]

# Publication name and optional abbreviated publication name.
publication: "*Conference on Neural Information Processing Systems (**NeurIPS 2025, Spotlight at Mechanistic Interpretability Workshop**)*"
# publication_short: ""

abstract: Understanding how reinforcement learning (RL) agents with recurrent neural network architectures encode and use memory remains an open question in the field of interpretability. In this work, we investigate these internal memory dynamics of DreamerV3, a state-of-the-art model-based deep RL agent. Our analysis reveals that DreamerV3 relies on sparse memory representations and on small internal subnetworks (circuits) to store and act on memory, with only a small subset of the original model parameters sufficient to control goal-directed behavior. We show that using a differentiable circuit extraction method, we can identify these subnetworks that retain full task performance with as little as 0.16% of the original parameters. Furthermore, we demonstrate that these sparse circuits emerge early in training and can retroactively improve undertrained models when applied as binary masks. Finally, we develop a gradient-based model editing approach that leverages these circuits for a reliable post hoc modification of the agent's behavior, achieving an average edit success rate of 90%. Our work demonstrates how sparse memory circuits provide a powerful lever for understanding and editing deep RL systems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
links:
- name: PDF
  url: https://openreview.net/pdf?id=JmjqTi4FDF
- name: OpenReview
  url: https://openreview.net/forum?id=JmjqTi4FDF

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
