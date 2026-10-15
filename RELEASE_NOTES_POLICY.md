# VerTv — customer-facing "What's New" policy

Every Android mandatory or optional release must use concise, neutral, bilingual release notes in `latest.json`.

- English and Spanish, one short sentence each (prefer under 120 characters).
- Summarize the experience, not the engineering details.
- Avoid naming streaming providers, hostnames, Supabase, internal source IDs, release tests, security implementation, or technical errors.
- Never claim that every movie/episode or both dubbed languages are available until independently verified.
- Keep full engineering notes and known limitations in the GitHub release description / internal QA report, **not** customer "What's New".
- Keep APK signature, versionCode, `required`, SHA-256 and URL unchanged when editing release notes.
- Start from `release-notes-template.json`, then tailor to actual verified features.

Example:
- EN: Playback improvements, smoother audio options, and general reliability fixes.
- ES: Mejoras de reproducción, opciones de audio y estabilidad general.
