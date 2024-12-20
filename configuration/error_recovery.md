# Error Recovery System

## File Access Errors

### 1. Primary File Missing (system_prompt.md)
If unable to access system_prompt.md:
1. Use embedded base template
2. Create new system_prompt.md
3. Initialize with base configuration
4. Log recovery action

### 2. Configuration Files Missing
If any configuration file unavailable:
1. Check templates.md for backup
2. If templates.md missing:
   ```markdown
   a. Create /configuration/ directory
   b. Restore templates.md from base template
   c. Rebuild missing files from templates
   ```
3. Log all recreated files

### 3. Settings Files Missing
If neptune4_settings.md missing:
1. Create new file from template
2. Initialize with safe defaults:
   ```markdown
   - Temperature: 200°C
   - Fan Speed: 100%
   - Flow Rate: 100%
   - Print Speed: 50mm/s
   ```
3. Flag for user verification

## Recovery Sequence

### 1. Assess Damage
- Check each required file
- List missing components
- Verify directory structure

### 2. Rebuild Core
1. system_prompt.md
2. templates.md
3. initialization.md
4. github_management.md

### 3. Restore Data
1. neptune4_settings.md
2. chat_context.md
3. configuration files

### 4. Verify Recovery
- Check file contents
- Verify file permissions
- Test file access
- Confirm GitHub connectivity

## Error Prevention
1. Always verify file access before updates
2. Create backups before major changes
3. Use atomic updates where possible
4. Maintain checksums of critical files

## Recovery Logging
- Log all recovery actions
- Document missing files
- Record restoration steps
- Note any data loss

## User Communication
If recovery needed:
1. Explain situation clearly
2. List recovered files
3. Highlight any lost data
4. Request verification of settings

## Base Templates
Emergency recovery templates stored here as last resort:

### Minimal system_prompt.md
```markdown
# Emergency Recovery Prompt
[Basic system instructions for recovery]
```

### Minimal templates.md
```markdown
# Emergency Templates
[Basic file templates for recovery]
```