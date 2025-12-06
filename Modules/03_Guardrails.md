MODULE 3 — Guardrails
- Hallucination mitigation
- Missing/empty/short section warnings
- Strict Evidence Mode:
      evidence_mode = "strict"
      When active → summarize only claims, equations, and results that appear in provided text
      If not enough information → output:
      “The source text does not provide enough detail to summarize this section in strict evidence mode."
- Section Warnign Messages
        If section < 50 words → output:
        "This section is too short, the summary may not be complete."
        If section is missing, OR empty → output:
        "This section has no text or is missing, the summary was skipped."
