# 🎩✨🦄 UserAgentWonderland 🦄✨🎩

## Overview
Welcome to the **UserAgentWonderland Repository**! This repository contains extensive lists of user-agents categorized by device type, making it easier for developers and researchers to identify and utilize user-agent strings from a variety of platforms.

## Description
In the digital landscape, User-agent strings are essential for identifying the client software making a request to a server. They provide critical information about the browser, operating system, device type, and more. Understanding the structure of user-agent strings can aid in various applications, such as analytics, debugging, or serving customized content. 

### Anatomy of a User-Agent String 
A typical user-agent string consists of multiple components, each containing specific information, often formatted in the following structure:

`Mozilla/5.0 (Platform; Encryption; OS; Browser; Version)`

### Breakdown of User-Agent Components

| **Parameter**     | **Description**                                 | **Example**                         |
|-------------------|-------------------------------------------------|-------------------------------------|
| **Browser Engine**| Indicates the engine used to render the web content. Most strings start with `Mozilla/5.0`. | `Mozilla/5.0`                        |
| **Platform**      | Specifies the operating system and CPU architecture. This includes details about the device type. | `(Windows NT 10.0; Win64; x64)`   |
| **Encryption**    | Indicates if the client supports secure connections (like TLS). This is sometimes included in the final string. | `(KHTML, like Gecko)`              |
| **OS**            | Further details about the operating system. This may include the version number and additional OS-specific details. | `(Ubuntu; Linux 20.04)`            |
| **Browser**       | Names the web browser being used, which may include information about its version as well. | `Chrome/94.0.4606.61`              |
| **Version**       | The specific version number of the browser, allowing for detailed analytics. | `Version/14.0`                     |

### Visual Representation

Below is a visual example of how the components fit together in a typical user-agent string:

```
User-Agent:
  ├── Browser Engine: Mozilla/5.0
  ├── Platform: Windows NT 10.0
  ├── Encryption: KHTML
  ├── OS: Ubuntu 20.04
  ├── Browser: Chrome
  └── Version: 94.0.4606.61
```

### Common Components in User-Agent Strings

- **Mobile Devices**:
  - Often include indicators like `Mobile` or `Tablet`.
- **Search Robots**:
  - Bots like Googlebot or Bingbot typically have unique identifiers.
- **Custom Headers**:
  - Some applications or devices might pass custom user-agent strings for identification.

## Example User-Agent Strings
This repository aims to provide a comprehensive collection of user-agents sorted into several categories including:

### Mobile Devices 📱

`Mozilla/5.0 (iPhone; CPU iPhone OS 14_0 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0 Mobile/15E148 Safari/604.1`
  
### Terminals 🖥️

`Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:91.0) Gecko/20100101 Firefox/91.0`

### Servers ⏳

`Mozilla/5.0 (compatible; Ubuntu; Linux; x86_64; rv:20.04) Gecko/20100101 Ubuntu/20.04`
  
### Personal Computers a.k.a. PCs 🖥️💻

`Mozilla/5.0 (Windows NT 10.0; Win64; x64; Trident/7.0; AS; rv:11.0) like Gecko`
  
### Tablets 📊

`Mozilla/5.0 (Linux; Android 10; SM-T870) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.4606.61 Safari/537.36`
  
### IoT Devices 🌐

`Mozilla/5.0 (Linux; U; Android 9; SmartTV) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/77.0.3865.92 Safari/537.36`
  
_And much more! 🎉_

## Features 🌟
- User-agent lists by category
- Easy access and integration for developers
- In two common file formats: .txt and .json
- Clear formatting for quick scanning

_Note: The lists do not contain unique user agents and also have some few duplicates. In addition, the different file formats do not contain the same user agents._

## Getting Started 🏁
To get started with the UserAgent Repository, you can clone this repository to your local machine:

```bash
git clone https://github.com/D4T4HUN73R/UserAgentWonderland.git
```

Once cloned, you can browse through the directories corresponding to different device types and view the user agents in plain text format.

## Use Case Examples
- **For TheNumberOneThing:** Just enjoy it!
- **Testing:** Test how your web applications behave with different devices by simulating user-agent strings.
- **Analytics:** Analyze traffic based on user-agents to understand your audience better.

## Future Feature List 🚧
- Integration of user-agent parsing libraries
- Automated updates for the user-agent lists
- User-contributed lists and submissions
- Enhanced categorization based on additional metrics (OS version, browser versions, etc.)

## Acknowledgments 🤝
- A big thank you to all contributors who help in keeping the lists updated!
- Special thanks to the open-source community for providing valuable resources to compile these user-agents.

⚠️ DISCLAIMER ⚠️

The published scripts, software, and associated URLs or links are intended for educational purposes only. We disclaim any responsibility for the content displayed on external platforms or websites mentioned. Users are prohibited from engaging in any criminal, malicious activities or actions that may cause harm to others or engage in activities with wrongful intent using the provided materials. By accessing and utilizing these materials, you agree to abide by this disclaimer and use the content solely for educational purposes.
