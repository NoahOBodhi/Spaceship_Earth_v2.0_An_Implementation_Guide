# Contributing to Spaceship Earth v2.0

Thank you for your interest in contributing to this project! This guide explains how to engage with the original content and create your own implementations.

## 🎯 Two Ways to Contribute

### 1. Improve the Original Content

The `/original/` directory contains the canonical ebook. Changes to this content are carefully curated.

**Process:**
1. **Open an issue** describing your proposed change
   - What needs improvement?
   - Why is this change valuable?
   - What specific content would you modify?

2. **Wait for discussion** - The maintainer (@NoahOBodhi) will review and discuss

3. **Submit a PR** only if approved
   - PRs to `/original/*` without prior approval will be closed
   - All changes require maintainer approval

**Note:** This is intentionally restrictive to maintain the integrity of the source material.

### 2. Create Your Own Implementation (Recommended)

This is the primary way to contribute - adapt the material for your specific context!

## 🍴 How to Fork & Implement

### Step 1: Fork to a Separate Repository

**Do NOT create a branch** - instead, fork the entire repository:

1. Click the "Fork" button on GitHub
2. Create the fork under your account (not as a branch of this repo)
3. Clone your fork locally

### Step 2: Adapt the Content

In your forked repository:

1. **Modify freely** - Change structure, content, examples
2. **Add your context** - Make it relevant to your community/organization
3. **Maintain attribution** - Keep references to the original
4. **Keep the license** - CC BY-SA 4.0 applies to derivatives

### Step 3: Link Back to the Original

**Required:** Your fork must maintain visible attribution:

**Add to your README:**
```markdown
## Attribution

This work is adapted from [Spaceship Earth v2.0: An Implementation Guide](https://github.com/NoahOBodhi/Spaceship_Earth_v2.0_An_Implementation_Guide) by Noah O. Bodhi, licensed under CC BY-SA 4.0.

**Original repository:** https://github.com/NoahOBodhi/Spaceship_Earth_v2.0_An_Implementation_Guide
**Forked from version:** v2.0-original (specify the tag/version)
```

### Step 4: Register Your Implementation

Help build the network of implementations:

1. In **your fork**, create a file: `IMPLEMENTATION.json`

```json
{
  "name": "Your Implementation Name",
  "description": "Brief description of your adaptation",
  "context": "Community/organization/region this serves",
  "repository": "https://github.com/your-username/your-fork",
  "forked_from": "v2.0-original",
  "date_created": "2025-10-17",
  "maintainer": "Your Name or Organization",
  "contact": "email or website"
}
```

2. Submit a PR to **this repository** adding your entry to `/implementations/registry.json`

3. This PR only adds to the registry - no other changes needed

## 📋 Implementation Best Practices

### Attribution Guidelines

**Always include:**
- Link to original repository
- Original author credit (Noah O. Bodhi)
- License notice (CC BY-SA 4.0)
- Version forked from

**In your content:**
- Add attribution footer/header to modified pages
- Example: `Adapted from Spaceship Earth v2.0 by Noah O. Bodhi`

### Naming Your Fork

Suggested patterns:
- `Spaceship_Earth_v2_[Your_Context]` - e.g., "Spaceship_Earth_v2_Urban_Gardens"
- `[Your_Project]_Implementation_Guide` - e.g., "Sustainable_Seattle_Implementation_Guide"
- Include "Implementation" to differentiate from original

### Sharing Your Work

Once your implementation is stable:
- Register it in the implementations registry
- Share with your community
- Consider presenting at conferences
- Write about your experience

## 📖 Implementation Registry

Registered implementations are listed at: `/implementations/registry.json`

This creates a network effect where:
- Communities learn from each other
- Best practices emerge
- The original improves based on real-world feedback
- Collaboration opportunities arise

## 🤖 AI Collaboration

This project welcomes AI-assisted contributions. See [CLAUDE.md](CLAUDE.md) for:
- How to work with Claude
- AI collaboration standards
- Prompt patterns for this project

## ❓ Questions?

- **About forking:** Open an issue
- **Technical problems:** Open an issue
- **General questions:** Open a discussion

## 📜 Code of Conduct

**Be respectful.** This project exists to serve planetary wellbeing. Contributions should:
- Maintain the spirit of collaboration
- Respect diverse perspectives
- Focus on practical, implementable guidance
- Avoid political or ideological extremism

## 🙏 Thank You

Every fork, every adaptation, every implementation helps build a network of sustainable practice. Your contribution matters.

---

**Remember:** Fork to implement, PR to register. Keep the original protected, let implementations flourish.