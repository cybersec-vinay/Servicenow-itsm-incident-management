# End-to-End Incident Lifecycle & Automation Test Cases

| Test ID | Scenario | Persona / Trigger | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01** | End-user ticket submission | `priya.fin` (Finance Dept) | User sees Self-Service only; submits Incident | Passed |
| **TC-02** | Tier 1 triage & escalation | `rohan.it` (IT Service Desk) | Inherits `itil` role; logs work notes & escalates to Network | Passed |
| **TC-03** | Tier 2 resolution | `ananya.net` (Network Eng) | Resolves incident with resolution code & notes | Passed |
| **TC-04** | Automated Assignment Rule | `Category = Network` | Auto-routes to **Network Engineering** without manual triage | Passed |
| **TC-05** | Custom 4-Hour SLA | Assigned to `Network Engineering` | Attaches 4-hour Resolution SLA; pauses on `On Hold` | Passed |
