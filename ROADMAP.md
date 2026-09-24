# 🗺️ Roadmap

A realistic plan for **3–5 hours per week**. Each week ends with **one write-up** in this repo.

Legend: ⬜ not started · 🟡 in progress · ✅ done

---

## Phase 1: SOC fundamentals (weeks 1–8)

| Week | Topic | Practice | Write-up | Status |
|---|---|---|---|---|
| 1 | What a SOC does · the alert lifecycle · CIA triad | Intro SOC rooms on TryHackMe | Notes: *How a SOC works* | ⬜ |
| 2 | Windows Event Logs (4624, 4625, 4688, 4720…) | Event Viewer on your own machine | Cheat-sheet: key Event IDs | ⬜ |
| 3 | Linux logs (auth.log, syslog) | Find a brute-force attempt in auth.log | Lab write-up | ⬜ |
| 4 | SIEM basics: searching & filtering | Splunk or Elastic free labs | Lab write-up | ⬜ |
| 5 | Alert triage: true vs false positive | LetsDefend free alerts | Incident report #1 | ⬜ |
| 6 | Brute-force & suspicious logins | SIEM investigation lab | Incident report #2 | ⬜ |
| 7 | MITRE ATT&CK: mapping what you see | Map reports #1–#2 to ATT&CK | Update both reports | ⬜ |
| 8 | Review month | Pick your best investigation | Polished case study | ⬜ |

## Phase 2: Network traffic analysis (weeks 9–12)

| Week | Topic | Practice | Write-up | Status |
|---|---|---|---|---|
| 9 | Wireshark basics & filters | Analyze your own traffic | Cheat-sheet: Wireshark filters | ⬜ |
| 10 | Spotting scans & suspicious traffic | PCAP challenge | Lab write-up | ⬜ |
| 11 | DNS & HTTP analysis | PCAP challenge | Lab write-up | ⬜ |
| 12 | Review | Best PCAP investigation | Case study | ⬜ |

## Later phases

- **Phase 3:** Phishing & social-engineering analysis (email headers, URLs, attachments)
- **Phase 4:** DFIR (endpoint artifacts, timelines, memory basics)
- **Phase 5:** Web security (OWASP Top 10, PortSwigger Web Security Academy) → bug bounty
- **Phase 6:** Malware analysis basics (static triage, sandboxes)

---

## Weekly routine (≈4 hours)

1. **~2.5 h:** do the lab or course.
2. **~1 h:** write it up using a template from [`templates/`](templates/).
3. **~0.5 h:** commit, update the progress log in the main README, and tick the week here.

> Rule: **no write-up, no progress.** A finished lab doesn't count until it's documented.
