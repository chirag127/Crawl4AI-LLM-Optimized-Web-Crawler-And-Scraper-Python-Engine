---
name: Bug Report
about: Report a bug in the Crawl4AI project
title: "Bug: "
labels: bug, needs-triage
assignees: "chirag127"

body:
  - type: markdown
    attributes:
      value: |n      ## Apex Standard Bug Report Template (Late 2025)
      
      Thank you for reporting a bug! Please provide as much detail as possible to help us diagnose and fix the issue.
      
      **Project:** `Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine`
      **Repository:** [https://github.com/chirag127/Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine](https://github.com/chirag127/Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine)

  - type: markdown
    attributes:
      value: |n      ### 1. Summary
      A concise, clear description of the bug.

  - type: textarea
    id: summary
    attributes:
      label: Bug Summary
      description: |n        Please provide a short, descriptive summary of the bug.
      placeholder: e.g., "Crawler crashes when encountering malformed HTML on specific pages."
    validations:
      required: true

  - type: markdown
    attributes:
      value: |n      ### 2. Steps to Reproduce
      Detailed steps to reproduce the behavior.

  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to Reproduce
      description: |n        Please provide clear, step-by-step instructions to reproduce the bug.
      placeholder: |
        1. Navigate to `https://example.com/malformed-page`
        2. Run the crawler with the command `crawl4ai crawl --url https://example.com/malformed-page --output-format markdown`
        3. Observe the error message or crash.
    validations:
      required: true

  - type: markdown
    attributes:
      value: |n      ### 3. Expected Behavior
      What you expected to happen.

  - type: textarea
    id: expected-behavior
    attributes:
      label: Expected Behavior
      description: |n        What did you expect to happen after following the steps above?
      placeholder: e.g., "The crawler should gracefully handle the malformed HTML, perhaps log a warning, and continue processing or terminate cleanly."
    validations:
      required: true

  - type: markdown
    attributes:
      value: |n      ### 4. Actual Behavior
      What actually happened.

  - type: textarea
    id: actual-behavior
    attributes:
      label: Actual Behavior
      description: |n        What actually happened. Include any error messages or stack traces.
      placeholder: e.g., "The crawler exited with a `ValueError: Malformed HTML detected` and a stack trace."
    validations:
      required: true

  - type: markdown
    attributes:
      value: |n      ### 5. Environment Details
      Information about your environment.

  - type: textarea
    id: environment
    attributes:
      label: Environment
      description: |n        Please provide details about your environment. This is crucial for diagnosing issues.
      placeholder: |
        *   **Operating System:** macOS 14.2 (Sonoma)
        *   **Python Version:** Python 3.11.9
        *   **uv Version:** 0.7.0
        *   **Ruff Version:** 0.4.2
        *   **Crawl4AI Version:** v0.1.0 (commit hash `abcdef123`)
        *   **Any relevant dependencies:** LangChain v0.2.0, OpenAI Python client v1.28.0
    validations:
      required: true

  - type: markdown
    attributes:
      value: |n      ### 6. Additional Context
      Any other information that might be helpful.

  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: |n        Screenshots, logs, configuration files, or any other context that helps explain the problem.
      placeholder: e.g., "I noticed this started happening after updating the `requests` library."
    validations:
      required: false

  - type: markdown
    attributes:
      value: |n      ### 7. Potential Cause/Solution (Optional)
      If you have any ideas about the cause or a potential solution, please share them.

  - type: textarea
    id: potential-cause-solution
    attributes:
      label: Potential Cause / Solution
      description: |n        (Optional) If you have any insights into the cause or a possible fix, please add them here.
      placeholder: e.g., "I suspect the regex used for parsing links is too strict."
    validations:
      required: false
