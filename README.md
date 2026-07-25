<!--
GitHub Profile README
Repository: Ylyass/Ylyass
-->

<p align="center">
  <img src="./assets/banner.png" width="100%" alt="Ylyas Nurmuhammedov">
</p>

<h1 align="center">Ylyas Nurmuhammedov</h1>

<p align="center">
  <strong>Security Engineer</strong><br>
  AI Agent Security · Detection Engineering · Security Testing
</p>

<p align="center">
  <a href="https://portfolio-ylyass-projects.vercel.app/">
    <img src="https://img.shields.io/badge/PORTFOLIO-0A66C2?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
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

<table>
<tr>
<td width="50%" valign="top">

### MCP Privilege Profiler

**Least-privilege security proxy for AI agents**

A Python security layer placed between an AI agent and MCP tool servers.

It records the tools required for a task, limits unnecessary access, and applies explicit:

- `ALLOW`
- `REQUIRE_APPROVAL`
- `DENY`

Additional controls include tool-schema change detection, path and host restrictions, usage limits, filtered tool visibility, fail-closed behavior, and Wazuh audit events.

**Current result**

- Claude Code integration
- Two controlled dependency-review runs
- Six MCP tool calls captured
- 159 automated tests passing
- Security, integration, property, and benchmark testing

<p>
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-F59E0B?style=flat-square" alt="In development">
  <img src="https://img.shields.io/badge/PYTHON-3.13-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.13">
  <img src="https://img.shields.io/badge/TESTS-159%20PASSING-22C55E?style=flat-square" alt="159 tests passing">
</p>

<sub>Runs locally. Public repository will be linked after the code and documentation are ready.</sub>

</td>

<td width="50%" valign="top">

### [LLM Red Team Assessment](https://github.com/Ylyass/LLM-RedTeam-assessment)

**Adversarial testing of a locally hosted Llama 3.2 model**

A repeatable assessment using Garak to test jailbreak and prompt-injection behavior.

The repository documents:

- Test environment and model version
- Baseline results
- Successful and failed attack cases
- Failure-pattern analysis
- OWASP LLM01 mapping
- System-level mitigation
- Before-and-after comparison
- Remaining risks and limitations

<p>
  <a href="https://github.com/Ylyass/LLM-RedTeam-assessment">
    <img src="https://img.shields.io/badge/REPOSITORY-VIEW-181717?style=flat-square&logo=github&logoColor=white" alt="Repository">
  </a>
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-22C55E?style=flat-square" alt="Completed">
  <img src="https://img.shields.io/badge/OWASP-LLM01-000000?style=flat-square&logo=owasp&logoColor=white" alt="OWASP LLM01">
</p>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Wazuh SIEM Home Lab

**Windows monitoring and detection-validation environment**

A local Wazuh lab collecting Windows Event Logs and Sysmon telemetry for:

- Process creation
- Command-line activity
- Authentication events
- File activity
- PowerShell execution

Investigations covered simulated brute-force activity, encoded PowerShell execution, a critical alert, false-positive confirmation, and a scheduled-task detection gap.

The public repository will contain investigation reports, redacted screenshots, architecture, queries, and reusable configuration examples. Virtual machines, credentials, and private logs will not be uploaded.

<p>
  <img src="https://img.shields.io/badge/STATUS-DOCUMENTATION%20IN%20PROGRESS-3B82F6?style=flat-square" alt="Documentation in progress">
  <img src="https://img.shields.io/badge/WAZUH-SIEM-005571?style=flat-square" alt="Wazuh">
  <img src="https://img.shields.io/badge/SYSMON-WINDOWS-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Sysmon">
</p>

</td>

<td width="50%" valign="top">

### [Swinburne Campus Mobile App](https://github.com/islam-mamedov/Final-Year-Project-B)

**Campus navigation and student-support application**

A team final-year project developed with Next.js, TypeScript, Capacitor, and Supabase.

My work covered:

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

</td>
</tr>
</table>

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
`Tool-Change Detection`  
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
  <img src="https://skillicons.dev/icons?i=python,ts,js,powershell,bash,docker,git,github,githubactions,linux,windows,aws,supabase,vercel,vscode&perline=15" alt="Tools and platforms">
</p>

---

## Current Project Architecture

```text
Claude Code
     │
     │ MCP requests
     ▼
MCP Privilege Profiler
     │
     ├── Tool inventory
     ├── Task policy
     ├── ALLOW / APPROVAL / DENY
     ├── Schema-change detection
     ├── Path and host restrictions
     └── Audit events
              │
              ▼
          Wazuh SIEM
```

---

## Certifications and Training

<table>
<tr>
<th>Credential</th>
<th>Issuer</th>
<th>Status</th>
</tr>

<tr>
<td>Cisco CyberOps Associate</td>
<td>Cisco Networking Academy</td>
<td>Completed · 2026</td>
</tr>

<tr>
<td>CCNA: Introduction to Networks</td>
<td>Cisco Networking Academy</td>
<td>Completed · 2025</td>
</tr>

<tr>
<td>CCNA: Switching, Routing and Wireless Essentials</td>
<td>Cisco Networking Academy</td>
<td>Completed · 2025</td>
</tr>

<tr>
<td>CCNA: Enterprise Networking, Security and Automation</td>
<td>Cisco Networking Academy</td>
<td>Completed · 2025</td>
</tr>

<tr>
<td>Security Analyst Pathway</td>
<td>TryHackMe</td>
<td>In progress</td>
</tr>
</table>

---

## GitHub Activity

<p align="center">
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api?username=Ylyass&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true"
    alt="Ylyas GitHub statistics"
  >
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ylyass&layout=compact&hide_border=true&theme=github_dark"
    alt="Most used languages"
  >
</p>

<p align="center">
  <img
    width="98%"
    src="https://github-readme-activity-graph.vercel.app/graph?username=Ylyass&theme=github-compact&hide_border=true"
    alt="GitHub contribution activity"
  >
</p>

> GitHub also displays the official contribution graph below this README. Private contribution details remain hidden.

---

## Contact

<p align="center">
  <a href="https://portfolio-ylyass-projects.vercel.app/">Portfolio</a>
  ·
  <a href="https://www.linkedin.com/in/ylyasnurmuhammedov">LinkedIn</a>
  ·
  <a href="mailto:nurmuhammedovylyas0909@gmail.com">Email</a>
</p>
