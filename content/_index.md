---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: "Download CV"
        url: "uploads/resume.pdf"
    design:
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: "stacked-peaks.svg"
          filters:
            brightness: 1.0
          size: "20%"
          position: "center"
          parallax: false

  - block: resume-skills
    content:
      title: "Skills & Expertise"
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-experience
    content:
      title: "Professional Experience"
      username: admin
    design:
      date_format: "January 2006"

  - block: resume-education
    content:
      title: "Education"
      username: admin
    design:
      date_format: "January 2006"

  - block: resume-projects
    content:
      title: "Open Source Contributions"
      username: admin

  - block: contact
    content:
      title: "Contact"
      text: "Feel free to reach out for collaboration opportunities or technical discussions."
      email: job@laodouya.com
      phone: "+86 15810540933"
      address:
        street: "Shenzhen"
        city: "Guangdong"
        region: "China"
        country: "China"
        country_code: "CN"
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---