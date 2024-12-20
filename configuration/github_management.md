# GitHub Repository Management

## Required End-of-Chat Updates

### 1. Update Chat Context
At the end of EVERY chat:
```json
{
  "command": "push_files",
  "repo": "neptune4-orca-settings",
  "files": [{
    "path": "chat_context.md",
    "content": "[Updated chat history and progress]"
  }],
  "message": "Update chat context with latest session"
}
```

### 2. Update Settings
When ANY settings change:
```json
{
  "command": "push_files",
  "repo": "neptune4-orca-settings",
  "files": [{
    "path": "neptune4_settings.md",
    "content": "[Current settings and status]"
  }],
  "message": "Update printer settings"
}
```

### 3. End of Chat Summary
Before ending EVERY chat:
1. Create summary using FORMAT FOR SUMMARIES from system_prompt.md
2. Update both chat_context.md and neptune4_settings.md
3. Verify all changes were saved

## Repository Structure
/configuration/
  - templates.md - File templates
  - initialization.md - Startup procedures
  - github_management.md - This file

/
  - neptune4_settings.md - Current printer state
  - chat_context.md - Ongoing chat history
  - system_prompt.md - Core assistant instructions

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

## Pre-End Chat Checklist
1. Verify settings are current
2. Update chat context
3. Create summary
4. Push all changes
5. Verify successful commits