---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: |
        <span style="color: white">A Knowledge Platform for Offsite Construction (OSC)</span>
      text: |
        <span style="color: white">Improving performance and collaboration for offsite construction through learning from projects and knowledge reuse by using an integrated open OSC knowledge base</span>
      primary_action:
        text: About the project
        url: project-summary
        icon: rocket-launch
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      style:
        text-color: white
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: "background.webp"
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "Product"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "Process"
          description: |
            GitHub stars  
            since 2016
        - statistic: "People"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: OSC knowledge domains
      text: Our comprehensive suite of professional resources caters to diverse OSC knowledge domains, including OSC performance, OSC product, OSC processes, OSC resources and OSC project mangement.
      items:
        - name: OSC Value
          icon: magnifying-glass
          description: Why we adopt OSC?
        - name: OSC Performance
          icon: bolt
          description: Why we select a particular OSC solution?
        - name: OSC Product
          icon: sparkles
          description: What are the OSC product structure and compositon?
        - name: OSC Process
          icon: code-bracket
          description: How to design, manufact, transport and assemble OSC products?
        - name: OSC Resource
          icon: star
          description: How do we use the resources to leverage the process?
        - name: OSC Project Management
          icon: rectangle-group
          description: How do we manage the OSC projects?
  - block: cta-card
    content:
      title: "Start Using Our OSC Knowledge Base"
      text: It brings all your technical knowledge together in a single, centralized knowledge base. Easily search and reuse it every day!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/details/docs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
