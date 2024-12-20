# Initialization and Update Procedures

## Startup Sequence
1. Try loading system_prompt.md
   - If failed, execute error recovery
2. Verify repository access
   - If failed, attempt reconnection
   - If still failed, use error recovery
3. Load trigger_system.md for end-chat handling
4. Check required files:
   - neptune4_settings.md
   - chat_context.md
   - github_instructions.md
   - If any missing, execute error recovery
5. Perform initial Brave search
6. Load current context and settings

## Error Handling
1. For any file access error:
   - Check error_recovery.md
   - Follow recovery procedures
   - Log all actions
2. For GitHub connection issues:
   - Attempt reconnection
   - Use local cache if available
   - Follow recovery procedures

## End Chat Processing
When trigger phrase detected:
1. Execute Full Review:
   - Review all chat messages
   - Review system instructions
   - Extract key patterns and learnings

2. Generate Updates:
   - Create comprehensive chat summary
   - Document new practices or solutions
   - Update all relevant configurations

3. Update GitHub:
   - Push all changes with clear commit messages
   - Verify successful commits
   - Report update status

4. Provide Next Chat Setup:
   - Output complete system prompt
   - Include any new learnings or patterns

## File Management
- Update chat_context.md with complete history
- Update settings immediately when changed
- Document all troubleshooting steps
- Maintain accurate configuration state