# Rules for anyone maintaining this repo

This repo is **public**. Read these before changing anything.

1. **No client content, ever.** No client names, slides, quotes or figures, in any file, commit or
   log entry. Examples inside a skill are anonymised before they land.
2. **A skill never writes the client's words.** It surfaces findings and asks questions. The
   consultant writes every word.
3. **claude.ai upload limits.** `SKILL.md` frontmatter uses only `name`, `description`, `license`,
   `compatibility`, `metadata` and `allowed-tools`; any other field makes the upload fail. The
   `description` is at most 200 characters. A zip has the skill folder at its root.
4. **One folder per skill**, flat: `skills/<name>/`. Unbuilt skills are named in `README.md`, never
   as placeholder folders.
5. **Decisions go in `decisions/`**, one short file each: what was decided and why. Ideas that were
   rejected go in `.out-of-scope/`, so nobody re-adds them.
6. **Changes to a skill follow real use.** Log what went wrong in the improvement log first. No
   entry, no change.
