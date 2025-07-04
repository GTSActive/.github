name: 🐛 Bug Report
description: Report a bug or unexpected behavior
title: "[BUG] <title here>"
labels: ["bug"]
assignees: []

body:
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      placeholder: Describe the issue in detail
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: What did you expect to happen?
    validations:
      required: false

  - type: input
    id: version
    attributes:
      label: Software Version
      placeholder: e.g. v1.2.3

  - type: textarea
    id: logs
    attributes:
      label: Relevant logs or screenshots
      render: shell
