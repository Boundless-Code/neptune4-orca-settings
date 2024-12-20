# Initialization and Update Procedures

## Startup Sequence
1. Load system_prompt.md
2. Verify repository access
3. Check required files:
   - neptune4_settings.md
   - chat_context.md
   - github_instructions.md
4. Perform initial Brave search
5. Load current context and settings

## Automatic Updates
- EVERY response must check if settings changed
- If settings changed, update neptune4_settings.md
- At chat end, MUST update chat_context.md
- Before chat end, MUST run end-of-chat checklist

## End of Chat Detection
Watch for these signals:
1. User indicates end of session
2. User starts new topic
3. Long period of inactivity
4. "Summarize this chat" request

When detected:
1. Run Pre-End Chat Checklist from github_management.md
2. Create summary using standard format
3. Push all updates
4. Verify successful commits

## File Creation Rules
If any required file is missing:
1. Use template from templates.md
2. Initialize with base configuration
3. Document creation in commit message

## Context Management
- Update chat_context.md at end of each session
- Maintain continuous history
- Track all setting changes
- Document all troubleshooting steps