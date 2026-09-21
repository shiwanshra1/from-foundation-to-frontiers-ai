# From Beginner to the Frontiers of AI — Skills Setup

This repository contains the skills demonstrated during the **From Beginner to the Frontiers of AI** workshop.

## Important note about the uploaded files

Two source files were provided for this setup:

1. `SKILL (6).md`
2. `c005d2ef-a883-4a9b-922e-6e510da35068.skill`

After inspecting both files, they contain the **same skill**:

- **Original skill name:** `hackathon-problem-research`
- **Skill title:** Hackathon & Startup Problem-Statement Research Skill

The `.skill` file is a packaged version containing:

```text
hackathon-problem-research/SKILL.md
```

Therefore, the two uploads do **not** represent two different skills. They are two representations of the same skill. No separate `Project Memory Log` skill was present in the uploaded source material, so this setup does not invent one.

## Files in this repository

```text
from-beginner-to-frontiers-of-ai/
│
├── hackathon-problem-research.md
├── hackathon-problem-research-from-package.md
└── setup.md
```

For an actual skill repository, keep only one copy of the skill:

```text
from-beginner-to-frontiers-of-ai/
│
├── hackathon-problem-research/
│   └── SKILL.md
│
└── setup.md
```

The canonical skill filename should be:

```text
hackathon-problem-research/SKILL.md
```

The skill's internal metadata also identifies it as `hackathon-problem-research`.

---

# Workshop Overview

## From Beginner to the Frontiers of AI

The skill was demonstrated as part of the **From Beginner to the Frontiers of AI** workshop.

The purpose of the skill is to turn a request for a hackathon or startup problem statement into a structured, presentation-ready idea using real, public, verifiable sources.

Its workflow is:

```text
Domain Selection
       ↓
Public Source Discovery
       ↓
Present 4–6 Options
       ↓
User Selects One
       ↓
Full Documentation
       ↓
Winning-Format PPT
```

The skill specifically emphasizes:

- Real and publicly verifiable problem statements
- Domain-first research
- Multiple options instead of immediately selecting one problem
- Source verification
- Structured documentation
- A six-slide hackathon presentation format
- Avoiding invented problem IDs, tender IDs, ministries, statistics, or claims

---

# 1. Cloud / Agent Setup

The exact UI differs between cloud platforms and AI-agent environments, but the general setup is:

## Step 1 — Download or clone the repository

```bash
git clone <repository-url>
cd from-beginner-to-frontiers-of-ai
```

## Step 2 — Create the skill directory

Use the standard skill layout:

```text
skills/
└── hackathon-problem-research/
    └── SKILL.md
```

Place the contents of:

```text
hackathon-problem-research.md
```

into:

```text
skills/hackathon-problem-research/SKILL.md
```

## Step 3 — Register or attach the skill

If your cloud/agent platform has a **Skills**, **Agent Skills**, **Tools**, **Capabilities**, or similar section, add the `hackathon-problem-research` skill there.

If the platform uses a filesystem-based skills directory, make sure the directory containing `SKILL.md` is available to the agent.

## Step 4 — Enable the skill for the agent

Attach the skill to the agent, workspace, or project where it will be used.

## Step 5 — Test it

Try:

> Find hackathon problem statements in Healthcare & MedTech.

The skill should first ask for the required domain/source-scope/target-use information before beginning research.

---

# 2. Using the Skill in ChatGPT

The same workflow can be used as part of a ChatGPT Project.

## Step 1 — Create a Project

Create a new ChatGPT Project and give it a project-specific name.

Example:

```text
Hackathon Research Lab
```

## Step 2 — Add the skill as a Project resource

Upload:

```text
hackathon-problem-research.md
```

to the Project's files/resources.

If your ChatGPT Project supports project instructions, keep the skill available as a project resource and configure the Project to use it when relevant.

## Step 3 — Add project-specific material

You can also add:

- Hackathon problem statements
- Competition guidelines
- Existing research
- Team information
- Technical requirements
- Reference documents
- Previous submissions

## Step 4 — Start the workflow

Example:

> I want to find a hackathon problem statement in Healthcare & MedTech.

The skill should begin with its mandatory domain/source-scope/target-use selection process.

---

# 3. What the Skill Does

## Phase 0 — Domain Selection

The skill requires three inputs before research begins:

1. Domain
2. Source scope
3. Target use

Supported domains include:

- Agriculture & AgriTech
- Healthcare & MedTech
- FinTech & Financial Inclusion
- Education & EdTech
- Smart Cities & Governance
- Transportation & Logistics
- Environment, Climate & Sustainability
- Renewable & Clean Energy
- Cybersecurity & Blockchain
- Disaster Management & Public Safety
- Tourism & Culture
- Manufacturing, Industry 4.0 & Robotics
- Retail, E-commerce & Supply Chain
- Miscellaneous / Surprise me across domains

Source scope can include SIH, government tenders, MyGov, NITI Aayog, AICTE, and Startup India.

Target use can be:

- Hackathon submission
- Startup / venture idea
- Both

## Phase 1 — Public Source Discovery

The skill uses public sources such as:

- SIH
- MyGov
- NITI Aayog
- AICTE
- Startup India
- GeM
- eProcure
- State tender portals
- data.gov.in

Promising results must be opened and verified before they are presented.

## Phase 2 — Present Options

The skill presents **4–6 real problem statements** for the selected domain.

Each option should contain:

- Source
- ID, where applicable
- Title
- Issuing body
- Problem description
- Direct URL
- Why it may be a good fit

## Phase 3 — Confirm the Pick

The skill waits for the user to explicitly choose an option.

It should not jump directly from research to the final document or presentation.

## Phase 4 — Full Documentation

After the user selects a problem, the skill produces documentation covering:

1. Problem Background
2. Existing Solutions & Gaps
3. Proposed Solution
4. Technical Approach / Architecture
5. Feasibility & Viability
6. Impact & Benefits
7. Implementation Roadmap
8. References

## Phase 5 — Winning-Format PPT

The skill uses a six-slide structure:

1. Title
2. Idea / Proposed Solution
3. Technical Approach
4. Feasibility & Viability
5. Impact & Benefits
6. Research & References

The skill specifies bullet-driven content, diagrams/flowcharts where appropriate, and avoidance of dense paragraphs.

---

# 4. Recommended Repository Structure

For publishing the actual skill, use:

```text
from-beginner-to-frontiers-of-ai/
│
├── README.md
│
├── skills/
│   └── hackathon-problem-research/
│       └── SKILL.md
│
└── setup.md
```

The canonical `SKILL.md` should retain the original metadata:

```yaml
---
name: hackathon-problem-research
description: >
  Use this skill whenever Shiwansh wants to research hackathon or startup
  problem statements from public sources...
---
```

Do not rename the internal `name` unless you intentionally want to create a different skill.

---

# 5. Important Integrity Rule

The skill itself requires research to be grounded in real, public, verifiable sources.

When deploying or modifying it:

- Do not invent problem statements.
- Do not invent PS numbers.
- Do not invent tender IDs.
- Do not invent issuing ministries or organizations.
- Do not present an unverified listing as current.
- Do not skip the domain/source-scope selection stage.
- Do not generate the final document or PPT before the user explicitly selects a problem.

---

# 6. Adding the Second Skill

The uploaded source material does not contain a separate `Project Memory Log` skill.

If a separate Project Memory Log skill was demonstrated during the workshop, its original `SKILL.md` needs to be added to this repository before it can be packaged accurately.

Once that file is available, the intended structure can become:

```text
from-beginner-to-frontiers-of-ai/
│
├── README.md
│
├── skills/
│   ├── hackathon-problem-research/
│   │   └── SKILL.md
│   │
│   └── project-memory-log/
│       └── SKILL.md
│
└── setup.md
```

The second skill should not be recreated from assumptions because its actual instructions, metadata, workflow, and original name are not present in the uploaded material.
