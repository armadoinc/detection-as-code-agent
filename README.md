<h1 align="center">
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

<p>This project is in development. Download links will be available upon release.</p>

# **Detection-as-Code Agent**
  <a href="#purpose">Purpose</a> •
  <a href="#capabilities">Capabilities</a> •
  <a href="#usage">Usage</a> •
  <a href="#implementation">Implementation</a> •
  <a href="#contribution">Contribution</a>
</div>

<br>

# DACAgent <a name="purpose"></a>

DACAgent is a detection-as-code agent for VSCode. It helps security engineers and analysts build detection rules and search queries across security platforms.

## Purpose

DACAgent addresses the fundamental problem of detection engineering: creating consistent, effective detection logic across multiple security platforms, query languages, and data formats.

## Capabilities <a name="capabilities"></a>

- **Detection Development**: Creates detection rules for multiple platforms (Sigma, KQL, SPL, EQL)
- **Platform Consistency**: Translates detection logic between query languages
- **Validation**: Tests rules against sample data
- **Conversion**: Transforms rules between formats
- **Search Assistance**: Generates hunting queries for specific techniques

## Implementation Example <a name="usage"></a>

<p align="center">
<img src="./assets/detection-rule-demo.png" alt="DACAgent Detection Rule Demo">
</p>

## Usage <a name="implementation"></a>

> The extension is in development.

1. **Install VS Code**
2. **Add DACAgent Extension**:
   - VSCode Extension Marketplace
   - Search for "DACAgent"
   - Install
3. **Usage**:
   - New file
   - Define threat behavior
   - Generate detection logic

## Technical Rationale

Detection engineering requires translating threat hypotheses into platform-specific query logic. This process demands:

1. Understanding of attacker TTPs
2. Knowledge of data structure and sources
3. Proficiency in query languages
4. Platform-specific optimization

DACAgent automates these processes based on detection engineering first principles.

## Development <a name="contribution"></a>

If you want to contribute:

1. Clone: `git clone https://github.com/armadoinc/detection-as-code-agent.git`
2. Open in VS Code: `code dac-agent`
3. Navigate: `cd extension`
4. Install: `npm run install:all`
5. Run: `F5`

Development notes:
- Webview supports hot-reload
- Extension host requires full reload (Cmd/Ctrl + R)

Create pull requests to improve detection engineering capabilities.
