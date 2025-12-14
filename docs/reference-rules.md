# Summary Reference Rules

## Core Principle

**All website development, content creation, and project documentation must reference and align with the findings and recommendations in [docs/summary.md](./summary.md)**

## Mandatory Reference Points

### 1. **Before Starting Any New Work**

- [ ] Review relevant sections of `docs/summary.md`
- [ ] Identify which phase and recommendations apply
- [ ] Align new work with the transformation plan
- [ ] Reference specific action items from the summary

### 2. **Page/Project Creation Requirements**

Every new page or project must include:

- [ ] Reference to the summary's technical skills showcase
- [ ] Alignment with the professional branding guidelines
- [ ] Implementation of navigation improvements
- [ ] Adherence to design and UX recommendations

### 3. **Content Standards**

All content must:

- [ ] Address issues identified in the summary
- [ ] Follow the professional presentation guidelines
- [ ] Include proper context and explanations as recommended
- [ ] Maintain consistency with the established transformation phases

## Specific Implementation Rules

### HTML Pages

```html
<!-- Required meta reference in every HTML file -->
<meta
  name="development-guide"
  content="Based on docs/summary.md recommendations"
/>

<!-- Required comment at top of every HTML file -->
<!--
Development aligned with docs/summary.md
Phase: [1-4] | Focus: [Branding/Content/Technical/Advanced]
Addresses: [Specific issues from summary]
-->
```

### Documentation Files

All `.md` files must include:

```markdown
---
**Development Reference**: This work aligns with [docs/summary.md](./summary.md) recommendations
**Phase**: [1-4] | **Focus Area**: [Specific area from summary]
---
```

### Project Structure

```
/docs/
  ├── summary.md (Master reference)
  ├── reference-rules.md (This file)
  ├── phase-1-checklist.md (Foundation & Branding)
  ├── phase-2-checklist.md (Content & Context)
  ├── phase-3-checklist.md (Technical Improvements)
  └── phase-4-checklist.md (Advanced Features)
```

## Reference Categories

### 1. **Technical Implementation**

When implementing code changes, reference:

- Summary sections: "Technical Skills Showcase Opportunities"
- Summary sections: "Performance & Technical Issues"
- Summary sections: "Accessibility & Standards"

### 2. **Content Creation**

When creating content, reference:

- Summary sections: "Content & Context"
- Summary sections: "Branding & Professional Identity"
- Summary sections: "Immediate Action Items"

### 3. **Design Changes**

When making design updates, reference:

- Summary sections: "Design & Visual Appeal"
- Summary sections: "Navigation & User Experience"
- Summary sections: "SEO & Discoverability"

## Enforcement Checklist

### Before Committing Code

- [ ] Verified alignment with summary recommendations
- [ ] Added appropriate summary references
- [ ] Checked against immediate action items
- [ ] Ensured phase-appropriate implementation

### Before Publishing Content

- [ ] Confirmed professional presentation standards
- [ ] Validated technical accuracy claims
- [ ] Ensured proper context and explanations
- [ ] Checked navigation and user experience

### During Reviews

- [ ] Summary alignment verified
- [ ] Phase progression maintained
- [ ] Action items addressed
- [ ] Long-term goals supported

## Status Tracking

### Current Website Status

Reference the summary's current state analysis:

- Main Landing Page: ⚠️ Needs improvement
- WebGL Experiments: ⚠️ Need context
- Audio Review Tool: ⚠️ Need integration
- Documentation: ⚠️ Needs expansion

### Progress Tracking

Track improvements against summary recommendations:

- [ ] Phase 1: Foundation & Branding
- [ ] Phase 2: Content & Context
- [ ] Phase 3: Technical Improvements
- [ ] Phase 4: Advanced Features

## Quick Reference Links

### Summary Sections

- [Current State Analysis](./summary.md#current-state-analysis)
- [Major Issues](./summary.md#major-issues-for-public-facing-website)
- [Recommendations](./summary.md#recommendations-for-public-facing-transformation)
- [Technical Skills](./summary.md#technical-skills-showcase-opportunities)
- [Immediate Actions](./summary.md#immediate-action-items)
- [Long-term Goals](./summary.md#long-term-goals)

### Common Reference Patterns

```markdown
<!-- In project documentation -->

This addresses [Summary Issue #X] by implementing [Specific Recommendation]

<!-- In code comments -->

// Implements summary.md recommendation: [Specific improvement]

<!-- In commit messages -->

feat: Add navigation improvements (refs: docs/summary.md Phase 1.3)
```

## Violation Consequences

### Minor Violations

- Missing summary reference in documentation
- Incomplete alignment with recommendations
- **Action**: Add proper references and align with summary

### Major Violations

- Work that contradicts summary recommendations
- Ignoring established transformation phases
- **Action**: Rework to align with summary guidelines

## Update Protocol

### When Summary Changes

1. Update all references to point to new summary sections
2. Revise implementation to match updated recommendations
3. Notify all stakeholders of changes
4. Update progress tracking

### Regular Reviews

- **Weekly**: Check alignment with immediate action items
- **Monthly**: Review phase progression
- **Quarterly**: Validate long-term goal progress

## Templates

### New Project Template

```markdown
# [Project Name]

**Summary Reference**: Addresses [docs/summary.md](./summary.md) [Specific Section]
**Phase**: [1-4] | **Priority**: [High/Medium/Low]

## Alignment with Summary

- **Issue Addressed**: [Specific issue from summary]
- **Recommendation Implemented**: [Specific recommendation]
- **Skills Showcased**: [From technical skills section]

## Implementation

[Project details here]

## Summary Compliance Checklist

- [ ] Addresses identified issues
- [ ] Follows phase guidelines
- [ ] Implements recommendations
- [ ] Maintains professional standards
```

---

**This rule document must be referenced and followed for all website development activities. It ensures consistent alignment with the comprehensive analysis and recommendations provided in docs/summary.md**
