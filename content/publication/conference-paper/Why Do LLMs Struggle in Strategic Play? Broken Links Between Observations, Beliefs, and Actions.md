---
title: "Why Do LLMs Struggle in Strategic Play? Broken Links Between Observations, Beliefs, and Actions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - admin
    - Mustafa O. Karabag
    - Ufuk Topcu

# Author notes (optional)
# author_notes:
#   - "First author"
#   - "Equal contribution"
#   - "Equal contribution"

date: "2026-04-30T00:00:00Z"
doi: "10.48550/arXiv.2605.00226"

# Schedule page publish date (NOT publication"s date).
publishDate: "2026-04-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Preprint"]

# Publication name and optional abbreviated publication name.
publication: "*ArXiv (under review)*"
# publication_short: ""

abstract: "Large language models (LLMs) are increasingly tasked with strategic decision-making under incomplete information, such as in negotiation and policymaking. While LLMs can excel at many such tasks, they also fail in ways that are poorly understood. We shed light on these failures by uncovering two fundamental gaps in the internal mechanisms underlying the decision-making of LLMs in incomplete-information games, supported by experiments with open-weight models Llama 3.1, Qwen3, and gpt-oss. First, an observation-belief gap: LLMs encode internal beliefs about latent game states that are substantially more accurate than their own verbal reports, yet these beliefs are brittle. In particular, the belief accuracy degrades with multi-hop reasoning, exhibits primacy and recency biases, and drifts away from Bayesian coherence over extended interactions. Second, a belief-action gap: The implicit conversion of internal beliefs into actions is weaker than that of the beliefs externalized in the prompt, yet neither belief-conditioning consistently achieves higher game payoffs. These results show how analyzing LLMs' internal processes can expose systematic vulnerabilities that warrant caution before deploying LLMs in strategic domains without robust guardrails."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://arxiv.org/abs/2605.00226"
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
