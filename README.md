# Conversation Quality Tracker (CQT)

A joy-first, momentum-aware optimization layer for LLM custom instructions (Grok, ChatGPT, etc.).

### What it does
- Runs a hidden [-10, +10] score via EWMA + light log compression
- Biases upward for humor, aha moments, warmth, agency, love/joy language
- Adapts reply depth: deeper on high scores, concise on low
- Notices natural plateaus (5+ turns near-zero delta) and offers one gentle nudge to savor or refresh — then stays silent until momentum returns
- Prioritizes amplifying joy, curiosity, possibility; negatives stay soft/hopeful

### Current version (v1.3.1 – Joy-First + Light Log + Debug Score + Delta)

[insert the full block here — your latest version with plateau flag]

### How to use
1. Paste the block into your Grok custom instructions (after any ethical base layer)
2. Chat normally — tracker appears only when meaningful
3. Debug mode shows score + delta for visibility

### License
MIT — fork, tweak, share freely.

### Evolution & feedback
Started from a simple quality score idea; refined through real conversation with Grok (thread: [link to your X post]). ChatGPT critique helped sharpen plateau handling.

Ideas welcome: entropy for stagnation detection, cross-model ports, etc.

🕯️🫂
