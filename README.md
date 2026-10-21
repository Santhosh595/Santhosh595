# Santhosh595

```text
~/lab/profile
I build small security tools for messy AI workflows, developer tooling, and SOC operations.
```

<p>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=15&pause=1600&color=7DD3FC&vCenter=true&width=720&lines=building+and+breaking+security+workflows;testing+prompt+boundaries+and+supply+chains;shipping+small+tools+that+stay+useful" alt="Subtle terminal-style animated line about ongoing security tooling work" />
  </a>
</p>

## Flagship

**[agentic-attack-chain](https://github.com/Santhosh595/agentic-attack-chain)** — a correlation
engine for AI-agent attack chains, implementing the ATR Correlation Rule Format v1.0.

![CI](https://github.com/Santhosh595/agentic-attack-chain/actions/workflows/ci.yml/badge.svg)
![Python 3.11+](https://img.shields.io/badge/python-3.11%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

An agent that has been prompt-injected does not leave a single obvious trace. The injection
sits in one tool call; the exfiltration sits in another, a few turns later, in a different
session. Detecting that means correlating observations across time and across agents — which
is what this does. It takes ATR-format observations, matches them against correlation rules
(session-scoped, agent-scoped, and delegation-scoped), and emits findings with the evidence
chain attached.

The README states plainly what is built and what is not: two shipped rules, a schema-validated
rule loader, an OTel GenAI bridge, and replayable evidence — but not yet a broad attack
taxonomy. 149 tests, green on Python 3.11 and 3.12.

## CI-verified projects

Every repo below has a GitHub Actions workflow that runs its test suite on every push, with
third-party actions pinned by full SHA. The test counts are what CI actually reports.

| Project | What it does | Tests |
|---|---|---|
| **[agentic-attack-chain](https://github.com/Santhosh595/agentic-attack-chain)** | Correlation engine for AI-agent attack chains (ATR Correlation Rule Format v1.0) | 149 |
| **[hook-scanner](https://github.com/Santhosh595/hook-scanner)** | Stdlib-only static audit CLI for AI-codetool supply-chain risk — Claude Code hooks, VS Code tasks/extensions, npm install scripts, GitHub Actions workflows, agent instruction files | 46 |
| **[SOC-AutoPilot](https://github.com/Santhosh595/SOC-AutoPilot)** | Autonomous alert triage and investigation agent with a self-learning knowledge base, built on Splunk MCP | 32 |
| **[hackerRack-support-triage](https://github.com/Santhosh595/hackerRack-support-triage)** | Safety-gated, deterministic triage for support requests: prompt-injection detection, domain and request-type classification, and escalation-or-respond routing | 31 |
| **[lean-verify](https://github.com/Santhosh595/lean-verify)** | CLI harness that reports which Lean 4 theorems and definitions actually compile, severity-ranked, with JSON output and CI exit codes | 28 |
| **[SecureNET-Toolkit-](https://github.com/Santhosh595/SecureNET-Toolkit-)** | A suite of standalone Python security tools: FileGuard (AES-256 file encryption), NetworkSniffer (real-time intrusion detection), port scanners, TLS and JWT inspection, security-header analysis, and a unified control-panel dashboard | 26 |
| **[openenv-project](https://github.com/Santhosh595/openenv-project)** | The full multi-agent RL environment for supply-chain disruption: 8-action decision space, 5-type disruption engine, REINFORCE training code, FastAPI server. Ships trained policy checkpoints | 25 |
| **[THREATLENS](https://github.com/Santhosh595/THREATLENS)** | Flask web app that analyses URLs for phishing indicators and returns an explainable, risk-based verdict — including punycode/IDN homograph hosts | 18 |
| **[ctxprobe](https://github.com/Santhosh595/ctxprobe)** | Context-poisoning and prompt-injection red-team scanner CLI | 16 |
| **[verix](https://github.com/Santhosh595/verix)** | Evidence-first multi-modal claim adjudication for insurance damage (car/laptop/package) — visual evidence outranks claim text, with prompt-injection detection and explainable structured decisions | 12 |

## More projects

- **[Supply-Chain-Disruption-Management-OpenEnv-v2.0](https://github.com/Santhosh595/Supply-Chain-Disruption-Management-OpenEnv-v2.0)** — the trained policy files for the environment above.
- **[passkey-security-playbook](https://github.com/Santhosh595/passkey-security-playbook)** —
  a field guide to where passkeys still fail (synced key ecosystems, device compromise,
  recovery flows, MFA bypass) and what organisations should do about it.
- **[mcpsec](https://github.com/Santhosh595/mcpsec)** — design and documentation for a static
  scanner for MCP configurations: hardcoded secrets, over-broad tool permissions,
  unauthenticated admin tools, permissive transports. *Not yet implemented — the repo holds
  the specification, not the tool.*
- **[soc-mini-lab](https://github.com/Santhosh595/soc-mini-lab)** — design for an AI-assisted
  SOC mini-lab: an LLM agent ingests logs, flags suspicious events and proposes
  Sigma/YARA-style detections, with every action behind a human approval gate and an
  append-only audit log. *Not yet implemented — the repo holds the specification, not the
  tool.*

## tools I use

`Python` · `Flask` · `PyTorch / reinforcement learning` · `Splunk MCP` · `Linux` · `Git` · `GitHub Actions` · `security automation` · `phishing analysis` · `prompt-injection testing` · `supply-chain auditing`

## contact

- GitHub: [@Santhosh595](https://github.com/Santhosh595)
- Email: [lmjsanthosh.l@gmail.com](mailto:lmjsanthosh.l@gmail.com)
