# 🚌 Road Notes Development Site

**Demonstrating the future of operator knowledge sharing**

*By operators, for operators, driving excellence*

<br>

## 🎯 About This Repository

This is the **development repository** for Road Notes—a proof-of-concept platform demonstrating how professional knowledge sharing can transform transit operations. This site showcases what operator-generated content can achieve when properly structured and professionally presented.

**🌐 Development Site:** [roadnotes.github.io/dev](https://roadnotes.github.io/dev)

<br>

## 💡 Purpose: Demonstrating Vision Through Example

### What This Site Is

This development site provides a **tangible demonstration** of the Road Notes vision. Rather than describing what operator knowledge sharing could look like, we've built a working example that shows:

| Feature | Description |
|---------|-------------|
| 📋 **Content Structure** | How route notes and professional articles are formatted and presented |
| 🛠️ **Platform Capabilities** | Navigation, search, responsive design, and user experience |
| ⭐ **Quality Standards** | The depth, professionalism, and practical utility we expect from contributions |
| ✅ **Proof-of-Concept** | Evidence that this approach to knowledge sharing is viable and valuable |

### Content Status

> **Note:** The content on this development site is **primarily AI-generated** to demonstrate format, scope, and quality standards. These examples illustrate what the platform can deliver—they are not yet authentic operator contributions, but they represent the level of detail and professionalism we're building toward.

**This approach allows us to:**

- Show stakeholders what the finished platform will look like
- Establish content standards before accepting submissions
- Demonstrate technical capabilities and user experience
- Provide a concrete vision rather than abstract descriptions

<br>

## 🎯 The Road Notes Vision

Road Notes represents infrastructure for professional self-organization within transit operations. This platform demonstrates how operators can systematically capture and share operational knowledge while building foundation for broader professional capabilities.

**Current Reality:** Operational wisdom exists in operators' collective experience but remains largely undocumented—passed informally between colleagues, lost when experienced operators retire, unavailable to those who need it most.

**Road Notes Solution:** Systematic platform for capturing route-specific knowledge and professional expertise, making it accessible to all operators while demonstrating that the operator community can self-organize around standards and excellence.

**Long-term Vision:** Proof-of-concept for professional transformation including evidence-based advocacy, industry-wide professional standards developed by practitioners, institutional knowledge preservation, and cross-system operational learning.

<br>

## 📚 Project Overview

### Content Structure

<table>
<tr>
<td width="50%">

#### 🛣️ Route Notes
Document route-specific operational knowledge covering timing strategies, safety considerations, stop-specific details, passenger flow patterns, and operational tips. These notes capture the practical wisdom that separates adequate service from excellent service.

</td>
<td width="50%">

#### 🎓 Pro Notes
Address professional development through in-depth articles on advanced techniques, safety protocols, operational excellence, and the craft knowledge that defines professional transit operations.

</td>
</tr>
</table>

### Technical Stack

| Component | Technology |
|-----------|-----------|
| **Platform** | MkDocs with Material theme |
| **Hosting** | GitHub Pages |
| **Version Control** | Git/GitHub |
| **Development Environment** | Visual Studio Code on macOS |
| **Content Format** | Markdown |

<br>

## 📁 Repository Structure
```
roadnotes-dev/
│
├── 📂 docs/
│   ├── 🏠 index.md                    # Development site home page
│   ├── 🛣️ Routes/                     # Example route notes
│   │   ├── route-004.md
│   │   ├── route-006.md
│   │   └── ...
│   ├── 🎓 Pronotes/                   # Example professional articles
│   │   ├── winterdrive.md
│   │   ├── pretrip.md
│   │   └── ...
│   └── 📄 Home/                       # Vision, standards, contribution
│       ├── contribute.md
│       └── standards.md
│
├── ⚙️ mkdocs.yml                      # MkDocs configuration
├── 🚫 .gitignore                      # Git ignore rules
└── 📖 README.md                       # This file
```

<br>

## 🏷️ Version Control & Release System

### Versioning Convention

Road Notes uses semantic versioning with meaningful milestone names:

**Format:** `0.X.Y`

| Digit | Meaning | Description |
|-------|---------|-------------|
| **0** | Development | Reserved for development. Production releases will use 1.X.Y and higher |
| **X** | Major Milestone | Named release (e.g., "Genesis", "Foundation") |
| **Y** | Incremental | Individual commits under current milestone |

### Current Version

> **Latest Release:** `v0.1.0` **"Genesis"** 🌱
> 
> **Tag:** `v0.1.0`
> 
> **Initial Commit:** "Commit Genesis 0.1.0"

### Release Process

Each major milestone (X version change) receives:

1. **Named Release** — Meaningful name reflecting the milestone
2. **Version Tag** — Git tag matching release version
3. **Release Assets:**
   - Source code (automatic from GitHub)
   - Site archive: `[version].[name].zip` containing complete website content
   - Release notes documenting changes and additions

### Commit Convention

| Type | Format | Example |
|------|--------|---------|
| **Milestone** | `Commit [Name] 0.X.0` | "Commit Genesis 0.1.0" |
| **Incremental** | `Commit [Name] 0.X.Y` | "Commit Genesis 0.1.1" |

All commits include descriptive messages explaining changes made.

### Version History Example
```
🌱 v0.1.0 - Genesis
    ├── 0.1.0 - Initial platform deployment
    ├── 0.1.1 - Added Route 4 example content
    ├── 0.1.2 - Enhanced navigation structure
    └── 0.1.3 - Refined Pro Notes formatting

🚀 v0.2.0 - [Future Milestone]
    ├── 0.2.0 - [Major feature addition]
    └── 0.2.X - [Incremental improvements]
```

<br>

## 🛠️ Development Workflow

### Quick Start

<table>
<tr>
<td width="33%">

**1. Clone Repository**
```bash
git clone https://github.com/roadnotes/dev.git
cd dev
```

</td>
<td width="33%">

**2. Install Dependencies**
```bash
pip install mkdocs-material
```

</td>
<td width="33%">

**3. Preview Locally**
```bash
mkdocs serve
```

</td>
</tr>
</table>

**Local preview available at:** `http://127.0.0.1:8000`

### Content Development

**Editing Workflow:**

1. Modify Markdown files in `docs/` directory
2. Changes appear immediately in local preview
3. Use VS Code Source Control panel for git operations
4. Test thoroughly before committing

### Version Control Operations

#### Making Commits
```bash
# Stage changes
git add .

# Commit with descriptive message
git commit -m "Commit Genesis 0.1.X - Description of changes"

# Push to GitHub
git push origin main
```

#### Creating Releases

When a major milestone is reached:
```bash
# Create and push version tag
git tag -a v0.X.0 -m "Release [Name] 0.X.0"
git push origin v0.X.0
```

**Then on GitHub:**

1. Navigate to repository **Releases**
2. Draft new release using created tag
3. Title: `v0.X.0 [Name]`
4. Add release notes and changelog
5. Attach site archive: `0.X.0.[Name].zip`

### Automated Deployment

**Deployment is fully automated:**
- Push triggers GitHub Actions workflow
- Site builds automatically
- Updates appear live within 2-3 minutes

<br>

## 🗺️ Project Roadmap

### Phase 1: Development Site **(Current)**

- [x] Build technical platform and establish content structure
- [x] Create example content demonstrating format and quality standards
- [x] Showcase vision through tangible demonstration
- [ ] Refine user experience and navigation
- [ ] Finalize content templates

### Phase 2: Training Community Production

- [ ] Deploy production version for line trainers and training officers
- [ ] Accept authentic operator contributions within training community
- [ ] Refine content standards through real-world application
- [ ] Prove practical value and establish governance structures

### Phase 3: System-Wide Access

- [ ] Open platform to all operators through dedicated URL
- [ ] Implement peer review panel of experienced operators
- [ ] Scale contribution and review processes
- [ ] Build comprehensive knowledge resource across entire system

### Phase 4: Industry Transformation

- [ ] Expand to multiple transit systems
- [ ] Establish professional standards and best practices
- [ ] Create evidence-based advocacy infrastructure
- [ ] Demonstrate operator-led professional self-organization

<br>

## 💎 Why This Matters

Formal training documentation serves its purpose, but operational excellence requires more. The nuances that distinguish exceptional operators from competent ones—timing strategies refined through experience, passenger flow patterns recognized over thousands of trips, situational awareness developed through real-world scenarios—this knowledge exists but rarely gets systematically captured.

> **Road Notes bridges that gap.** By creating infrastructure for operators to document and share professional knowledge, we build something larger than any individual contribution. We create a professional resource that elevates everyone's capabilities while demonstrating that operators can self-organize around standards and excellence.

**This development site proves that vision is achievable.**

<br>

## 🤝 Contributing to Development

This development repository focuses on platform development and content standards. Authentic operator contributions will be accepted through the production platform in Phase 2.

### Current Development Priorities

| Priority | Status |
|----------|--------|
| Refining content structure and templates | 🔄 In Progress |
| Enhancing user experience and navigation | 🔄 In Progress |
| Establishing quality benchmarks | ✅ Complete |
| Testing technical capabilities | 🔄 In Progress |

**Feedback and suggestions:** roadnotesvictoria@gmail.com

<br>

## 🔧 Technical Features

### Platform Capabilities

<table>
<tr>
<td width="50%">

**User Experience**
- Responsive design (desktop, tablet, mobile)
- Dark/light mode toggle
- Fast loading and smooth transitions
- Intuitive navigation structure

</td>
<td width="50%">

**Functionality**
- Full-text search across all content
- Organized navigation with expandable sections
- Table of contents for long articles
- Persistent navigation state

</td>
</tr>
</table>

### Content Standards

- Professional tone and practical focus
- Specific, actionable operational information
- Safety-first approach to all guidance
- Clear writing with logical organization
- Evidence-based recommendations

<br>

## 📧 Contact

| Purpose | Email |
|---------|-------|
| **Project Lead** | roadnotesvictoria@gmail.com |
| **Safety Concerns** | roadnotes.safety@protonmail.com |
| **Development Feedback** | roadnotesvictoria@gmail.com |

<br>

## ⚠️ Disclaimer

Road Notes is an **unofficial resource** not endorsed by, affiliated with, or approved by any transit agency, union, or governing body. This development site demonstrates platform capabilities and content standards—it does not yet contain authentic operator contributions.

Content will never replace official training, policies, or procedures. **Always follow official protocols.**