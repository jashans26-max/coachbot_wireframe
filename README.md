# CoachBot Wireframe

A test plugin for Claude Code that validates plugin loading mechanisms for agents, skills, and hooks.

## Installation

In Claude Code, go to Plugins → Add Marketplace or Add Plugin and paste:
```
https://github.com/jashans26-max/coachbot_wireframe
```

## What's Included

- **Agent**: Test agent that confirms agent loading works
- **Skill**: Test skill with `/test-skill` command for validating skill loading
- **Hooks**: Hook configuration to verify hooks load correctly

## Testing

After installation, verify:
1. Plugin appears in the plugins list
2. `/test-skill` command is available and fires
3. Test agent loads without errors
4. Hooks are registered correctly
