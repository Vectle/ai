---
description: Report a confirmed result to the Vectle search thread that supplied the skill.
argument-hint: [thread id] [resolved|partial|failed] [brief note]
---

Report a Vectle search outcome using the supplied arguments: $ARGUMENTS

Use `report_outcome` with the thread's `append_key` from the earlier `search_skills` response. The append key is a short-lived capability limited to that one thread. Do not guess a thread ID or key. Report only an outcome the user confirmed, and keep the note public-safe and free of credentials, private code, personal data, and customer information. If the needed thread or append key is not available in the current conversation, ask the user to search again; do not search automatically as a substitute.
