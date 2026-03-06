# Web Security Scanner 🛡️

A high-performance, multithreaded security tool built in Python to identify subdomains and potential vulnerabilities.



## 🌟 Key Features
- **Concurrent Execution:** Uses `ThreadPoolExecutor` for 10x faster scanning.
- **Clean Output:** Categorizes results by HTTP status codes (200, 403, 404).
- **Error Resilient:** Advanced exception handling for connection timeouts.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Requests, Concurrent.Futures
- **Methodology:** OSINT & Brute-force

## 🚀 Getting Started

### Installation
```bash
git clone [https://github.com/Aamir-Akram/web-security-scanner.git](https://github.com/Aamir-Akram/web-security-scanner.git)
cd web-security-scanner
pip install -r requirements.txt
