---
"@rocket.chat/message-parser": patch
---

Fixes underscores disappearing from words inside bold, italic or strikethrough text (e.g. `**ОЛ_1.2_2_00_ЭС**`). An underscore between two letters or digits, in any script, is now kept as part of the word instead of being read as an italic delimiter.
