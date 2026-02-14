# Recommended Labels

Language: **English** | [中文](labels.zh-CN.md) | [Français](labels.fr.md) | [Deutsch](labels.de.md)

Use the following labels to keep triage lightweight and searchable.

| Name | Color | Purpose |
| --- | --- | --- |
| `idea` | `#0E8A16` | New idea, pain point, or unmet need |
| `looking-for-solution` | `#1D76DB` | Looking for existing tools |
| `team-wanted` | `#5319E7` | Recruiting collaborators |
| `building` | `#FBCA04` | Project is actively being built |
| `solved` | `#0052CC` | Solved by existing tool or implemented |
| `duplicate` | `#CFD3D7` | Duplicate of another issue |
| `needs-info` | `#D876E3` | Missing required context |
| `stale` | `#E4E669` | Inactive for a long time |

## Optional Extra Labels

| Name | Color | Purpose |
| --- | --- | --- |
| `good-first-join` | `#7057FF` | Easy entry for new collaborators |
| `high-potential` | `#B60205` | High-value or high-demand idea |
| `research-needed` | `#C2E0C6` | Needs market/technical research |

## GitHub CLI Example

If you use GitHub CLI, you can create labels quickly:

```bash
gh label create idea --color 0E8A16 --description "New idea, pain point, or unmet need"
gh label create looking-for-solution --color 1D76DB --description "Looking for existing tools"
gh label create team-wanted --color 5319E7 --description "Recruiting collaborators"
gh label create building --color FBCA04 --description "Project is actively being built"
gh label create solved --color 0052CC --description "Solved by existing tool or implemented"
gh label create duplicate --color CFD3D7 --description "Duplicate of another issue"
gh label create needs-info --color D876E3 --description "Missing required context"
gh label create stale --color E4E669 --description "Inactive for a long time"
```
