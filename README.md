# Deloitte Data Analytics Case Study - Daikibo

> Forensic analysis of IoT telemetry data & gender pay equality audit for 4 global factories.

### Client - Daikibo
4 Plants: Meiyo (Tokyo), Seiko (Osaka), Berlin, Shenzhen.
Problem: Machine breakdowns & Pay inequality complaints.

### What I Did

**1. Telemetry + Tableau**
- Merged JSON files into CSV
- Built Tableau Dashboard (Downtime per Factory as Filter)
- Finding: Meiyo factory had highest downtime. 1 Unhealthy = 10 mins.

**2. Equality Audit (Excel)**
Formula used:
=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))

Logic:
- 0 = Perfect Equality
- -10 to 10 = Fair
- -20 to -11 and 11 to 20 = Unfair
- >20 or <-20 = Highly Discriminative

Findings:
- C-Level (-25), VP (-26) at Meiyo = Highly Discriminative
- Sr. Manager (-21) at Seiko/Shenzhen = Highly Discriminative
- Jr. Roles = Mostly Fair

### Tools
Excel, Tableau

### Author
forgeBySandi
