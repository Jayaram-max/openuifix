---
"@openuidev/lang-core": patch
---

Include Zod `.describe()` text for component props in the generated prompt. Each described prop is listed under its component signature, and the text is also exposed as `propDescriptions` on `ComponentPromptSpec`. Components with no described props produce the same prompt as before.
