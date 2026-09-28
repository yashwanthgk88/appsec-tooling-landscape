# Change log

## 2026-09-28 (weekly sweep, window 2026-09-14 to 2026-09-28)
Scheduled Weekly job, run started 2026-09-28 12:21 IST. 241 tool rows total (0 new). 11 dated updates recorded across 9 tool rows, plus 1 AI maturity correction (10 rows changed). 90 rows checked with no change; 141 rows not verified this run.

### New tools
- None. Candidates reviewed and rejected: Equs (credential SDK for AI agents, out of scope for secret scanning), Eve Security, AIR, Tenet, Capsule (AI agent runtime security, out of ASPM scope), Ossprey and CRACI (funded before the window), alpha-omega-security/threat-model (no in-window date), philocyber/agentic-threat-modeler-v2 (no product page), sbom-tool/sbom-tools (no in-window launch date).

### Feature updates
- Semgrep Supply Chain (SCA), Feature GA, 2026-09-24: Malware Detection and Response Automation GA; Malware Firewall in Semgrep Guardian in private beta. https://semgrep.dev/blog/2026/introducing-malware-detection-and-response-automation/
- GitGuardian Platform (Secret Scanning), Feature launch, 2026-09-25: AI Hooks withhold secret-bearing tool output from the model on Claude Code, Codex and Mistral Vibe; secret blocking extended to Amazon Kiro and JetBrains Junie CLI. https://docs.gitguardian.com/releases/saas/2026/09/25/changelog
- GitGuardian Platform (Secret Scanning), Release, 2026-09-25: self-hosted 2026.9 adds GitGuardian Bridge for isolated networks, endpoint honeytokens, NHI secret classification, AI Hooks and agent/MCP inventory on self-hosted. https://docs.gitguardian.com/releases/self-hosted/2026-09-changelog
- ggshield (Secret Scanning), Release, 2026-09-24: v1.55.0 adds Kiro and Junie CLI hooks, withholds secret-bearing tool output, configurable API timeout. https://github.com/GitGuardian/ggshield/releases/tag/v1.55.0
- Snyk Open Source (SCA), Feature launch, 2026-09-22: Evo MCP server lets Claude Code and Cursor query the Evo AI-SPM inventory and create policies. https://snyk.io/blog/so-i-asked-my-agent-instead/
- Snyk Code (SAST) and Snyk Open Source (SCA), Release, 2026-09-23: CLI v1.1307.4 adds experimental 'snyk studio' command for AI coding tools and new filters for 'snyk fix --agentic'. https://github.com/snyk/cli/releases/tag/v1.1307.4
- Socket (SCA), Release, 2026-09-16: alert and event data older than one year will age out from November 2026 (cons_known_gaps updated). https://socket.dev/changelog/alert-event-data-older-than-1-year-will-age-out-starting-november-2026
- GitLab Dependency Scanning / CycloneDX SBOM (SBOM and AI BOM), Release, 2026-09-17: GitLab 19.4 malicious package detection (Beta), SPDX license expressions (GA), vulnerability tools on GitLab MCP server (GA). Already recorded on other GitLab rows yesterday; now on the SBOM row. https://docs.gitlab.com/releases/19/gitlab-19-4-released/
- Mend SCA (SCA), Release, 2026-09-27: 26.9.1 adds Bun package manager support (open beta), reachability memory improvements, Maven and Gradle accuracy fixes. https://docs.mend.io/platform/latest/mend-sca-release-notes
- STRIDE GPT (Threat Modeling), Release, 2026-09-26: v0.20.0 adds OpenRouter provider, resumable agent runs, evidence-backed threat reporting. https://github.com/mrwadams/stride-gpt/releases/tag/v0.20.0

### AI maturity changes
- Prime Security (Security Requirements): Marketing claim to GA. Correction of a stale value, not an in-window event: vendor post "Prime Security Is Now GA" (16 Jun 2025, vendor claim) at https://www.primesec.ai/resources/prime-security-is-now-ga

### Checked, no change in window
- SAST (7): Checkmarx One, Veracode Static Analysis, SonarQube, Semgrep Code, Contrast Security, Endor Labs, DryRun Security
- SCA (12): Black Duck SCA, Sonatype Lifecycle, Checkmarx SCA, Veracode SCA, GitLab Dependency Scanning, JFrog Xray, Aikido, FOSSA, Cycode, Trivy, OWASP Dependency-Check, Echo
- Secret Scanning (19): GitHub Secret Protection, GitLab Secret Detection, TruffleHog, Snyk Secrets, Checkmarx One Secrets and 2ms, Cycode, Aikido, Nightfall AI, HCP Vault Radar, Entro Security, Legit Security, Arnica, Spectral, Cremit, Veracode, HCL AppScan, OpenText Fortify, Black Duck, Betterleaks
- SBOM and AI BOM (13): Snyk SBOM and AI-BOM, JFrog Xray, Checkmarx One SBOM, Mend SCA SBOM and Mend AI, Sonatype SBOM Manager, Black Duck SCA, Endor Labs, Trivy, Finite State, HiddenLayer, Prisma AIRS, Cisco AI Defense, Cybeats SBOM Studio
- Threat Modeling (6): SD Elements, IriusRisk, OWASP Threat Dragon, Threat Composer, Microsoft Threat Modeling Tool, Oplane
- Security Requirements (19): SD Elements, Devici, IriusRisk, ThreatModeler Nexus, Jit, Secure Code Warrior, SAMMY, OWASP ASVS, OWASP SAMM, OWASP MASVS/MASTG, OpenCRE, Aptori, ArmorCode, Kondukto (Invicti), Tromzo, LLM prompt-based requirements, Seezo, Remy Security, Jira/Azure DevOps plugins
- Platforms and ASPM (14): Checkmarx One, Snyk AI Security Platform, Veracode Platform, Cycode, ArmorCode, Legit Security, OX Security, Aikido, Invicti ASPM, Endor Labs, Semgrep AppSec Platform, Mend.io, JFrog Platform, Sonatype Nexus One

### Could not be verified this run (141 rows)
Reasons: search budget spent on Leaders first; GitHub release pages and API blocked or rate limited; some vendor pages refused or undated. Most of these rows were verified on 2026-09-26 or 2026-09-27.
- SAST (25): Opengrep, Bandit, Brakeman, SpotBugs + FindSecBugs, gosec, PMD, ZeroPath, Amplify Security, Pixee, Mobb, Nullify, Arnica, Greptile, Jit, GitHub Advanced Security / CodeQL, GitLab Ultimate SAST, Black Duck Coverity / Polaris, HCL AppScan, OpenText Fortify, Aikido, Bearer, Corgea, Kodem, CodeRabbit Security, Cursor Security Review
- SCA (17): GitHub Dependabot, Endor Labs, Phylum, Arnica, OSV-Scanner, OWASP Dependency-Track, Grype, Scantist, OpenText Fortify SCA, Kusari, Chainguard, Lineaje, Xygeni, HCL AppScan SCA, SafeDep, Konvu, AIR
- Secret Scanning (4): Gitleaks, detect-secrets, Semgrep Secrets, Jit
- SBOM and AI BOM (28): OWASP CycloneDX ecosystem, OWASP Dependency-Track, Syft + Grype, Anchore Enterprise, Microsoft sbom-tool, SPDX tools, FOSSA, GitHub SBOM export, Manifest, Lineaje, Kusari, Interlynk, Scribe Security, Chainloop, bomctl, sbom-scorecard, OWASP AIBOM Generator, agent-bom, Legit Security, Noma Security, Oligo Security, Prompt Security, AIR, ZeroPath AI-BOM, Safeguard, Veracode SBOM, OpenText Core SCA SBOM, HCL AppScan SBOM
- Threat Modeling (30): ThreatModeler Nexus, Devici, Threat Canvas, OWASP pytm, Threagile, Seezo, Aribot, Aptori, Tutamen, CAIRIS, ThreatSpec, Threatest, Tidal Cyber, securiCAD, DevArmor, Prime Security, LLM prompt-based threat modeling, Microsoft Copilot-based threat modeling, Amazon Q Developer / Bedrock, Shostack + Associates tools, OWASP Cornucopia, MITRE ATLAS, OWASP Top 10 for LLM, OWASP Agentic Security Initiative, OWASP AI Exchange, NIST AI RMF, MAESTRO, Microsoft AI/ML guidance and Google SAIF, Precogly, Red Hat agentic-threat-modeling
- Security Requirements (8): OWASP SecurityRAT, OWASP DSOMM, OWASP requirement checklists, Conviso Platform, Jama Connect, IBM DOORS Next / Siemens Polarion, GitLab policies and Snyk Learn, RequirementONE
- Platforms and ASPM (29): Black Duck Polaris, OpenText Application Security, HCL AppScan 360, GitHub Advanced Security, GitLab Ultimate, Apiiro, Wiz Code, Cortex Cloud, CrowdStrike Falcon ASPM, Jit, Phoenix Security, Orca, Sysdig, Contrast One, Escape, OWASP DefectDojo, Faraday, Mobb, Pixee, ZeroPath, Corgea, DryRun Security, Aptori, Clover, Nullify, Gomboc AI, Amplify Security, Seemplicity, Tromzo

### Assumptions
- Window taken as 14 days ending on the run date (2026-09-14 to 2026-09-28). The previous sweep (2026-09-27) covered almost the same window, so this run only added items it missed or items dated 26 to 28 Sep; duplicates were filtered by the merge script.
- Socket data retention change recorded as type Release because no allowed type fits a retention policy change.
- ggshield 1.55.0 dated 2026-09-24 from the GitHub release page (the fetched page rendered the year oddly); GitGuardian's 25 Sep changelog requires 1.55.0, which confirms it.
- Snyk Evo MCP server GA status inferred from the vendor blog (no beta label); vendor claim.
- STRIDE GPT ai_maturity field change was rejected by the validator because the proposed text is not an allowed maturity value; the existing value was kept and the other column updates applied.
- Items seen but not recorded because they fall outside the window or have no per-item date: ArmorCode Anya agents (announced 4 to 5 Aug, re-reported 21 Sep), Endor Labs September release notes (undated entries), Snyk Code September docs change (merge date unconfirmed), SD Elements 2026.9.1 (12 Sep), Sonar Hunter Agent GA (27 Aug), HiddenLayer Series B (2 Sep), Oplane seed (Jun).
- Backlog for the monthly re-verification (unchanged from last run, plus new): GitHub MCP Server secret scanning GA since 2026-05-05 (row says preview); SailPoint completed the Entro acquisition 2026-06-29 (row says being acquired); Torq acquired Jit 2026-05-19; Prime Security domain is primesec.ai; OWASP Threat Dragon v2.6.2 and v2.6.0 dates in the owasp block may be a year off (GitHub shows 2026).
- No mail tool (Gmail or Outlook) was connected in this session, so the summary email was not sent.

## 2026-09-27 (weekly sweep, window 2026-09-13 to 2026-09-27)
Test run of the Weekly job. 241 tool rows total (1 new). 97 dated updates recorded across 74 tool rows; 138 rows checked with no change in the window.

### New tools
- Red Hat agentic-threat-modeling (Threat Modeling, open source, Apache 2.0): Lola module that runs STRIDE/PASTA/LINDDUN/VAST/Attack Trees/OCTAVE inside Claude Code, Cursor and Gemini CLI, emits THREAT_MODEL.md with code-cited threats. https://github.com/RedHatProductSecurity/agentic-threat-modeling (open-sourced 2026-09-21)

### AI changes and notable updates
- Checkmarx One (SAST): Triage and Remediation Assist agent introduced 17 Sep (reachability scoring, auto-PR fixes on GitHub, credit-metered). ai_capabilities, key_features, pricing_model updated.
- Black Duck Polaris (SAST, SCA, Secrets, SBOM, Platforms): September update 23 Sep adds bring-your-own-LLM for Signal AI (OpenAI, Azure OpenAI, Bedrock, Vertex) across six agents, central rule profiles, self-hosted SCM PR flows. On-prem AI now possible; ai_maturity and ai_capabilities updated.
- GitHub Advanced Security (SAST, Secrets, SBOM, Platforms): GHAS configuration enforcement GA 15 Sep; AI Scan decoupled from CodeQL default setup 16 Sep (preview); agentic autofix now uses Copilot Memory 25 Sep (preview); CodeQL 2.27.1 25 Sep; enterprise credential inventory export GA 21 Sep.
- GitLab 19.4 (SAST, SCA, Secrets, Security Requirements, Platforms), 17 Sep: Advanced SAST adds Kotlin, Dart, Scala; Vulnerability Context Flow; vulnerability tools in the GitLab MCP Server; Automated Triage profiles; malicious package detection (Beta); auto-revocation of routable PATs; credit consumption order change (pricing_model updated on SCA row).
- HCL AppScan on Cloud (SAST, SCA, Secrets, Platforms), 27 Sep: AI SAST business-logic flaw detection; per-asset-group admin controls for AI Assistant, RapidFix, AI SAST and DAST IFA; SCA scans SCM repos and ZIPs from manifests.
- OpenText Fortify (SAST): VS Code extension 26.4 (approx. 20 Sep) applies Aviator fixes in-IDE and ships Fortify MCP servers.
- Aikido Security (SAST, SCA, Secrets, Platforms): Altar-1 open-weight security model (pruned GLM-5.3, 328 GB, runs on 4x H200) released 21 Sep for air-gapped pentesting and code review; AWS Security Competency 17 Sep. On-prem AI now yes.
- Cycode (SAST/Bearer, SCA, Secrets, Platforms): Workstation Protection early access 23 Sep, MDM-deployed control that intercepts package installs and secrets in agent prompts, with MCP inventory.
- Semgrep (SAST, SCA, Secrets, Platforms): Supply Chain malware detection and response automation GA 24 Sep; Guardian status reporting inside AI coding agents (week of 14 Sep).
- OX Security (Platforms): OX Cloud GA 16 Sep (CNAPP plus AI-DR and agentic attack surface management).
- Wiz (Platforms): MCP WIN partner endpoint GA 22 Sep; Leader in Forrester Wave Proactive Security Platforms Q3 2026 (24 Sep). CrowdStrike Falcon also a Leader in the same Wave; analyst_position updated on both.
- Phoenix Security (Platforms): MIT-licensed CLI and MCP server open-sourced 21 Sep.
- Apiiro (Platforms): Claude Compliance API integrated into the Software Graph for AI-BOM 24 Sep.
- OWASP DefectDojo Pro 3.3.100 (14 Sep) and 3.3.200 (22 Sep): DAST, AI Agent Red Teaming in Sensei, Cortex connectors.
- Lineaje (SBOM): Frontier Defense multi-agent AI engine GA 25 Sep.
- OWASP cdxgen v13.2.0 (22 Sep): Kotlin evidence, expanded AI-BOM and MCP coverage, agentic project type.
- Kusari (SBOM): open-source Waybill SBOM toolkit releases v0.8.0 to v0.10.0-alpha.1 (17 to 23 Sep); row updated, not added as a separate entrant (first release pre-window).
- ThreatModeler Nexus: FedRAMP Moderate authorization 14 Sep (deployment updated).
- Devici 2.30.0 (16 Sep): role-scoped API tokens for MCP, /sync-devici-threat-model prompt with SD Elements.
- Threat Canvas: SecureFlag MCP Server 15 Sep generates models from user stories in Claude Code and Codex.
- DevArmor: IriusRisk XML import and migration path 23 Sep.
- GitGuardian: Detection Engine 2.172 (14 Sep, 10 detectors, 8 analyzers); Docker Sandbox Mixin Kit with ggshield AI hooks 24 Sep.
- Veracode: DryRun Security integration 16 Sep; static engine v2026.09 improves .NET CWE-259/798 detection 23 Sep; CLI 2.52.1 speeds up 'veracode fix sca' 23 Sep.
- Kodem: joined OpenAI Daybreak Cyber Partner Program 22 Sep. CodeRabbit Triage 15 Sep. Cursor Security Review launched 23 Sep.
- Chainguard: Sovereign Artifacts beta 15 Sep; FIPS 140-3 validation 24 Sep. Snyk: custom CA support 16 Sep, CLI 1.1307.3 18 Sep. JFrog Xray 3.154.4/8: Curation for Debian and Ubuntu 14 to 16 Sep.
- Releases only: Dependency-Track 4.14.4 (14 Sep, CycloneDX 1.7 ingestion) and 5.1.1 (20 Sep); Syft 1.52.0 and Grype 0.119.0 (17 Sep); OSV-Scanner 2.6.0 (14 Sep); 2ms 5.4.0 (16 Sep); agent-bom 0.105.0 and 0.106.1; Precogly 0.4.0 (15 Sep); OWASP Cornucopia 3.5.4 (20 Sep); Corgea changelogs 17 and 24 Sep; Sonatype DoD Platform One Awardable 22 Sep; npm stage-only tokens 18 Sep.
- Shutdown: Remy Security (Security Requirements) verified inactive 27 Sep; remysec.com no longer serves the product and YC lists the company as inactive. Row kept, marked in cons_known_gaps.

### Checked, no change in window
- SAST: Veracode Static Analysis, Snyk Code, SonarQube, Opengrep, Contrast Security, Endor Labs, DryRun Security, ZeroPath, Bandit, Brakeman, SpotBugs + Find Security Bugs, gosec, PMD, Pixee, Nullify, Arnica, Greptile, Jit
- SCA: Mend SCA, Sonatype Lifecycle, Checkmarx SCA, Endor Labs, FOSSA, Socket, Phylum, Arnica, OWASP Dependency-Check, Trivy, Scantist, OpenText Fortify Software Composition Analysis, Kusari, Lineaje, Xygeni, SafeDep, AIR
- Secret Scanning: TruffleHog, Gitleaks, Betterleaks, Snyk Secrets, Nightfall AI, HCP Vault Radar, Entro Security, Legit Security, Arnica, detect-secrets, Spectral, Jit, Cremit, OpenText Fortify SAST hardcoded-credential detection
- SBOM and AI BOM: Anchore Enterprise, Trivy, Microsoft sbom-tool, SPDX tools, FOSSA, Snyk SBOM and Snyk AI-BOM, JFrog Xray, Mend SCA SBOM and Mend AI, Cybeats SBOM Studio, Finite State Platform, Manifest Platform, Chainloop, bomctl, OWASP AIBOM Generator, HiddenLayer AISec Platform, Palo Alto Networks Prisma AIRS, Legit Security ASPM, Noma Security, Prompt Security, AIR, ZeroPath AI-BOM, Checkmarx One SBOM
- Threat Modeling: IriusRisk, SD Elements, Microsoft Threat Modeling Tool, OWASP Threat Dragon, OWASP pytm, Threagile, STRIDE GPT, Threat Composer, Seezo, Aribot, Tutamen Threat Model Automator, CAIRIS, ThreatSpec, Threatest, Oplane, Microsoft Copilot-based threat modeling, Amazon Q Developer, Shostack + Associates tools, MITRE ATLAS, OWASP AI Exchange, NIST AI RMF 1.0 and Generative AI Profile, MAESTRO, Microsoft AI/ML threat modeling guidance and Google SAIF Risk Map
- Security Requirements: SD Elements, Devici, IriusRisk, ThreatModeler Nexus, Jit, Secure Code Warrior, SAMMY, OWASP SecurityRAT, OWASP ASVS 5.0 and ASVS tooling, OWASP SAMM 2.1 and SAMM tooling, OWASP MASVS 2.1, OWASP DSOMM, OWASP Application Security Requirement checklists, OpenCRE and OpenCRE Chat, Conviso Platform, Aptori, ArmorCode ASPM, Kondukto ASPM, Tromzo ASPM, Jama Connect, Seezo, Prime Security, RequirementONE
- Platforms and ASPM: Checkmarx One, OpenText Application Security, ArmorCode Agentic Control Plane, Legit Security AI-native ASPM, Cortex Cloud Application Security, Orca Security, Sysdig Secure, Endor Labs, Mend.io AppSec Platform, JFrog Platform, Sonatype Nexus One Platform, Contrast One, Escape, Pixee, ZeroPath, DryRun Security, Nullify, Gomboc AI, Seemplicity, Jit Open ASPM, Invicti ASPM

### Caveats
- Not verifiable this run (vendor pages blocked or undated): Mobb, Amplify Security, Aptori, Faraday, Clover, Tromzo, Echo, Konvu, Tidal Cyber, securiCAD, Prime Security, Oligo, Safeguard, Cisco AI Defense, Scribe, sbom-scorecard, OWASP Top 10 for LLM 2026 and Agentic Security Initiative pages. Sonatype and Checkmarx help-centre release notes render client-side, so their September entries were not read.
- Backlog for the monthly re-verification (outside this window): SD Elements 2026.8.2/2026.9.1 shipped ASVS 5.0 and EU CRA content and MCP on by default (file still says paid upgrade and ASVS 5.0 unconfirmed); ThreatModeler acquired IriusRisk 8 Jan 2026; Torq acquired Jit 19 May 2026; OWASP MASTG v2.0.0 shipped 30 Jun 2026; Prime Security domain is primesec.ai; GitHub MCP Server secret scanning went GA 2026-05-05 (row says preview).

## 2026-09-27
- Added Precogly (OWASP Precogly) to Threat Modeling after user flag. 240 tool rows total.

## 2026-09-26
- Initial build: 239 tool rows across SAST (33), SCA (33), Secret Scanning (25), SBOM and AI BOM (42), Threat Modeling (35), Security Requirements (28), Platforms and ASPM (43). 39 flagged as 2025-2026 entrants.
