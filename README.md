# August Cyber Plugin for Cursor & Claude

Security skill and remote MCP connector by [August Cyber](https://august.so).

## What This Plugin Includes

- **Remote MCP Connector (`https://mcp.august.so/mcp`):** Zero-auth, read-only Streamable HTTP MCP server exposing three tools:
  - `audit_mcp_schema`: Audits MCP `tools/list` JSON definitions against the 2026 MCP Security Checklist (35 testable controls).
  - `check_security_posture`: Strictly passive check of HTTPS headers (HSTS, CSP, X-Frame-Options, CORS), `/.well-known/security.txt`, and DNS SPF/DMARC records.
  - `scope_staging_pentest`: Builds a 48 to 72-hour staging audit plan, 15-minute intake checklist, and SOC 2 evidence map for Vanta, Drata, Sprinto, and Secureframe.
- **MCP & API Security Audit Skill (`skills/mcp-security-audit/SKILL.md`):** Guides Cursor and Claude Code through auditing MCP tool handlers and multi-tenant authorization boundaries directly in your codebase.

## Links

- Website: [august.so](https://august.so)
- SOC 2 Penetration Testing: [august.so/soc2-pentest](https://august.so/soc2-pentest)
- MCP & AI Agent Security: [august.so/mcp-security](https://august.so/mcp-security)
- 2026 MCP Security Checklist: [github.com/augstai/mcp-security-checklist](https://github.com/augstai/mcp-security-checklist)
- GitHub Action: [github.com/marketplace/actions/august-cyber-pr-gate](https://github.com/marketplace/actions/august-cyber-pr-gate)
- Privacy Policy: [august.so/privacy](https://august.so/privacy)
- Terms of Service: [august.so/terms](https://august.so/terms)
- Contact: `hello@august.so`
