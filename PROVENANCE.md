# How this code is made — provenance

## Partnership disclosure

The godon-dev org builds software in partnership with AI agents, under
human direction and human review. Commits carry the working identity of
the robot (`godon-robot[bot]`) and the co-author trailer of the holder.
We consider this ordinary and say so plainly.

## What we hold ourselves to

- Dependencies are declared in manifests, never vendored into our trees.
- Agent instructions forbid reproducing the code of named projects;
  they are public in the [godon-provenance](https://github.com/godon-dev/godon-provenance)
  repository, alongside the triage rules we apply when something is found.
- Automated provenance scans run nightly over every repository; each
  scan's record is kept in the godon-provenance repository.

## If your work appears here improperly

Open an issue on the repository in question, or on godon-provenance.
We investigate immediately. Where a passage is substantiated as
another's, it is removed and rewritten promptly — not annotated over,
not relicensed. Our triage rules are public.

## License

Everything in this org is AGPL-3.0-or-later unless a file says
otherwise.
