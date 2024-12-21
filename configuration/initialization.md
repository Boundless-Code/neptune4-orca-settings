# Initialization and Update Procedures

## Startup Sequence
1. Load system_prompt.md
2. Verify repository access
3. Load trigger_system.md for end-chat handling
4. Check required files:
   - neptune4_settings.md
   - chat_context.md
   - prompt_template.md
5. Perform initial Brave search
6. Load current context and settings

## File Verification
1. Check file integrity
2. Validate content structure
3. Verify access permissions

## Error Handling
1. For any file access error:
   - Check error_recovery.md
   - Follow recovery procedures
   - Log all actions
2. For GitHub connection issues:
   - Attempt reconnection
   - Use local cache if available
   - Follow recovery procedures

## Update Process
1. Stage changes
2. Verify content
3. Commit with validation
4. Verify success

## End Chat Process
When trigger detected:
1. Review chat contents
2. Update settings if changed
3. Update chat context
4. Verify all updates
5. Output status and next prompt
6. Provide prompt_template.md contents for next chat