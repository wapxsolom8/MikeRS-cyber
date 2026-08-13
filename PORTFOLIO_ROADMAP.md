# Cybersecurity portfolio roadmap

The goal is to make the GitHub profile evidence-based. Each repository should demonstrate judgment, clarity, and safe security practice without exposing employer or client information.

## Recommended publishing order

### 1. `security-governance-toolkit`

**Why it fits:** Demonstrates ISO 27001, NIST CSF, CIS Controls, audit readiness, risk assessment, and executive reporting experience.

**Useful first release:**

- A synthetic risk register with likelihood, impact, owner, treatment, due date, and residual risk.
- A control-evidence register with evidence owner, collection frequency, retention, and review status.
- A short control-mapping method using a limited example set across ISO/IEC 27001, NIST CSF 2.0, and CIS Controls.
- A one-page executive cyber-risk summary using synthetic data.
- A clear disclaimer that the materials are examples, not legal, certification, or audit advice.

### 2. `incident-response-playbooks`

**Why it fits:** Demonstrates incident coordination, root-cause analysis, mitigation, corrective action, and stakeholder reporting.

**Useful first release:**

- A vendor-neutral incident lifecycle.
- Playbooks for phishing, compromised credentials, malware, cloud access-key exposure, and data-loss alerts.
- Severity and escalation criteria.
- A post-incident review template focused on lessons, actions, owners, and deadlines.
- A tabletop exercise scenario using fictional systems and organizations.

### 3. `cloud-security-control-baselines`

**Why it fits:** Demonstrates AWS, GCP, Azure, Microsoft 365, identity, endpoint, and hybrid-security experience.

**Useful first release:**

- Vendor-neutral baseline principles for identity, logging, network boundaries, encryption, vulnerability management, and recovery.
- Small platform-specific checklists for AWS, Azure, GCP, and Microsoft 365.
- A control rationale and evidence example for every recommendation.
- Versioned releases so readers can see how the baseline evolves.

### 4. `cyber-risk-dashboard-demo`

**Why it fits:** Demonstrates the ability to translate security operations into decision-ready metrics.

**Useful first release:**

- Synthetic input data in CSV format.
- Metrics for vulnerability aging, remediation SLA, incident trends, control exceptions, audit actions, and third-party risk.
- A simple dashboard in a broadly accessible tool or notebook.
- A data dictionary and explanation of why each metric supports a decision.

## Repository quality standard

Every public repository should include:

- `README.md` - purpose, audience, contents, usage, limitations, and screenshots where useful.
- `LICENSE` - selected deliberately for the content type.
- `SECURITY.md` - a safe way to report problems when the repository contains code or security-relevant material.
- `CHANGELOG.md` - useful once the project has releases.
- `docs/` - rationale and mapping notes when the repository needs deeper explanation.
- Realistic but entirely synthetic sample data.

## First 30 days

1. Publish the profile README.
2. Build the first complete release of `security-governance-toolkit`.
3. Publish one incident-response playbook and one fictional tabletop scenario.
4. Pin only completed repositories.
5. Add one short case-study note explaining a security decision, the tradeoff, and the evidence used - without naming an employer or client.

## Confidentiality guardrails

Never publish internal policies, audit evidence, client deliverables, incident timelines, screenshots of production tools, infrastructure identifiers, proprietary control mappings, credentials, tokens, or data copied from an employer. Recreate examples from a blank page with fictional names and synthetic values.
