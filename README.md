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

### [resumx](https://resumx.dev)

Full reference for Resumx, a CLI Markdown resume renderer for AI-first workflows, featuring auto page fitting and role-based tailoring.

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
| [Laszlo Bock / Work Rules!](https://www.linkedin.com/posts/laszlobock_my-personal-formula-for-a-winning-resume-activity-7289686500462452736-PcrJ) | XYZ formula: "Accomplished [X] as measured by [Y] by doing [Z]" |
| [TheLadders Eye Tracking (2012, updated 2018)](https://www.theladders.com/career-advice/you-only-get-6-seconds-of-fame-make-it-count) | Recruiters spend 6-7.4 seconds on initial resume scan |
| [MatchRate](https://www.matchrate.co/blog/resume-keywords-data) | ATS pass rates from 10k+ scans: action verbs ("Led" 96%), buzzwords ("Responsible for" 23%), passive ("helped" 33%, "involved in" 21%), tech-vague ("coding" 45%, "computer skills" 12%) |
| [JobEase / Fortune 500 A/B test](https://www.jobease.ca/blog/the-resume-element-that-increased-interview-rates-by-340-it-s-not-what-you-think) | Keywords in first 50 words → 340% more interview requests (n = 8,000) |
| [ScoutApply](https://scoutapply.com/research/keyword-matching-statistics) | Job title match → 10.6x interview rate |
| [EDLIGO (1,000 rejected resumes)](https://www.edligo.net/job-search-tips/i-analyzed-1000-rejected-resumes-heres-what-ats-actually-sees-and-its-not-what-you-think/) | Vague isolated skill claims → 67% rejection; contextual skills → 34% |
| [Inc. / Resume.io](https://www.inc.com/jeff-haden/the-10-most-commonly-used-resume-buzzwords-hiring-managers-hate-most.html/) | 1,600+ hiring managers flag "proven," "synergy" as filler |
| [Nielsen Norman Group](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content-discovered/) | F-pattern reading: eyes scan top horizontally, then down the left margin |
| [Forbes / Huntr (59k resumes)](https://www.forbes.com/sites/rachelwells/2025/09/03/this-resume-hack-boosts-interview-chances-by-115-study-shows/) | Tailored resumes → 115% higher interview rate vs generic (5.75% vs 2.68%) |
| [Resume-Now (18.4M resumes)](https://www.resume-now.com/job-resources/careers/resume-results-report) | Only 10% of resumes include measurable results; 34% of hiring managers call it a dealbreaker |
| [ResumeGo (7,712 resumes)](https://resumego.net/research/one-or-two-page-resumes) | Two-page resumes preferred 2.3x over one-page; scored 21% higher on clarity |
| [TalentTuner (944 resumes)](https://talenttuner.app/research/whitepaper) | 72% of resumes score below the 70% ATS threshold; average score 57.6% |
| [SSRN 4074976](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4074976) | Gender-incongruent resume language penalizes women's callbacks (330k resumes) |
| [ACL 2022](https://aclanthology.org/2022.nlpcss-1.15/) | Gender signals detectable in CVs even after stripping names |
| [ICIS 2021](https://aisel.aisnet.org/icis2021/data_analytics/data_analytics/17/) | Neutral verbs outperform both passive and aggressive extremes |
