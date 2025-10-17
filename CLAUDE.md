# CLAUDE.md: AI Collaboration Standards

## Project Context

**Spaceship Earth v2.0: An Implementation Guide** - A living ebook designed for collaborative adaptation while protecting the canonical original.

---

## Available Resources

- 20-chapter original ebook in `/original/`
- Technical guide for GitHub integration
- Implementation registry tracking forks
- Contributing guidelines and license

---

## Core Principles

### 1. Protect the Original
- `/original/*` content requires maintainer approval
- Never modify original content without explicit permission
- Suggest improvements via issues first

### 2. Enable Implementations
- Assist users in forking and adapting content
- Generate implementation-specific templates
- Help maintain attribution and licensing

### 3. Build the Network
- Support registry updates for new implementations
- Generate comparative analyses across forks
- Foster cross-implementation learning

---

## Execution Protocol

### When Given a Task:

**STEP 1: UNDERSTAND**
- Read the instruction clearly
- Determine if it involves `/original/` (protected) or implementations
- If unclear → ASK (max 2 questions)

**STEP 2: CHECK SCOPE**
- Original content modification? → Confirm permission first
- New implementation? → Use fork workflow
- Registry update? → Validate format

**STEP 3: EXECUTE**
- Use appropriate GitHub tools
- Follow documented patterns
- Single-pass execution preferred

**STEP 4: REPORT**
- Confirm completion with link
- Keep responses concise
- No unnecessary explanations

---

## Repository-Specific Rules

### Protected Content
**I NEVER modify `/original/*` without:**
1. Explicit user confirmation
2. Clear rationale provided
3. Understanding this is exceptional

### Fork Support
**I ALWAYS help users:**
- Understand fork vs. branch distinction
- Generate proper attribution
- Create IMPLEMENTATION.json files
- Register in the implementations registry

### File Operations
**I prioritize:**
- Correct directory placement
- Proper naming conventions
- Clean commit messages
- Efficient tool usage

---

## Common Tasks

### Create New Implementation Template
```
1. Identify user's context
2. Generate IMPLEMENTATION.json
3. Create attribution README section
4. Provide fork setup instructions
```

### Register Implementation
```
1. Validate IMPLEMENTATION.json format
2. Add entry to /implementations/registry.json
3. Create PR if requested
```

### Modify Original (RARE)
```
1. Confirm this is intentional
2. Verify user is maintainer
3. Proceed only with explicit approval
```

### Generate Comparative Analysis
```
1. Read multiple implementations from registry
2. Identify patterns and innovations
3. Synthesize learnings
4. Suggest back-ports to original if valuable
```

---

## Prohibited Actions

**I NEVER:**
- Modify `/original/*` without explicit permission
- Create branches when forks are needed
- Skip attribution requirements
- Ignore license terms
- Make assumptions about user intent with protected content

---

## Communication Style

**For Simple Tasks:**
- Minimal explanation
- Direct execution
- Link to result

**For Complex Tasks:**
- Brief plan statement
- Execute systematically
- Concise summary

**For Protected Content:**
- Extra caution
- Explicit confirmation
- Clear documentation

---

## License Compliance

**I ensure all generated content:**
- Includes CC BY-SA 4.0 notice
- Maintains attribution chain
- Links back to original
- Follows ShareAlike requirements

---

## Success Metrics

- Original content remains pristine
- Implementations properly attributed
- Registry accurately maintained
- Users understand fork workflow
- Collaboration scales efficiently

---

## Project-Specific Workflows

### RPIC Pattern for Content Development
- **Research:** Understand original structure
- **Plan:** Design adaptation approach
- **Implement:** Create modified content
- **Commit:** Document changes and rationale

### Implementation Registration Workflow
1. User creates fork
2. User adapts content
3. User creates IMPLEMENTATION.json
4. I help format registry entry
5. User submits registry PR

---

**These standards ensure the project maintains integrity while maximizing collaborative potential.**

**Ready to assist with repository operations.**