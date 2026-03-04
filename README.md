# RFC 9116 (security.txt) adoption – Switzerland (sample)

This repository contains a snapshot of the adoption of RFC 9116 (`/.well-known/security.txt`) and related vulnerability disclosure practices among selected Swiss organisations.

## Legend

✅ Yes  
❌ No  
⚪ No information / not declared  

---

# Summary by Industry

| Industry | Companies | security.txt present | RFC 9116 compliant | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|
| Finance / Banking | 8 | 7/8 | 6/8 | 3/8 | 3/8 | 3/8 | 3/8 | 2/8 |
| Telecommunications | 8 | 5/8 | 4/8 | 3/8 | 2/8 | 3/8 | 2/8 | 1/8 |
| Utilities / Energy | 8 | 7/8 | 6/8 | 2/8 | 2/8 | 1/8 | 2/8 | 1/8 |
| Retail | 8 | 4/8 | 4/8 | 2/8 | 2/8 | 2/8 | 1/8 | 1/8 |

---

# Detailed Results

## Utilities / Energy

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Alpiq | https://www.alpiq.com/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Axpo | https://www.axpo.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| BKW | https://www.bkw.ch/.well-known/security.txt | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| EBL | https://www.ebl.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | Compass Security Managed Bug Bounty |
| EKZ | https://www.ekz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EWL | https://www.ewl-luzern.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Repower | https://www.repower.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| WWZ | https://www.wwz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |

---

## Finance / Banking

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Julius Baer | https://www.juliusbaer.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| PostFinance | https://www.postfinance.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Raiffeisen | https://www.raiffeisen.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Swissquote | https://www.swissquote.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| UBS | https://www.ubs.com/.well-known/security.txt | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| ZKB | https://www.zkb.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ZKB Bug Bounty Program |
| Zuger Kantonalbank | https://www.zugerkb.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Credit Suisse (legacy) | https://www.credit-suisse.com/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |

---

## Telecommunications

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Swisscom | https://www.swisscom.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Swisscom Bug Bounty Programme |
| Sunrise | https://www.sunrise.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Salt | https://www.salt.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Init7 | https://www.init7.net/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Quickline | https://www.quickline.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| WWZ Telekom | https://www.wwz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Netplus | https://www.netplus.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Green | https://www.green.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | ⚪ |

---

## Retail

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Migros | https://www.migros.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚪ |
| Coop | https://www.coop.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Digitec | https://www.digitec.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Galaxus | https://www.galaxus.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Brack | https://www.brack.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Manor | https://www.manor.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Lidl Schweiz | https://www.lidl.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| Aldi Suisse | https://www.aldi-suisse.ch/.well-known/security.txt | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
