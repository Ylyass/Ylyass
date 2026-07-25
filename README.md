<!-- GitHub profile README: github.com/Ylyass -->

<p align="center">
  <img
    src="https://raw.githubusercontent.com/Ylyass/Ylyass/main/assets/banner.png"
    width="100%"
    alt="Ylyas Nurmuhammedov — Security Engineer"
  />
</p>

<p align="center">
  <a href="https://portfolio-ylyass-projects.vercel.app/">
    <img src="https://img.shields.io/badge/PORTFOLIO-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/ylyasnurmuhammedov">
    <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:nurmuhammedovylyas0909@gmail.com">
    <img src="https://img.shields.io/badge/CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## Selected Work

### MCP Privilege Profiler

**Least-privilege security proxy for AI agents**

A Python 3.13 security proxy positioned between AI-agent hosts and MCP tool servers. It profiles the tools required for a task, restricts unnecessary access, detects changes to tool definitions, and exports privacy-minimized security events to Wazuh.

**Implemented controls**

- `ALLOW`, `REQUIRE_APPROVAL`, and `DENY` decisions
- Task-specific tool permissions
- Filtered tool visibility
- Path and host restrictions
- Usage limits
- Schema-drift detection
- Fail-closed handling
- Human-review controls
- Wazuh audit events

**Current results**

- Integrated with Anthropic Claude Code
- Completed two controlled dependency-review runs
- Captured six successful MCP tool calls
- Validated blocked actions through searchable Wazuh alerts
- 159 automated tests passing
- Security, integration, property, and benchmark testing

<p>
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-F59E0B?style=flat-square" alt="In development">
  <img src="https://img.shields.io/badge/PYTHON-3.13-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.13">
  <img src="https://img.shields.io/badge/TESTS-159%20PASSING-22C55E?style=flat-square" alt="159 tests passing">
  <img src="https://img.shields.io/badge/WAZUH-INTEGRATED-005571?style=flat-square" alt="Wazuh integrated">
</p>

> Runs locally. The public repository will be linked after the source code and documentation are prepared.

### Architecture

<p align="center">
  <img
    src="https://raw.githubusercontent.com/Ylyass/Ylyass/main/assets/mcp_architecture.png"
    width="100%"
    alt="MCP Privilege Profiler architecture"
  />
</p>

---

<table>
<tr>
<td width="50%" valign="top">

### [LLM Red Team Assessment](https://github.com/Ylyass/LLM-RedTeam-assessment)

**Adversarial testing of a locally hosted Llama 3.2 model**

A repeatable Garak assessment covering jailbreak and prompt-injection behaviour.

The repository includes:

- Documented test environment
- Baseline assessment
- Successful and failed cases
- Failure-pattern analysis
- OWASP LLM01 mapping
- System-level mitigation
- Before-and-after comparison
- Remaining risks and limitations

<p>
  <a href="https://github.com/Ylyass/LLM-RedTeam-assessment">
    <img src="https://img.shields.io/badge/REPOSITORY-VIEW-181717?style=flat-square&logo=github&logoColor=white" alt="View repository">
  </a>
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-22C55E?style=flat-square" alt="Completed">
  <img src="https://img.shields.io/badge/OWASP-LLM01-000000?style=flat-square&logo=owasp&logoColor=white" alt="OWASP LLM01">
</p>

</td>

<td width="50%" valign="top">

### Wazuh SIEM Home Lab

**Windows endpoint monitoring and detection validation**

A local lab collecting Windows Event Logs and Sysmon telemetry for process, command-line, authentication, PowerShell, and file activity.

Investigations included:

- Simulated brute-force activity
- Encoded PowerShell execution
- Critical-alert investigation
- Process relationship analysis
- False-positive confirmation
- Scheduled-task detection gap
- Detection-improvement documentation

<p>
  <img src="https://img.shields.io/badge/STATUS-LOCAL%20LAB-3B82F6?style=flat-square" alt="Local lab">
  <img src="https://img.shields.io/badge/WAZUH-SIEM-005571?style=flat-square" alt="Wazuh">
  <img src="https://img.shields.io/badge/SYSMON-WINDOWS-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Sysmon">
</p>

<sub>A public documentation repository will contain redacted screenshots, investigation reports, architecture, queries, and reusable configuration examples.</sub>

</td>
</tr>
</table>

---

### [Swinburne Campus Mobile App](https://github.com/islam-mamedov/Final-Year-Project-B)

**Cross-platform campus navigation and student-support application**

A team final-year project developed with Next.js, TypeScript, Capacitor, and Supabase.

**My contributions**

- Backend route logic
- Assistant service integration
- Request filtering
- API rate limiting
- JWT authentication
- Database Row-Level Security
- Functional and security testing
- High-request-volume testing
- Technical documentation

The application was tested with approximately 80 students and received 92% positive feedback.

<p>
  <a href="https://final-year-project-b-dx9c.vercel.app/">
    <img src="https://img.shields.io/badge/LIVE%20APPLICATION-OPEN-22C55E?style=flat-square&logo=vercel&logoColor=white" alt="Live application">
  </a>
  <a href="https://github.com/islam-mamedov/Final-Year-Project-B">
    <img src="https://img.shields.io/badge/TEAM%20REPOSITORY-VIEW-181717?style=flat-square&logo=github&logoColor=white" alt="Team repository">
  </a>
</p>

---

## Technical Areas

<table>
<tr>
<td width="33%" valign="top">

### Security Engineering

`Least Privilege`  
`Policy Enforcement`  
`Fail-Closed Design`  
`Audit Logging`  
`Schema-Drift Detection`  
`RBAC`  
`Row-Level Security`  
`Rate Limiting`

</td>

<td width="33%" valign="top">

### Detection and Testing

`Wazuh`  
`Sysmon`  
`Windows Event Logs`  
`Garak`  
`OWASP LLM Top 10`  
`MITRE ATT&CK`  
`Atomic Red Team`  
`Alert Investigation`

</td>

<td width="33%" valign="top">

### Development

`Python`  
`TypeScript`  
`PowerShell`  
`Bash`  
`Docker`  
`GitHub Actions`  
`pytest`  
`Hypothesis`

</td>
</tr>
</table>

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=python,ts,js,powershell,bash,docker,git,github,githubactions,linux,windows,aws,supabase,vercel,vscode&perline=15"
    alt="Development tools and platforms"
  />
</p>

---

## Certifications and Training

| Credential | Issuer | Status |
|---|---|---|
| Cisco CyberOps Associate | Cisco Networking Academy | Completed · 2026 |
| CCNA: Introduction to Networks | Cisco Networking Academy | Completed · 2025 |
| CCNA: Switching, Routing and Wireless Essentials | Cisco Networking Academy | Completed · 2025 |
| CCNA: Enterprise Networking, Security and Automation | Cisco Networking Academy | Completed · 2025 |
| Security Analyst Pathway | TryHackMe | In progress |

---

## Development Activity

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=Ylyass&theme=github-compact&hide_border=true&area=true"
    width="100%"
    alt="Ylyas Nurmuhammedov GitHub contribution activity"
  />
</p>

---

<p align="center">
  <a href="https://portfolio-ylyass-projects.vercel.app/">Portfolio</a>
  ·
  <a href="https://www.linkedin.com/in/ylyasnurmuhammedov">LinkedIn</a>
  ·
  <a href="mailto:nurmuhammedovylyas0909@gmail.com">Email</a>
</p>
