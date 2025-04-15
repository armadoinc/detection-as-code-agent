<h1 align="center">
  <br>
  <br>
  Detection-as-Code Agent
  <br>
</h1>

<div align="center">

  ![VSCode Extension](https://img.shields.io/badge/VSCode-grey?style=for-the-badge&logo=visual-studio-code&logoColor=blue)
  ![Sigma](https://img.shields.io/badge/Sigma-grey?style=for-the-badge)
  ![KQL](https://img.shields.io/badge/KQL-grey?style=for-the-badge)
  ![SPL](https://img.shields.io/badge/SPL-grey?style=for-the-badge)
  [![MITRE ATT&CK](https://img.shields.io/badge/%20ATT%26CK%20v15-red?style=for-the-badge)](https://attack.mitre.org/)
  ![License](https://img.shields.io/badge/Apache%202.0-grey.svg?style=for-the-badge&logo=apache)
  
  ![Download Extension](https://img.shields.io/badge/Coming%20Soon-grey?style=for-the-badge&logo=visualstudiocode)
  ![Join Community](https://img.shields.io/badge/Coming%20Soon-grey?style=for-the-badge&logo=discord)
</br>
</br>

<p><strong>Note:</strong> This project is currently in development. Download links and community access will be available soon.</p>

# **Detection-as-Code Agent**
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#community">Community</a> •
  <a href="#license">License</a>
</div>

<br>

# 👋 Welcome to DACAgent

DACAgent is an autonomous detection-as-code agent that lives in your IDE. It's designed to help security engineers, threat hunters, and SOC analysts build threat detection rules and search queries in any language and for any platform.

## 🚀 What's DACAgent?

DACAgent is a VSCode extension that transforms how security teams develop and manage detection rules. It adapts to your security stack, helping you create, test, and deploy detection content faster than ever before.

### 🌟 Here's what DACAgent can do for you: <a name="features"></a>

- 💡 **Autonomous Detection Development**: Convert security concepts into working detection rules for any platform (Sigma, KQL, SPL, EQL, etc.)
- 🧠 **Contextual Awareness**: Understands your environment, data sources, and security stack
- 🛡️ **Multi-Platform Support**: Works with any SIEM or EDR platform's query language
- 🐞 **Detection Testing**: Validate rules against sample data before deployment
- 🔄 **Rule Conversion**: Translate detection logic between different platforms and languages
- 📚 **Knowledge Enhancement**: Learn best practices for detection engineering
- 🔍 **Threat Hunt Assistance**: Generate complex search queries to hunt for specific TTPs

## 🎬 See it in action <a name="demo"></a>

Here's a demo of DACAgent helping a security engineer create a detection rule for malicious PowerShell execution:

<p align="center">
<img src="./assets/detection-rule-demo.png" alt="DACAgent Detection Rule Demo">
</p>

## 🛠 Getting Started <a name="getting-started"></a>

> **Note:** The VSCode extension is currently in development and will be available soon.

1. **Install VS Code**: If you haven't already, [download it here](https://code.visualstudio.com/).
2. **Add DACAgent**:
   - Open VS Code
   - Click the puzzle piece icon on the left sidebar
   - Search for "DACAgent" (Coming Soon)
   - Click "Install"
3. **Start Building Detections**:
   - Open a new file
   - Describe the threat behavior you want to detect
   - Let DACAgent assist you in creating detection rules and queries!

## 💖 Why We Made This

As security practitioners, we've experienced the challenges of writing effective detection rules. Detection engineering requires deep knowledge of both security concepts and query languages. DACAgent bridges this gap, making detection development more accessible to security teams of all experience levels while boosting the productivity of seasoned detection engineers.

## 🤝 Join Our Community <a name="community"></a>

> **Note:** Our community platforms are currently in development and will be launched soon.

Whether you're developing your first Sigma rule or building complex detection logic, you'll soon be able to join our community! Connect with fellow detection engineers and security practitioners to share ideas and best practices.

## 🙏 Special Thanks

A big shoutout to the amazing projects and people that inspired DACAgent:

- **Sigma Project**: For standardizing detection rules
- **MITRE ATT&CK**: For providing a comprehensive framework of adversary tactics and techniques
- **Detection Engineering Community**: For continuous collaboration and knowledge sharing

## 🚀 Ready to Transform Your Detection Engineering?

DACAgent is coming soon! Stay tuned for the release of our VSCode extension.

Whether you're writing your first detection rule or managing an enterprise detection engineering program, DACAgent is your companion for building more effective security content. Can't wait to see what you detect! 🌟

---

<details>
<summary>🔧 For the tech-savvy: How to Contribute <a name="license"></a></summary>

If you're a developer and want to help make DACAgent even better, here's how:

1. Clone the repo: `git clone https://github.com/armadoinc/detection-as-code-agent.git`
2. Open in VS Code: `code dac-agent`
3. Navigate to extension folder: `cd extension`
4. Install dependencies: `npm run install:all`
5. Run with `F5`

Pro tips:

- Webview hot-reloads, but might need an occasional extension host reload
- Extension host changes need a full reload (Cmd/Ctrl + R)

Create a pull request with your improvements, and help us advance detection engineering for everyone!

</details>
