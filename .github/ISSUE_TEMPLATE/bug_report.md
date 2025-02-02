name: Bug report
description: Create a report to help us improve
title: "[BUG] "
labels: ["bug"]

body:
- type: markdown
  attributes:
    value: |
      Thank you for reporting a bug! Please fill out the form below with as much detail as possible.

- type: textarea
  id: bug_description
  attributes:
    label: "Describe the bug"
    description: "A clear and concise description of what the bug is."
    placeholder: "Describe the bug..."
  validations:
    required: true

- type: textarea
  id: to_reproduce
  attributes:
    label: "To Reproduce"
    description: |
      Steps to reproduce the behavior:
      1. Go to '...'
      2. Click on '...'
      3. Scroll down to '...'
      4. See error
    placeholder: "List steps to reproduce..."
  validations:
    required: true

- type: textarea
  id: expected_behavior
  attributes:
    label: "Expected behavior"
    description: "A clear and concise description of what you expected to happen."
    placeholder: "Describe expected behavior..."
  validations:
    required: true

- type: textarea
  id: logs
  attributes:
    label: "Logs"
    description: "If relevant please attach your log file. See the Settings screen in DLSS Swapper for the location of your current log file."
    placeholder: "Attach logs here..."

- type: textarea
  id: screenshots
  attributes:
    label: "Screenshots"
    description: "If applicable, add screenshots to help explain your problem."
    placeholder: "Paste screenshots here..."

- type: textarea
  id: additional_context
  attributes:
    label: "Additional context"
    description: "Add any other context about the problem here."
    placeholder: "Provide additional context..."

- type: input
  id: dlss_swapper_version
  attributes:
    label: "DLSS Swapper version"
    description: "Version:"
    placeholder: "e.g. 1.2.3"
  validations:
    required: true
