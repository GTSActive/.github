name: 🌟 Feature Request
description: Suggest a new feature or enhancement
title: "[FEATURE] <title here>"
labels: ["enhancement"]
assignees: []

body:
  - type: textarea
    id: proposal
    attributes:
      label: Describe your idea
      placeholder: What should we build and why?
    validations:
      required: true

  - type: dropdown
    id: priority
    attributes:
      label: Priority
      options:
        - Low
        - Medium
        - High
