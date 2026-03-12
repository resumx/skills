# Resume Writing Agent Skills

Research-backed skills for writing resumes. Every rule traces back to a real study.

## Available Skills

### resume-writing

Data-driven rules for resume content, drawn from 500k+ hiring outcomes and 10k+ ATS scans. Explains why certain wording hurts (e.g. buzzwords lower pass rate, passive language signals subordination) so the agent can apply the mental model, not just a word list.

**Use when:**

- Writing or rewriting resume bullets or sections
- Improving word choice, quantification, or phrasing
- Tailoring a resume to a job description (keywords, tech-in-context)
- Structuring or formatting a resume (headers, dates, promotion stack, visual hierarchy)
- Checking for gendered language bias or aspirational filler

**Covers:** strategic framing, bullet composition (XYZ, So what?, show don't tell), bullet priority and length, quantification and scale anchoring, ATS-tested word choice with causal framing, tailoring and keyword placement, structure and formatting (including de-junioring, interests), visual hierarchy (F-pattern, white space), gendered language

### resumx

Full reference for Resumx, a Markdown-to-PDF resume renderer with auto page fitting and tag-based tailoring.

**Use when:**

- Creating or editing a Resumx resume
- Configuring tags, views, or multi-language output
- Styling, custom CSS, or page fitting
- Using the CLI or converting from other formats

**Covers:** syntax, CLI, frontmatter, style options, icons, tags, views, variables, multi-language, page fitting, validation, custom CSS

## Installation

```bash
npx skills add resumx/skills
```

## Sources

| Study | Finding |
| --- | --- |
| [NBER 30886](https://www.nber.org/papers/w30886) | Better writing = 8% more hires, 10% higher wages (n ≈ 500k) |
| [ScoutApply](https://scoutapply.com/research/keyword-matching-statistics) | Job title match → 10.6x interview rate |
| [MatchRate](https://www.matchrate.co/blog/resume-keywords-data) | ATS pass rates from 10k+ scans ("Led" 96%, "Responsible for" 23%) |
| [Inc. / Resume.io](https://www.inc.com/jeff-haden/the-10-most-commonly-used-resume-buzzwords-hiring-managers-hate-most.html/) | 1,600+ hiring managers flag "proven," "synergy" as filler |
| [ACL 2022](https://aclanthology.org/2022.nlpcss-1.15/) | Gender signals detectable in CVs even after stripping names |
| [ICIS 2021](https://aisel.aisnet.org/icis2021/data_analytics/data_analytics/17/) | Neutral verbs outperform both passive and aggressive extremes |
