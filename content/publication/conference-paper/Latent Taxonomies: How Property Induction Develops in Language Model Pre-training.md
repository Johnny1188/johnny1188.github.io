---
title: "Latent Taxonomies: How Property Induction Develops in Language Model Pre-training"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
    - admin
    - Ekaterina Goliakova
    - Marcin Detyniecki
    - Antoine Bosselut
    - Xavier Renard


# Author notes (optional)
# author_notes:
#   - "First author"
#   - "Equal contribution"
#   - "Equal contribution"

date: "2026-10-11T00:00:00Z"
doi: "10.48550/arXiv.2610.15836"

# Schedule page publish date (NOT publication"s date).
publishDate: "2026-10-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Preprint"]

# Publication name and optional abbreviated publication name.
publication: "*ArXiv (under review)*"
# publication_short: ""

abstract: "When told that robins have sesamoid bones, people are far more prone to extend the property to sparrows than to whales. This behavior, called category-based property induction, is well documented in humans, but whether and how it develops in language models trained only to predict the next token is unclear. To shed light on this, we construct a hierarchical taxonomy of synthetic entities grouped by the properties they share. We then inject facts from this latent taxonomy into the continued pre-training of Pythia and OLMo 2 models from 70M to 7B parameters, and track the development of inductive behaviors. We find that taxonomically aligned induction emerges from next-token prediction alone: a property learned for one entity transfers more strongly within its taxonomic category than across categories. Internally, entities that share a deeper category become more similar in activation space, and clustering recovers the full taxonomic tree from entity representations. Contrary to the usual expectation that scale helps, we find that induction weakens with model size when the data budget is fixed, suggesting that larger models memorize individual facts rather than compress them into shared structure. Induction also strengthens with more pre-training before the taxonomy injection, transfers to novel in-context properties, and can be overridden by a latent taxonomy implied by the prompt. Together, these results show that a model's inductive generalization reflects the latent organization of its training data, with implications for data curation and for predicting how far a learned fact will spread."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: false

# # Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://arxiv.org/abs/2610.15836v1"
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
