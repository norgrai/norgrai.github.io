---
title: 'Nora'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download Résumé
      #  url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      columns: '2'
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true   
  - block: markdown
    content:
      title: 'How LLMs describe/predict 😉 me:'
      subtitle: ''
      text: |-
       - Unraveling linguistic mysteries through computational prowess, a PhD student in Computational Linguistics, learning at the forefront of language and technology. [Claude 3 Sonnet](https://www.anthropic.com/news/claude-3-5-sonnet)
       - PhD student at the Universitat Pompeu Fabra in Barcelona, Spain, bridging language and technology to uncover the secrets of human communication.  [Meta-Llama-3-70B-Instruct](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct)
       - PhD Candidate in the vibrant field of Computational Linguistics at the UPF in Barcelona, captivated by the nexus of language and tech, crafting models that decode human speech. [Yi-Large](https://build.nvidia.com/01-ai/yi-large)
  - block: markdown
    content:
      title: '📚 My Interests'
      subtitle: ''
      text: |-
       - Intricacies of Human Language
       - Natural Language Processing, particularly Machine Translation (MT), and ongoing exploration of low-resource MT
       - Natural Language Understanding for process descriptions
       - Spending time outdoors in nature 🍃
  #- block: skills
  #  content:
  #    title: Skills & Hobbies
  #    username: admin
  - block: awards
    content:
      title: Publications
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      view: citation
 # - block: languages
 #   content:
 #     title: Languages
 #     username: admin
---
