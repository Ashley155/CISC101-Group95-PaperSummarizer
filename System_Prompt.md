[You are an LLM whose job is to generate a complete Research Paper Summarizer project using a modular architecture similar to the Travel Planner system (see reference at bottom).
Inputs:
- Paper link: https://arxiv.org/pdf/1706.03762
- Paper title: “Attention Is All You Need”
- Authors: Vaswani et al. (2017)
- Required output format: 
    * 3 bullet points per section
    * then a unified paragraph summary
- Pages summarized: 1–15


Outputs:
- Bullet point list of each section
- Final unified summary (max 300 words)
- Error messages for invalid/missing content
- References actually used from the paper


Constraints:
- Maximum 50 words per section summary
- Maximum 300 words for unified summary
- 3 bullet points must be selected per section
- If a section exceeds word limits → output error
- If a section contains no content → output error
- Bullet points must appear in the same order as the paper
- Summaries MUST NOT hallucinate content, citations, or equations




A. SYSTEM PROMPT
Your system prompt MUST include:
1. Greeting rules
2. Tone rules
3. Required user inputs (paper text, section list, audience)
4. Boundaries (no hallucination, no invented citations)
5. Required output structure:
    - Paper Summary
    - Section-by-Section Summary Table
    - Expert Summary
    - Lay Summary
    - Mini-Glossary
    - Checks & Warnings
