<a name="start-building"></a>
<br>
<p align="center">
<img src="img/banner-build-26.png" alt="Microsoft Build 2026" width="1200"/>
</p>

# [Microsoft Build 2026](https://build.microsoft.com)

## 🔥 DEM334: Build agents where work happens: chats, channels, and meetings in Microsoft Teams

### Session Description

Agents are moving beyond simple chat experiences. With the Microsoft Teams SDK, developers can build agents that participate directly in the flow of work across chats, channels, and meetings. In this demo, we showed how to leverage Teams capabilities to create agents that automate tasks, surface insights, and take action in context without pulling users out of Teams.

### 👀 What you saw in this demo

This demo walked through building collaborative agents in Microsoft Teams — agents that participate in chats, channels, and meetings, not just 1:1. We framed successful collaborative agents around three pillars:

- **Manners** — for crowded rooms: quoted replies, threaded replies
- **Privacy** — for trusted moments
- **Polish** — for clean, scannable interactions: Adaptive Cards

The demo scenario was **EngSys**, an internal engineering-health agent that monitors GitHub, pipelines, and on-call signals — first in a 1:1 chat, then in a group incident-response channel.

#### Features highlighted

| Feature | Status |
|---|---|
| Quoted replies, threaded replies, source citations, AI labels, response streaming, feedback buttons, sensitivity labels, slash commands | Generally available |

### 🚀 Getting started

This demo is a walkthrough of what's new in the Microsoft Teams SDK and how to build agents in collaborative spaces (chats, channels, meetings). There's no sample code in this repo — to start building your own agent, use the Teams Developer CLI:

- Install and scaffold a new agent with the [Teams Developer CLI](https://aka.ms/teamscli)
- Read the [Microsoft Teams SDK docs](https://aka.ms/teams-sdk) for concepts and reference
- Explore additional links in the [📚 Resources and Next Steps](#-resources-and-next-steps) table below

### 🧠 Learning Outcomes

In this demo, you saw how to:

- Build agents for Microsoft Teams collaborative surfaces — 1:1 chats, group chats, channels, and meetings — using the unified Microsoft Teams SDK
- Apply the three pillars of collaborative agents — **Manners** (quoted and threaded replies), **Privacy** (for trusted moments), and **Polish** (Adaptive Cards) — so agents fit into group conversations instead of cluttering them
- Use Teams-native agent UX — streaming, AI labels, citations, feedback, and starter prompts — to make agent responses feel trustworthy and in-context

### 💻 Technologies Used

1. [Microsoft Teams SDK](https://aka.ms/teams-sdk) — the primary SDK for building agents that run natively in Microsoft Teams chats, channels, and meetings.

### 📚 Resources and Next Steps

| Resource | Description |
|:---------|:------------|
| [Microsoft Teams SDK](https://aka.ms/teams-sdk) | Official docs for the Microsoft Teams SDK — concepts, guides, and reference for building agents in Teams. |
| [Teams Developer CLI](https://aka.ms/teamscli) | Command-line tool to scaffold, run, and manage Teams SDK agent projects. |
| [Adaptive Cards Hub](https://aka.ms/adaptivecardshub) | Design and build the rich, interactive cards used in the demo for approvals and other in-context actions. |
| [https://aka.ms/build26-next-steps](https://aka.ms/build26-next-steps) | Explore lab and session repos to further your learning from Microsoft Build |


### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the products and services covered in this demo.

**Visual Studio Code** — One click installation: 

[![Install in Visual Studio Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)


**GitHub Copilot CLI** — Run this to install the Learn MCP Server as a plugin:
```
/plugin install microsoftdocs/mcp
```

For more info, other clients, and to post questions, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

## Content Owners

<table>
<tr>
    <td align="center"><a href="https://github.com/lilyydu">
        <img src="https://github.com/lilyydu.png" width="100px;" alt="Lily Du"/><br />
        <sub><b>Lily Du</b></sub></a><br />
            <a href="https://github.com/lilyydu" title="talk">📢</a>
    </td>
    <td align="center"><a href="https://github.com/umangsehgal">
        <img src="https://github.com/umangsehgal.png" width="100px;" alt="Umang Sehgal"/><br />
        <sub><b>Umang Sehgal</b></sub></a><br />
            <a href="https://github.com/umangsehgal" title="talk">📢</a>
    </td>
</tr></table>

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
