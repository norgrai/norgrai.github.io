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
  - block: collection
    content:
      title: Publications
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      view
 # - block: languages
 #   content:
 #     title: Languages
 #     username: admin
---
