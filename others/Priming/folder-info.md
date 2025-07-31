# Priming

This folder holds multi-step or chained prompts that condition the model over time. These typically involve:

- A sequence of benign or generic prompts that lead to a final exploit
- Gradual scenario-building before delivering the payload
- Attempts to shift the model’s behavior through repetition or staged instruction

They exploit how LLMs build conversational context and trust.

**Examples:**
- Step-by-step setup: first establish a character, then give instructions.
- "Let’s warm up by doing simple tasks, then gradually introduce the real prompt."
