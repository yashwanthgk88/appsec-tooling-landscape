# Change log

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
