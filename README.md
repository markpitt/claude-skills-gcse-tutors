<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/banner-dark.svg">
    <img src="docs/assets/banner-light.svg" alt="GCSE tutors" width="100%">
  </picture>
</h1>

Nine GCSE revision tutors, frozen at the 2026 exam year.

Revision tutors for students and parents rather than developers. Every tutor is pinned to the 2026 exam year in its name, description and metadata, and the set is frozen there: specifications change, so check a tutor against the current specification before relying on it for a later year.

This is one of seven skill groups. [claude-skills](https://markpitt.dev/claude-skills/) lists them all and
holds the shared tooling: validation, packaging, the evaluation harness and the TUI.

## Skills

<!-- BEGIN GENERATED SKILL INDEX -->
| Skill | Bundled files | What it does |
|---|---|---|
| [gcse-art-tutor](skills/gcse-art-tutor/SKILL.md) | 4 files | GCSE Art and Design (Fine Art) tutor and revision assistant for 15 to 16 year old students preparing for… |
| [gcse-biology-tutor](skills/gcse-biology-tutor/SKILL.md) | 4 files | GCSE Biology tutor and revision assistant for 15 to 16 year old students preparing for their exams across… |
| [gcse-chemistry-tutor](skills/gcse-chemistry-tutor/SKILL.md) | 4 files | GCSE Chemistry tutor and revision assistant for 15 to 16 year old students preparing for their exams across… |
| [gcse-english-language-tutor](skills/gcse-english-language-tutor/SKILL.md) | 4 files | GCSE English Language tutor and revision assistant for 15 to 16 year old students preparing for their exams… |
| [gcse-english-literature-tutor](skills/gcse-english-literature-tutor/SKILL.md) | 4 files | GCSE English Literature tutor and revision assistant for 15 to 16 year old students preparing for their exams… |
| [gcse-history-tutor](skills/gcse-history-tutor/SKILL.md) | 4 files | GCSE History tutor and revision assistant for 15 to 16 year old students preparing for their exams across… |
| [gcse-maths-tutor](skills/gcse-maths-tutor/SKILL.md) | 3 files | GCSE Maths tutor and revision assistant for 15 to 16 year old students preparing for their exams across AQA… |
| [gcse-pe-tutor](skills/gcse-pe-tutor/SKILL.md) | 4 files | GCSE Physical Education tutor and revision assistant for 15 to 16 year old students preparing for their exams… |
| [gcse-physics-tutor](skills/gcse-physics-tutor/SKILL.md) | 4 files | GCSE Physics tutor and revision assistant for 15 to 16 year old students preparing for their exams across… |

9 skills.
<!-- END GENERATED SKILL INDEX -->

## Install

Copy a skill directory into either skills location, then start a new session:

```bash
cp -r skills/<skill-name> ~/.claude/skills/    # personal, all projects
cp -r skills/<skill-name> .claude/skills/      # this project only
```

For Claude Desktop, zip the skill directory's contents and upload the zip under Settings,
Capabilities, Skills:

```bash
cd skills/<skill-name> && zip -r ../../<skill-name>.zip .
```

## Licence

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE). Each skill directory carries its
own copy of the licence, so a skill copied out on its own stays covered.
