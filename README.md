<!-- GitHub profile README: github.com/Ylyass -->

<p align="center">
  <img
    src="./banner.png"
    width="100%"
    alt="Ylyas Nurmuhammedov — Security Engineer"
  />
</p>

<p align="center">
  <a href="https://portfolio-ylyass-projects.vercel.app/">
    <img
      src="https://img.shields.io/badge/PORTFOLIO-2563EB?style=for-the-badge&logo=vercel&logoColor=white"
      alt="Portfolio"
    />
  </a>
  <a href="https://www.linkedin.com/in/ylyasnurmuhammedov">
    <img
      src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"
      alt="LinkedIn"
    />
  </a>
  <a href="mailto:nurmuhammedovylyas0909@gmail.com">
    <img
      src="https://img.shields.io/badge/CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white"
      alt="Email"
    />
  </a>
</p>

<p align="center">
  Security engineering across AI-agent access control, adversarial testing,
  endpoint telemetry, and detection validation.
</p>

---

## Selected Work

### MCP Privilege Profiler

**Least-privilege security proxy for AI agents**

A Python 3.13 security proxy positioned between AI-agent hosts and MCP tool servers. It profiles the tools required for a task, restricts unnecessary access, detects unexpected changes to tool definitions, and exports privacy-minimized security events to Wazuh.

**Implemented controls**

- `ALLOW`, `REQUIRE_APPROVAL`, and `DENY` policy decisions
- Task-specific tool permissions
- Filtered tool visibility
- Path and host restrictions
- Usage limits
- Schema-drift detection
- Fail-closed handling
- Human-review controls
- Privacy-minimized Wazuh audit events

**Current results**

- Integrated with Anthropic Claude Code
- Completed two controlled dependency-review runs
- Captured six successful MCP tool calls
- Validated blocked actions through searchable Wazuh alerts
- 159 automated tests passing
- Security, integration, property, and benchmark testing

**Status:** In development  
**Stack:** Python 3.13 · MCP Python SDK · Pydantic · SQLite · Docker · Wazuh · pytest · Hypothesis

> Runs locally. The public repository will be linked after the source code and documentation are ready.

### Architecture

```mermaid
flowchart LR
    A[Anthropic Claude Code] --> B[MCP Privilege Profiler]

    B --> C[Tool Inventory]
    C --> D[Task-Specific Policy]
    D --> E{Policy Decision}

    E -->|ALLOW| F[MCP Tool Server]
    E -->|REQUIRE_APPROVAL| G[Human Review]
    G -->|Approved| F
    G -->|Rejected| H[Blocked]
    E -->|DENY| H

    B --> I[Schema-Drift Detection]
    B --> J[Path, Host and Usage Controls]

    E --> K[Privacy-Minimized Audit Event]
    K --> L[Wazuh SIEM]
    L --> M[Searchable Security Alert]
