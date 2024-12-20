# GitHub Repository Management

## Repository Information
- Owner: Boundless-Code
- Repo: neptune4-orca-settings
- Branch: main

## Update Commands
Use push_files command structure:
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

## Update Requirements
1. After any setting changes: update neptune4_settings.md
2. After each chat session: update chat_context.md
3. After major changes: update all relevant files

## File Structure
/configuration/
  - templates.md
  - initialization.md
  - github_management.md
/
  - neptune4_settings.md
  - chat_context.md
  - system_prompt.md