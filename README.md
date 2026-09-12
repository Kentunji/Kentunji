# Kehinde Adetunji

**Security engineer. Detection engineering, DevSecOps, and applied AI security.**

I write detections and I run the infrastructure they watch. Most people do one or the other.

---

## What I work on

I build security tooling that sits earlier in the lifecycle than it usually does: vulnerability scanners that verify their own findings, CI/CD gates that fail a build rather than file a ticket, SIEM and SOAR pipelines that create the case and escalate it without a human copying anything.

I came into security from carrier networks, so I read a failure at the packet level before I read it at the pod level. That turns out to matter. Knowing what normal traffic looks like is what makes an anomaly visible, and knowing how an access model actually works is what separates a real finding from a noisy one.

The part I find most interesting right now is where LLM reasoning genuinely improves a security workflow, rather than just appearing in the marketing. Usually the hard problem isn't getting a model to work once. It's getting it to behave the same way twice.

---

## Selected work

**[argus](https://github.com/Kentunji/argus)** — Web vulnerability scanner that uses LLM reasoning to find *and then verify* OWASP Top 10 flaws, rather than reporting them blind. Containerised, 67 passing tests, validated against OWASP Juice Shop. Most of the effort went into prompt design for repeatable output.

**[wazuh-soc-lab](https://github.com/Kentunji/wazuh-soc-lab)** — End-to-end SIEM build: Wazuh wired to TheHive for case management, Shuffle for SOAR automation, ModSecurity as the WAF. Custom detection rules mapped to MITRE ATT&CK, with automated case creation, enrichment and escalation.

**[ccf-malware-analysis](https://github.com/Kentunji/ccf-malware-analysis)** — Comparative YARA detection engineering across WannaCry and NotPetya, with multi-angle rules and static reverse engineering.

**ThreatLens** — Malware triage pipeline chaining YARA, capa and Ghidra, mapping indicators to ATT&CK techniques and producing structured threat intelligence rather than a wall of text.

---

## Writing

I author the security research blog at [PurpleIris](https://www.purpleiris.io/blog) — topic selection through research, writing and publication.

- **Keyv npm Worm: Signed Packages and Editor Hooks** — supply chain compromise in the npm ecosystem
- **[Sandbox Escape in OpenAI Models and the Hugging Face Breach](https://www.purpleiris.io/blog/sandbox-escape-openai-models-hugging-face-breach)** — compromise of the AI model supply chain
- **[Phantom Squatting: AI-Hallucinated Domains as an Attack Surface](https://www.purpleiris.io/blog/phantom-squatting-hallucinated-domain-attack-surface)** — a new attack surface created by model hallucination

---

## Background

**Security Analyst** at PurpleIris — detection engineering, SIEM validation, threat intelligence tooling, attack surface management.

**DevOps Engineer** at AzeniQ — Kubernetes on AWS: Istio service mesh with strict mTLS, OPA sidecar authorisation, Kyverno admission control, GitOps delivery through Argo CD.

**IP Network Engineer** at Huawei Technologies — mobile packet backbone at carrier scale for operator customers across West and Southern Africa. 24/7 incident ownership, Python and Netmiko automation across the router fleet.

---

## Tools

```
Detection      Sigma · MITRE ATT&CK · Wazuh · Splunk · TheHive · Shuffle · Suricata
Analysis       YARA · Ghidra · capa · Volatility · Wireshark · Autopsy
AppSec         Semgrep · Trivy · Gitleaks · ModSecurity · Hydra
Languages      Python · Bash · TypeScript
Infrastructure Docker · Kubernetes · Istio · OPA · Kyverno · Terraform · Ansible · KVM
Cloud & CI     AWS · Oracle Cloud · GitHub Actions · Argo CD
Networking     BGP · OSPF · IS-IS · MPLS · L3VPN · Segment Routing · Netmiko
```

---

## Education

**M.Sc. Security and Network Engineering** — Innopolis University (full scholarship)
**B.Eng. Computer Engineering** — Bells University of Technology (Nigeria)

---

Open to remote security engineering roles. [LinkedIn](https://www.linkedin.com/in/kehinde-adetunji-45a6b6191)
