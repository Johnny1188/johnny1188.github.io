---
# Display name
title: Jan Sobotka

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Jan
last_name: Sobotka

# Status emoji
status:
  icon: '👨‍💻'

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: CS Master's Student & AI/ML Research Assistant


# Organizations/Affiliations to show in About widget
organizations:
    - name: Swiss Federal Institute of Technology in Lausanne (EPFL)
      url: https://www.epfl.ch/en/


# Short bio (displayed in user profile at end of posts)
# bio: My research interests include reinforcement learning, data-driven control, meta-learning, and self-modeling.
# bio: I am a master's student in computer science at EPFL, and a research assistant at the MLBio Lab. I am interested in representation learning, (mechanistic) interpretability, meta-learning, reasoning, test-time training, and machine consciousness.
bio: I am a master's student in computer science at EPFL and a research assistant at the Autonomous Systems Group at the University of Texas at Austin. I am interested in (mechanistic) interpretability, foundation models, the science of deep learning, and ML applications in brain-computer interfaces.

# Interests to show in About widget
interests:
    - (Mechanistic) interpretability
    - Foundation models
    - Science of deep learning
    # - Machine learning applications in brain-computer interfaces and neuroprosthetics
    #- Reinforcement learning
    #- Meta-learning
    #- Self-modeling
    #- Meta-learning and second-order perception
    # - Test-time training

# Education to show in About widget
education:
  courses:
    - course: Master's degree in Computer Science
      institution: Swiss Federal Institute of Technology in Lausanne (EPFL)
      year: 2024 - 2026
    - course: Bachelor's degree in Informatics, Specialization in Artificial Intelligence
      institution: Czech Technical University in Prague
      year: 2021 - 2024

# Skills
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
# skills:
#   - name: Technical
#     items:
#       - name: Python
#         description: ''
#         percent: 80
#         icon: python
#         icon_pack: fab
#       - name: Data Science
#         description: ''
#         percent: 100
#         icon: chart-line
#         icon_pack: fas
#       - name: SQL
#         description: ''
#         percent: 40
#         icon: database
#         icon_pack: fas
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-hiking
#         icon_pack: fas
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#         icon_pack: fas
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera-retro
#         icon_pack: fas

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: '/#contact'
#   - icon: twitter
#     icon_pack: fab
#     link: https://twitter.com/GeorgeCushen
#     label: Follow me on Twitter
#     display:
#       header: true
#   - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
#     icon_pack: fas
#     link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
#   - icon: github
#     icon_pack: fab
#     link: https://github.com/gcushen
#   - icon: linkedin
#     icon_pack: fab
#     link: https://www.linkedin.com/
  - icon: linkedin
    icon_pack: fab
    link: "https://www.linkedin.com/in/jan-sobotka-6a2822192/"
  - icon: github
    icon_pack: fab
    link: "https://github.com/Johnny1188"
  # Link to a PDF of your resume/CV.
  # To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.yaml`,
  # and uncomment the lines below.
  - icon: cv
    icon_pack: ai
    link: uploads/resume.pdf

# Highlight the author in author lists? (true/false)
highlight_name: true
---

<!-- Hello, I'm Jan, an undergraduate studying computer science at the Czech Technical University in Prague. -->

<!-- While I approach these topics with a fairly multidisciplinary background, my primary focus is on the computational part, particularly in the following areas: -->

My name is Jan, I am a master's student in computer science at EPFL and a research assistant at the [Autonomous Systems Group](https://autonomy.oden.utexas.edu/Groups/autonomous-systems-group) at the University of Texas at Austin, where I work on Large Language Models (LLMs) in strategy games.

<!-- Additionally, I conduct research on world models for reinforcement learning agents at the [Biorobotics Laboratory](https://www.epfl.ch/labs/biorob/). -->

At a high level, I am interested in **(1) understanding how our mind and cognition work** and **(2) building machines that can perceive, think, and learn**. This intersection of artificial intelligence and cognitive computational neuroscience excites me the most. Currently, my primary research interests include (mechanistic) interpretability, foundation models as the basis for autonomous systems, and more broadly, the science of deep learning.

<!-- - (Mechanistic) interpretability
- Foundation models
- Meta-learning -->
<!-- - Machine learning applications in brain-computer interfaces and neuroprosthetics -->
<!-- - Meta-learning and second-order perception
- Test-time training -->

I am always happy to discuss these topics, so if you have related thoughts or questions, please do not hesitate to [contact me](#contact).

<!-- **Actively looking for a 6-month master's thesis internship in industry (Start: Feb 2026).** -->

<!-- If you have strong opinions or an interest in machine consciousness, I'd be especially happy to hear from you :) -->

---
<!-- 
## Why these topics?
Essentially, my goal is to better understand the mechanisms of the mind and cognition, and use this knowledge to empower machines with broad cognitive capabilities, enabling them to adapt to changing, unknown environments and solve novel problems. While current AI systems already exist along this spectrum of generality and problem-solving, the current state seems less than satisfying to me.

Since generality requires adaptation and learning[^1], the efficiency and speed of these processes are critical. And why are humans so good at this? My current understanding is that it mainly stems from the following three sources:
1. **rich cognitive priors** (*innate knowledge*, evolution)
2. **self-modeling** and **self-guidance in our reasoning process**
3. **active learning**

Any system we program on a computer inherently lacks **(1)**, necessitating the training on large amounts of data to imbue priors similar to ours. This is one of the reasons why I'm interested in **meta-learning and self-modeling** - I think learning to learn and self-correct is the natural next step in the AI/ML field to further improve the data efficiency and erase the division between training time and test time. Moreover, to enable further use of what the system has learned, **(2)** self-modeling and self-guidance at inference seems to be of particular importance in reasoning. It's a relatively less studied research area, but I believe it is crucial for the development of general AI as well as the most valuable direction from the cognitive/neuroscience perspective.

**Reinforcement learning (RL) and data-driven control**, on the other hand, act as general frameworks and engineering methodologies for the interaction of an autonomous system with its environment. Additionally, its **(3)** active learning component is one of the reasons why I'm interested in this area - we do not learn passively but rather actively seek out information that is most relevant to our current task. Within these fields, I'm particularly interested in goal-conditioned RL, hierarchical RL, intersections with meta-learning, and the application of these methods in control.

If you see any flaws in my reasoning or just want to share your thoughts, please do not hesitate to [contact me](#contact). I'm always happy to discuss these topics! If you have strong opinions or interest in machine consciousness, I'd be especially happy to hear from you :)

[^1]: Implication of the **No Free Lunch Theorem(s)** in machine learning.
-->

{style="text-align: justify;"}
