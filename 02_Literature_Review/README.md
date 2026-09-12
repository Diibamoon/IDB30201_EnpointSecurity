
## 2. Comparison of Detection Paradigms

| Parameter | Signature-Based (AV) | Heuristic-Based | Behavioural ML (Proposed) |
| :--- | :--- | :--- | :--- |
| **Detection Basis** | Known file hashes, byte patterns, YARA rules | Static rule checks, API import tables | Dynamic endpoint activity, runtime metrics, entropy |
| **Zero-Day Resilience** | Very Poor (fails on new hashes) | Moderate (can be bypassed via packing) | **High** (detects malicious operational behavior) |
| **Obfuscation Resistance** | Vulnerable to polymorphism/packing | Vulnerable to code mutation | **Robust** (focuses on observable OS impact) |
| **False Positive Rate** | Minimal on known binaries | Moderate | Low when multi-feature ensemble is applied |
| **Latency** | Instantaneous lookup | Fast | Real-time sliding window (sub-second) |

---
