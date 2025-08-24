# Claude Project Context - Content Repository

## Project Overview

This is NovoAcuity's marketing content repository, containing AI vendor assessments, brand guidelines, and other marketing materials. Unlike typical development projects, this is a content-focused repository where the documentation IS the product.

## Repository Purpose

- **Primary Goal**: Maintain and organize marketing content for NovoAcuity
- **Content Types**: AI vendor assessments, brand voice guides, business context documentation
- **Target Audience**: Professional knowledge workers, business decision-makers, marketing teams

## Directory Structure

```
Content/
├── AI Vendor Assessments/      # Comprehensive AI vendor guides and assessments
│   ├── Individual assessments (Anthropic, OpenAI, Google, etc.)
│   ├── Consolidated guides (Executive Summary, Complete Guide)
│   └── zzArchive/             # Obsolete templates and initial prompts
├── Brand Central/              # Brand voice and business context
│   ├── Brand Voice Guide
│   ├── Business Context Synthesis
│   └── AI Usage Guidelines
└── [Future content areas]      # Additional marketing content as needed
```

## Content Management Rules

### Version Control
- Git handles ALL versioning - maintain only ONE active version of each file
- NO versioned filenames (e.g., file_v1.md, file_v2.md)
- NO timestamped filenames for production content
- Overwrite files and rely on git history for versions

### Archive Usage
- `zzArchive/` folders are for obsolete materials (old prompts, deprecated templates)
- NOT for version control - that's what git is for
- Temporary retention for lineage/context only

### File Naming
- Use canonical, descriptive names for all production content
- Keep names consistent and professional
- No timestamps in production filenames

## Content Style Guidelines

### Brand Voice (per Brand Central guidelines)
- Professional yet approachable
- Warm and conversational (knowledgeable colleague over coffee)
- Clear and accessible (complex topics made digestible)
- Light humor and cultural references where appropriate
- Globally minded perspective

### Writing Standards
- Focus on helping professional knowledge workers
- Avoid excessive jargon
- Include practical, actionable insights
- Maintain NovoAcuity's mission: reducing stress in decision-making

## Working with This Repository

### When Adding Content
1. Determine appropriate folder (or create new category if needed)
2. Use descriptive, canonical filename
3. Follow brand voice guidelines
4. Create/update README.md for new folders
5. Commit with clear, descriptive message

### When Updating Content
1. Overwrite the existing file (don't create versions)
2. Use meaningful commit messages describing the changes
3. Move truly obsolete materials to zzArchive if needed for context

### Session Management
- Content work is organized in writing/editing sprints
- Use SESSION_CONTEXT.md for complex multi-file updates
- Commit at natural breakpoints (completed sections, assessments)

## Key Business Context

### NovoAcuity Mission
"We improve the quality of lives by helping people use data and technology to make better, trustworthy decisions at scale."

### Core Frameworks
- **DI-to-PI (DI2PI)**: Decision Intelligence-to-Presentation Intelligence framework
- **Gold Medal Decision-making (GMD)**: Certification standard for critical information

### Target Market
- Senior corporate executives (CEOs, CIOs, CDOs)
- Decision support teams
- Professional knowledge workers adopting AI

## Maintenance Notes

### Regular Reviews
- AI vendor assessments: Update as landscape changes
- Brand voice guide: Quarterly review
- Business context: Annual review

### Quality Checks
- Ensure all content aligns with brand voice
- Verify technical accuracy of AI vendor information
- Maintain consistency across all documents

## Platform Modules Required

For work in this repository, load:
- ✅ Git workflow guide - `~/.config/claude-instructions/operations/git-workflow.md`
- ✅ Project management guide - `~/.config/claude-instructions/operations/project-management.md`
- ✅ Content project considerations (integrated in above guides)

## Special Instructions

### DO
- Maintain professional tone consistent with brand guidelines
- Keep content accessible to non-technical audiences
- Update assessments as AI landscape evolves
- Use git for all version control

### DON'T
- Create multiple versions of files
- Use timestamps in filenames
- Add technical jargon without explanation
- Create documentation unless specifically requested

## Last Updated

August 24, 2025 - Initial project setup and migration from previous structure

---

*This CLAUDE.md provides AI assistants with the specific context needed to work effectively with NovoAcuity's content repository.*