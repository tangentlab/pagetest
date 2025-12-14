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

**Current Site Structure:**

```
/pagetest/
├── index.html (Main landing page)
├── exp1_cube.html (WebGL Cube Demo)
├── exp2.html (3D Text Demo)
├── exp3.html (Swarming Particles Demo)
├── aframe/
│   └── index.html (A-Frame VR Demo - Interactive 3D objects)
├── audio_review/
│   └── index.html (Audio Review Tool)
├── exp1/ (Contains index.html - WebGL Cube)
├── exp2/ (Contains index.html - 3D Text)
├── exp3/ (Contains index.html - Swarming Particles)
├── exp4/ (Contains index.html - React Three Fiber Hotspots)
├── exp5/ (Contains index.html - iFrame Demo)
└── docs/
    ├── summary.md (Master reference)
    └── reference-rules.md (This file)
```

**Note:** The site currently has both root-level HTML files and organized folder structures. The main index.html links to root-level files, while folder structures exist for better organization.

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

### Current Website Status (Updated)

**Project Structure:**

```
/pagetest/
├── index.html (Main landing page)
├── exp1_cube.html (WebGL Cube Demo - root level)
├── exp2.html (3D Text Demo - root level)
├── exp3.html (3D Model Demo - root level)
├── aframe/
│   └── index.html (A-Frame VR Demo with clickable objects)
├── audio_review/
│   └── index.html (Audio Review Tool)
└── docs/
    ├── reference-rules.md (This file)
    └── summary.md (Master reference)
```

**Current Pages:**

1. **Main Landing Page** (`index.html`)

   - Simple welcome page with links to experiments
   - Links to: Cube Demo, 3D Text Demo, 3D Model Demo
   - Status: Basic functionality, needs enhancement per summary recommendations

2. **WebGL Experiments**

   - `exp1_cube.html`: Rotating colored cube with particle effects on click
   - `exp2.html`: Three.js 3D text animation ("Ryan Hill")
   - `exp3.html`: Swarming particles WebGL demo with mouse interaction
   - Status: Functional demos, need context and professional presentation

3. **A-Frame VR Demo** (`aframe/index.html`)

   - Interactive 3D scene with clickable objects
   - Objects transform into different shapes when clicked (cycles through 8 shapes)
   - Features: Cursor interaction, smooth animations, color changes
   - Back button to return to home page
   - Status: Fully functional, showcases VR/3D interaction skills

4. **Audio Review Tool** (`audio_review/index.html`)
   - Status: Exists but needs integration with main site

**Note:** There are also experiment folders (exp1/, exp2/, exp3/, exp4/, exp5/) that may contain additional versions of experiments, but the main index currently links to root-level HTML files.

### Progress Tracking

Track improvements against summary recommendations:

- [ ] Phase 1: Foundation & Branding
- [ ] Phase 2: Content & Context
- [ ] Phase 3: Technical Improvements
- [ ] Phase 4: Advanced Features

## Current Site Features

### Active Experiments

1. **WebGL Cube Demo** (`exp1_cube.html`)

   - Rotating colored cube with WebGL
   - Particle effects on click
   - Mouse drag rotation controls

2. **3D Text Demo** (`exp2.html`)

   - Three.js text geometry
   - Rotating "Ryan Hill" text
   - Phong material with lighting

3. **Swarming Particles** (`exp3.html`)

   - WebGL particle system
   - Mouse-following behavior
   - Swarming/repulsion physics

4. **A-Frame VR Demo** (`aframe/index.html`)
   - Interactive 3D scene
   - Clickable objects that transform into different shapes
   - 8 shape types: box, sphere, cylinder, torus, octahedron, tetrahedron, cone, dodecahedron
   - Color cycling on transformation
   - Smooth elastic animations
   - VR headset compatible
   - Back navigation to home

### Technical Stack

- **WebGL**: Direct WebGL rendering for particles and cube
- **Three.js**: 3D graphics library for text demo
- **A-Frame**: VR framework for immersive 3D experiences
- **Vanilla JavaScript**: No frameworks for core functionality

### A-Frame Demo Details

**Location**: `/aframe/index.html`

**Features**:

- Interactive 3D scene with multiple primitive shapes
- Click-to-transform functionality: Objects cycle through 8 different shapes
- Dynamic color changes on each transformation
- Smooth elastic scale animations
- Raycasting cursor for object interaction
- VR mode support (works with VR headsets)
- Navigation: Back button to return to home page

**Object Transformation Cycle**:

1. Box → 2. Sphere → 3. Cylinder → 4. Torus → 5. Octahedron → 6. Tetrahedron → 7. Cone → 8. Dodecahedron → (repeats)

**Implementation Notes**:

- Uses A-Frame 1.7.1
- Custom JavaScript for object transformation logic
- Event-driven architecture for click handling
- Maintains position and rotation during transformations

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
