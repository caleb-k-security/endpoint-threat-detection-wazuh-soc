# Brute Force Detection

## Alert Source
Wazuh SIEM

## Detection Logic
Multiple failed login attempts detected from a single source IP within a short time window.

## Indicators
- Event ID: 4625
- Same username
- Same source IP
- Rapid frequency

## Severity
Medium

## Analyst Interpretation
Pattern consistent with automated brute-force authentication attempt.
