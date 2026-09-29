# Hiring Plan for Digital Project Packs (Agent-First Version)

## Overview
For version 1 (v1) of the Digital Project Packs business, **no outside hiring** is permitted. All production is handled by AI agents + CEO (Kiren) only. This document outlines the agent and tool stack that can produce the initial release, with a path to consider polishing/hiring after initial income and feedback.

## Team Composition (v1)
- **CEO (Kiren)**: Provides vision, approves packs, oversees Systeme.io funnel, runs agent workflows.
- **AI Agents**: Perform content creation, document generation, funnel setup, video production, and marketing tasks using approved skills and tools.
- **No external workers, contractors, or freelancers** for v1.

## Agent & Tool Stack for Initial Release
The following agents/skills/tools/websites can be used to produce the first set of project packs:

### 1. HTML/CSS for A4 Print-Ready Worksheets (Agent-Generated)
- **Skill**: `high-end-visual-design` (from Hermes skills) can generate A4-optimized HTML/CSS templates.
- **Output**: Print-ready worksheets (Introduction, Proposal, User Guide, Video Script) saved as .docx via pandoc or browser print-to-PDF then converted.
- **Tools**: 
  - Hermes agent with `high-end-visual-design` skill
  - Pandoc (free) to convert HTML to .docx
  - Inkscape (free) for vector graphics if needed
  - Google Docs (free) for final formatting and collaboration (optional, agent can generate .docx directly)

### 2. AI Content Generation for Pack Documents
- **Skill**: `autonomous-ai-agents` (Claude Code, Codex, or OpenCode) to write and refine documents.
- **Process**: 
  - Agent researches project type (from Project 11/12 specs)
  - Generates draft documents (Introduction, Proposal, User Guide, Core Deliverable, Supporting Asset, Reference Asset)
  - Uses `humanizer` skill to remove AI-isms and add natural voice
  - Outputs .txt or .md then converted to .docx/.xlsx as needed
- **Tools**: 
  - Hermes agent with coding skills
  - Local LLM (via Hermes) for generation
  - LibreOffice (free) or Google Docs for final .docx/.xlsx

### 3. Systeme.io Native Tools for Funnel/Course Delivery
- **Platform**: Systeme.io (paid plan required, but considered a fixed cost, not a hired person)
- **Used for**:
  - Landing pages (drag-and-drop builder)
  - Email automation sequences
  - Course hosting (video lessons, PDF downloads)
  - Affiliate management (later)
  - Payment processing (Stripe/PayPal integrated)
- **No external marketer needed**: Agent can set up funnels using Systeme.io GUI guided by CEO.

### 4. Video Production (Free Tools)
- **Skill**: `manim-video` or `p5js` for generating video content programmatically, or use OBS Studio + DaVinci Resolve.
- **Process**:
  - Agent writes video script (file 10) using `claude-design` or `humanizer`.
  - Record screen/webcam with OBS Studio (free).
  - Edit with DaVinci Resolve (free) or Shotcut (free).
  - Output MP4 lessons uploaded to Systeme.io course module.
- **Tools**:
  - OBS Studio (free)
  - DaVinci Resolve (free)
  - Hermes agent for script generation

### 5. Document Assembly & Packaging
- **Skill**: Agent-generated scripts (bash/python) to:
  - Gather files 01-04, 06-09 into a folder
  - Compress into ZIP
  - Upload to Systeme.io via API (if available) or manual upload.
- **Tools**:
  - Standard Linux zip command
  - Hermes agent for scripting
  - Systeme.io manual upload (agent directs CEO)

### 6. Free/Low-Cost Tools Only (v1)
- **Document Creation**: Google Docs (free), LibreOffice (free)
- **Graphics**: Canva free tier, Inkscape (free)
- **Video**: OBS Studio (free), DaVinci Resolve (free), Shotcut (free)
- **AI**: Hermes agent (included)
- **Funnel/Systeme.io**: Paid subscription but no per-user cost
- **Paid Tools Excluded**: Microsoft 365, Adobe Creative Cloud, paid design tools, paid video editors (beyond free tiers)

## Version 2 Considerations (After Initial Income + Feedback)
After the first packs are sold and feedback collected:
- Consider polishing specific packs with contracted designers (if needed for high-ticket packs).
- Consider hiring a part-time video editor if volume justifies.
- Consider hiring a marketing specialist to scale beyond organic Facebook groups.
- **Only after** validated revenue and clear ROI.

---
*This hiring plan defines the agent-first, zero-outside-hiring approach for v1 Digital Project Packs, with a path to v2 team expansion post-validation.*
