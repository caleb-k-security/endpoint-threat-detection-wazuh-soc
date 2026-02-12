# Tier-1 Investigation Framework

## Analyst Workflow

1. Validate alert legitimacy
2. Confirm log integrity
3. Identify affected asset
4. Review event timeline
5. Analyze indicators
6. Check threat intelligence
7. Classify incident
8. Decide escalation

---

## Decision Criteria

False Positive
- Single event
- Internal system behavior
- No malicious indicators

True Positive
- Repeated events
- Automation pattern
- Suspicious source

---

## Escalation Rules

Escalate when:
- Persistence detected
- Malware execution observed
- Privilege escalation suspected
- External attacker confirmed

---

## Analyst Principle
A SOC analyst verifies evidence before concluding.
