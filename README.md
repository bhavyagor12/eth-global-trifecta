# CodeGuard - AI-Powered Code & Security Review 🚀

**CodeGuard** is a CLI tool for **security auditing** and **code quality analysis** using AI-powered insights. It supports **general code review** and **Solidity smart contract security audits** with Slither and AI-driven analysis.

## ✨ Features

- ✅ **AI-Powered Code Review** using SecretLLM
- ✅ **Security Audits for Solidity Contracts** (Slither, Mythril)
- ✅ **Performance & Best Practices Recommendations**
- ✅ **General Code Review for Python, JavaScript, and more**
- ✅ **Simple CLI Usage**

---

## 🔧 Installation

Install via **pip**:

```bash
pip install alkin-codeguard
```

Verify installation:

```bash
codeguard --help
```

---

## 🚀 Usage

### 🔍 General Code Review (Python, JS, etc.)

```bash
codeguard my_script.py
```

OR

```bash
codeguard my_code.js
```

**Output:**

- AI-powered analysis of security, quality, and performance issues.

### 🛡️ Solidity Security Audit

```bash
codeguard my_contract.sol
```

**What Happens?**

- Runs **Slither** for security analysis.
- Sends results + code to AI for deeper security insights.
- Returns **critical vulnerabilities, gas optimizations, and best practices**.

---

## 📌 Example Output

```bash
🔍 Analyzing my_contract.sol...
🛡️ Running Solidity Security Audits...
✅ No vulnerabilities found with Slither.

📌 **AI Security Insights:**
🚨 **Critical Vulnerabilities:**
- Reentrancy attack possible in function `withdraw()`

💡 **Best Practices:**
- Use `checks-effects-interactions` pattern
- Optimize gas usage with `constant` and `immutable`
```

---

## 🛠️ Requirements

- Python 3.7+
- `pip install -r requirements.txt`
- (For Solidity Audits) Install [Slither](https://github.com/crytic/slither)

---

## 🤝 Contributing

1. Clone the repo
   ```bash
   git clone https://github.com/bhavyagor12/eth-global-trifecta.git
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run tests
   ```bash
   pytest
   ```
4. Submit a PR 🚀

---

## 📜 License

MIT License
