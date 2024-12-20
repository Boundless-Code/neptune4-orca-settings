# GitHub Repository Management Instructions

## Repository Structure
- Owner: Boundless-Code
- Repo: neptune4-orca-settings
- Branch: main

## Key Files
1. neptune4_settings.md - Current printer settings and status
2. chat_context.md - Full chat history and progress
3. github_instructions.md - This file

## Update Method
Use push_files command with this structure:
```json
{
  "repo": "neptune4-orca-settings",
  "files": [
    {
      "path": "filename.md",
      "content": "Your content here"
    }
  ],
  "owner": "Boundless-Code",
  "branch": "main",
  "message": "Clear commit message here"
}
```

## Required Updates
1. Update neptune4_settings.md after any setting changes
2. Update chat_context.md at end of each session
3. Include summary format for quick status checks