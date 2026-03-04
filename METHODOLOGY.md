# Methodology

This repository documents the adoption of **RFC 9116 (security.txt)** among selected Swiss organisations.

The goal is to provide a **transparent snapshot of adoption**, not to rate or assess the overall security posture of any organisation.

## Scope

- Organisations were selected manually across several industries.
- The dataset is **not statistically representative**.
- The analysis reflects a **point-in-time observation**.

## security.txt lookup

For each organisation the file was checked at: https://www.[example.com]/.well-known/security.txt

A file was considered **present** only if:

- HTTP status = 200  
- Content-Type = `text/plain`  
- the file contains typical fields such as `Contact`, `Expires`, or `Policy`.

HTML pages (e.g. "Page not found") were treated as **not present**.

## RFC compliance (simplified)

A file was considered **RFC compliant** if it contains:

- `Contact:` field  
- `Expires:` field

## Additional checks

If present, the `security.txt` file was used to check for:

- contact email (`Contact: mailto:`)
- vulnerability disclosure policy (`Policy:` link)
- safe harbor statement
- defined scope
- bug bounty mention or program

If information could not be verified directly from `security.txt` or the linked policy, it was recorded as **No information**.

## Important note

This project is intended to **raise awareness and transparency** around RFC 9116 adoption.  
It should be interpreted as **observational data**, not as a security assessment.
