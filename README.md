# AI Governance Evidence Lab

An independent, one-page [Quarto](https://quarto.org/) research concept exploring **the quality of evidence used in AI governance, what evaluations establish, and how evidence should inform oversight decisions**.

This is a **research agenda and visual concept**, not an operational evaluation tool, validated assessment methodology, completed empirical study, or institutional project.

## Illustrative case: AI in hiring

A proposed research case asks what evidence would support a claim that an AI recruitment system reduces discrimination. It separates measured performance and audits from conclusions about fairness or causal impact, then considers what evidence employers and regulators would require before making deployment and oversight decisions. The example is hypothetical, grounded in UK public guidance and regulator audit work. It is a possible research direction rather than a completed study or confirmed fellowship topic.

References: [UK Responsible AI in Recruitment guidance](https://www.gov.uk/government/publications/responsible-ai-in-recruitment-guide/responsible-ai-in-recruitment) and [ICO audits of AI recruitment tools](https://ico.org.uk/about-the-ico/media-centre/news-and-blogs/2024/11/ico-intervention-into-ai-recruitment-tools-leads-to-better-data-protection-for-job-seekers/).

## Research questions

1. **Evidence quality:** What makes developer claims, evaluations, audits, and incident reports credible?
2. **Measurement and inference:** When can test results or deployment observations support conclusions about real-world impacts and risks?
3. **Governance decisions:** How should decision-makers use evidence and uncertainty to determine oversight, disclosure, monitoring, or intervention?

## Proposed first output

A scoped research paper or policy report comparing publicly documented AI assurance approaches, with a transparent evidence matrix and decision-relevant recommendations. The question, methods, and output remain open to refinement.

## Files

- `index.qmd` — one-page research concept.
- `styles.css` — responsive visual design.
- `_quarto.yml` — Quarto website configuration.
- `.gitignore` — local and generated files excluded from version control.

## Preview and publish

Install [Quarto](https://quarto.org/docs/get-started/), then run:

```bash
quarto preview
```

Build static HTML with `quarto render`. To publish to a **new, separate repository**, initialize or copy these source files into that repository and run `quarto publish gh-pages` from its root. Configure GitHub Pages to serve the `gh-pages` branch. Do **not** run the publish command from the original repository if you want to preserve it.

Suggested new repository name: `ai-governance-evidence-lab`.

## Research context and references

The concept is independently authored and broadly relevant to questions of AI evaluation, risk management, assurance, and evidence-informed governance. Useful starting references:

- [GovAI — UK Summer Fellowship 2027, Research Track](https://www.governance.ai/post/uk-summer-fellowship-2027-research-track)
- [GovAI — AI Governance: A Research Agenda](https://cdn.governance.ai/GovAI-Research-Agenda.pdf)
- [GovAI — Research Scholar topics](https://www.governance.ai/post/research-scholar)

These references motivate research directions but do not imply endorsement, collaboration, or acceptance into any program.

© 2026 Caio Velasco.
