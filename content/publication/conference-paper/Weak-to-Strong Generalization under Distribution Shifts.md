---
title: "Weak-to-Strong Generalization under Distribution Shifts"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - Myeongho Jeon
    - admin
    - Suhwan Choi
    - Maria Brbic

# Author notes (optional)
author_notes:
#   - "First author"
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
#   - "Equal contribution"

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

abstract: As future superhuman models become increasingly complex, accurately supervising their behavior may exceed human capabilities. Recent works have demonstrated that in such scenario weak models can effectively supervise strong models, a phenomenon known as weak-to-strong generalization. However, we find that naive weak-to-strong generalization fails under distribution shifts, often leading to worse performance of the strong model than its weak supervisors. To address this, we propose RAVEN, a robust weak-to-strong generalization framework that dynamically learns the optimal combinations of weak models in addition to parameters of the strong model. We demonstrate the effectiveness of RAVEN on image classification, text classification and preference alignment tasks. RAVEN outperforms alternative baselines by over 40% on out-of-distribution tasks while matching or surpassing existing methods on in-distribution tasks. Moreover, our results show that RAVEN assigns higher weights to more accurate weak models, demonstrating its ability to automatically identify trustworthy supervision.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/abs/2510.21332
- name: OpenReview
  url: https://openreview.net/forum?id=fEg31YjLct

# url_pdf: "https://openreview.net/forum?id=fEg31YjLct"
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
