# RFC 9116 (security.txt) adoption – Switzerland

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
| Goverment / Public Sector | 7/8 | 7/8 | 7/8 | 7/8 | 5/8 | 1/8 | 4/8 | 2/8 |

---

# Detailed Results

## Utilities / Energy

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Alpiq | https://www.alpiq.com/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Axpo | https://www.axpo.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| BKW | https://www.bkw.ch/.well-known/security.txt | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EBL | https://www.ebl.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | Compass Security Managed Bug Bounty |
| EKZ | https://www.ekz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EWL | https://www.ewl-luzern.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Repower | https://www.repower.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| WWZ | https://www.wwz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |

---

## Finance / Banking

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| UBS | https://www.ubs.com/.well-known/security.txt | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Julius Baer | https://www.juliusbaer.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Raiffeisen Switzerland | https://www.raiffeisen.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | GObugfree |
| Zürcher Kantonalbank | https://www.zkb.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ZKB Bug Bounty Program (Zürcher Kantonalbank) |
| Zuger Kantonalbank | https://www.zugerkb.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| PostFinance | https://www.postfinance.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Swissquote | https://www.swissquote.com/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| TWINT | https://www.twint.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |

---

## Telecommunications

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Swisscom | https://www.swisscom.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Swisscom Bug Bounty Programme |
| Sunrise | https://www.sunrise.ch/.well-known/security.txt | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Salt | https://www.salt.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Init7 | https://www.init7.net/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Quickline | https://www.quickline.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| WWZ Telekom | https://www.wwz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| iWay | https://www.iway.ch/.well-known/security.txt | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Green | https://www.green.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | ❌ |

---

## Retail

| Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|
| Migros | https://www.migros.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Coop | https://www.coop.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | YesWeHack private bug bounty program |
| Galaxus Digitec | https://www.galaxus.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| ALDI SUISSE | https://www.aldi-suisse.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| lidl.ch | https://www.lidl.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Brack | https://www.brack.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Manor | https://www.manor.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| volg.ch | https://www.volg.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |

---

## Government / Public Sector

| Industry | Company | .well-known/security.txt URL | security.txt present | Expires field present | RFC 9116 compliant | Contact email present | VDP present | Safe Harbor present | Scope defined | Bug bounty mentioned | Bug bounty program |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Government / Public Sector | admin.ch | https://www.admin.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | Bug Bounty Program of the Federal Administration (NCSC) |
| Government / Public Sector | zh.ch | https://www.zh.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| Government / Public Sector | zg.ch | https://www.zg.ch/.well-known/security.txt | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Government / Public Sector | stadt-zuerich.ch | https://www.stadt-zuerich.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Government / Public Sector | ethz.ch | https://www.ethz.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ |
| Government / Public Sector | epfl.ch | https://www.epfl.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Government / Public Sector | post.ch | https://www.post.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| Government / Public Sector | SBB | https://www.sbb.ch/.well-known/security.txt | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Intigriti |
