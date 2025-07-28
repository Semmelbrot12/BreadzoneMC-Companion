name: Bug report
about: Report an issue with the BreadzoneMC Companion.
title: "[BUG] "
labels: bug
assignees: Semmelbrot12

body:
  - type: markdown
    attributes:
      value: |
        BEFORE SUBMITTING, FILL THIS CHECKLIST OUT  
        YOUR ISSUE WILL BE IGNORED IF YOU DO NOT

  - type: checkboxes
    id: pre_submit_checklist
    attributes:
      label: ""
      options:
        - label: I have searched for existing issues related to this bug
          required: true
        - label: I have provided detailed steps to reproduce the issue
          required: true
        - label: I have included screenshots or logs if applicable
          required: true
        - label: I am on the latest version. Support for outdated versions will not be provided, use them at your own risk.
          required: true

  - type: markdown
    attributes:
      value: |
        **Describe the bug**  
        A clear and concise description of what the bug is.

  - type: textarea
    id: description
    attributes:
      label: To Reproduce
      description: Steps to reproduce the behavior:
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. See error
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: Expected behavior
      description: A clear description of what you expected to happen.
    validations:
      required: true

  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: If applicable, add screenshots to help explain your problem.

  - type: textarea
    id: additional_context
    attributes:
      label: Additional context
      description: Add any other context about the problem here.
