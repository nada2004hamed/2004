rules:
  - id: avoid-eval
    patterns:
      - pattern: eval($X)
    message: "dont use eval! 🚨"
    severity: WARNING
    languages: [python]
