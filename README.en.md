# Electric Mobility UGC Workflow / 电摩真人 UGC 内容工作流

[简体中文](README.md) | **English**

Turn electric-mobility product references into realistic UGC stories, character assets, shot plans, video prompts and social copy.

[Download complete project ZIP](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools/raw/main/packages/skill-ecommerce-ugc-workflow.zip) · [All projects](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools)

## Features

- Reference-bound product appearance
- Two-part stories with explicit speakers
- TikTok / Instagram post copy

## What is included

| Part | Location |
| --- | --- |
| Skill instructions | [SKILL.md](skill/ecommerce-ugc-workflow/SKILL.md) |

This project is a Codex skill/workflow with its own instructions or scripts; it has no separate app server to launch.

## Download and extract

1. Open this repository, choose **Code → Download ZIP**, or use the complete-project download above.
2. Right-click the downloaded ZIP and choose **Extract All**. Open the extracted folder containing this README.
3. Keep the whole folder together. Start the program first using the next section, then install/use its skill.

## 1. Set up the program first

No app installation is required. Prepare Codex and the input listed below. If the skill includes Python scripts, install the stated script dependency before running them.

## 2. Install the Skill

1. At the extracted project's root, double-click `安装Skill.cmd` on Windows.
2. The installer copies `skill/ecommerce-ugc-workflow` to `%USERPROFILE%\.codex\skills\ecommerce-ugc-workflow`. Existing same-name skills are skipped; check the displayed result.
3. Reopen Codex and start a new chat. Use the exact skill name shown below.
4. If scripts cannot run under your organization policy, open install.ps1 for review or copy the skill directory manually to the same destination.

## 3. First task

| Prepare | Details |
| --- | --- |
| Input | Product images, verified specifications, audience, duration and story brief. |
| Output | Character prompts, timed shots, English generation prompts and a Chinese review version. |

```text
Use ecommerce-ugc-workflow to plan two 10-second family-gift scenes using my product reference. Start with a storyboard and use only verified specifications.
```


## Limits and troubleshooting

This is a Codex authoring workflow, not a standalone video generator. Rendering requires your own image/video tool.

| Problem | Next step |
| --- | --- |
| Skill not visible | Check the installer output and destination SKILL.md, reopen Codex and start a new chat. |
| Program fails to start | Open its directory in PowerShell and run the documented command so the error remains visible; check that program's README. |
| Browser panel missing | Select the exact folder containing manifest.json, check supported websites and refresh the website tab. |
| External service unavailable | Supply your own authorization/settings and verify access. Keep local output rather than claiming a sync/send succeeded. |

## Privacy and status

This is a source/skill distribution. No real accounts, OAuth tokens, customer/KOL lists, contracts, orders, mailbox exports or business media are included. You configure your own services. Documentation and package paths were checked; live orders, sends and publications were not executed as part of documentation validation.
