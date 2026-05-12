# competitive-intelligence (Compete)

A Kiro skill for compete positioning against non-AWS cloud providers, ISVs, and incumbent vendors — sourced **exclusively from Cloud Intelligence Highspot** (the "CI Database"). No public internet. No invented feature comparisons. Returns positioning, proof points, objection handlers, pricing combat analysis, architecture/benchmark guidance, honest competitor strengths, watch-outs, and a recommended compete motion (Displace / Coexist & Erode / Contain / Defend / Walk Away).

## Pipeline position

This skill is a **parallel branch off `account-analysis`** — not a step in the `solutions-search → bttroc` chain.

```
account-analysis  →  strategic initiative suggestion
                      ├──→  compete  (parallel)
                      └──→  bttroc
```

## Inputs

- **Customer name**
- **Competitor name** — specific (e.g. "Azure OpenAI Service", not "public cloud")
- **Strategic initiative suggestion** from `account-analysis` — used to identify the contested workload or action per incumbent

It can also run standalone when the user supplies customer + competitor + contested workload directly, without invoking the upstream chain.

## Data source

Cloud Intelligence Highspot (battlecards, compete narratives, displacement playbooks, win/loss analysis, published benchmarks). Every claim is traceable to a CI Highspot artifact.

## Output

`Compete 分析结果` — one compete brief per incumbent × strategic action, with the recommended compete motion, positioning frame, proof points, objection handlers, pricing combat analysis, benchmark guidance, honest competitor strengths, watch-outs, and seller takeaways.

## Triggers

`competitive intelligence`, `compete against Azure`, `compete against GCP`, `compete with Oracle`, `compete with Snowflake`, `compete with Databricks`, `competitive battlecard`, `displacement playbook`, `win against`, `objection handling`, `counter-positioning`, `competitor landscape`, `Cloud Intelligence Highspot`, `CI Highspot`, `pricing comparison`, `benchmark against`, `compete with Alibaba`.

## Usage

Drop this folder into your Kiro `.kiro/skills/` directory. See `SKILL.md` for the full skill definition.
