MODULE 3 — Guardrails
- Hallucination mitigation
- Missing/empty/short section warnings
- Strict Evidence Mode:
      evidence_mode = "strict"
      When active → summarize onlywhat exists in the provided text
      If insufficient evidence → output:
      “The source text does not provide enough detail to summarize this section in strict evidence mode."
