# Tool Stack for Digital Project Packs (Agent-First, v1)

## Primary Platform
- **Systeme.io**: All-in-one platform for funnel, course delivery, email, affiliate, and blog.
  - Funnel creation (landing pages, thank you pages)
  - Email sequences and broadcasts
  - Course hosting for video lessons (piracy protection)
  - Digital product delivery (ZIP packs)
  - Payment processing (one-time purchases)
  - Affiliate program management (later)
  - Blog and SEO capabilities (for content marketing)

## Content Creation Workflow
### Document Creation (HTML/CSS A4 Templates)
- **Agent-Generated HTML/CSS**: Use `high-end-visual-design` skill to create A4 print-ready worksheets.
- **Output**: HTML files converted to .docx via pandoc or browser print.
- **NO Microsoft 365, NO Adobe Creative Cloud, NO paid design tools** — free/agent-generated only.

### Video Production
- **Script**: Internal video script (file 10) written by agents.
- **Recording**: OBS Studio (free) for screen/webcam capture.
- **Editing**: DaVinci Resolve (free) or Shotcut (free) to produce MP4 lessons.
- **NO paid video editing tools** — free alternatives only.

### AI Prompts
- **Engineered Upfront**: AI prompts (file 06) created by agents for each pack.
- **User Runs**: Customer inputs their parameters in their LLM (e.g., Claude, GPT) to generate customized starting points.
- **NO external AI API costs** — uses Hermes agent or local LLM.

### Document Assembly
- **ZIP Packaging**: Agent-generated script (bash/python) to gather files 01-04, 06-09 and compress.
- **Automation**: Scripts can be triggered by agent or manually by CEO.

## File Storage & Delivery
- **Systeme.io File Storage**: Hosts all digital product files (ZIP packs, course videos).
- **NO Google Drive/Dropbox for primary delivery** — Systeme.io is the source of truth.
- **Backup**: Optional free Google Drive for agent workspace.

## Email & Communication
- **Systeme.io Email Automation**: Primary email sequences and broadcasts.
- **NO Gmail/Outlook for marketing** — all marketing via Systeme.io.
- **Customer Support**: Email via Systeme.io (ticketing) + knowledge base in Notion (free).

## Analytics & Tracking
- **Systeme.io Analytics**: Built-in funnel and sales tracking.
- **NOTION Dashboards**: Custom revenue and metric tracking (free).
- **NO Google Analytics, NO Facebook Pixel** — rely on Systeme.io and Notion for v1.

## Security & Legal
- **Terms of Service & Privacy Policy**: Generated via free tools (e.g., Termly.io free tier) or written by agent.
- **PayPal/Stripe**: Integrated via Systeme.io (no separate handling).

## Cost Overview (Monthly)
- Systeme.io: $27-$97/month (depending on plan) — **fixed cost, not per-user**.
- All other tools: **free** (OBS Studio, DaVinci Resolve, LibreOffice, Notion free, etc.).
- **NO Microsoft 365, NO Adobe Creative Cloud, NO paid design tools**.

## Workflow Summary
1. **Content Creation**: Agent generates HTML/CSS templates for documents, writes AI prompts and video scripts.
2. **Asset Production**: Record video lessons with OBS Studio, edit with DaVinci Resolve.
3. **AI Prompts**: Engineer upfront for each pack (file 06).
4. **Assembly**: Agent script zips files 01-04, 06-09.
5. **Upload to Systeme.io**: Create product, upload ZIP, set price, configure email delivery.
6. **Funnel Setup**: Create landing page, email sequence, thank you page in Systeme.io.
7. **Drive Traffic**: Organic Facebook groups → free lead magnet → $10 tripwire.
8. **Automated Delivery**: Systeme.io handles email, ZIP download, course access.
9. **Support**: Email via Systeme.io, knowledge base in Notion.

## Tools to Avoid (Per Guardrails)
- No Microsoft 365, no Adobe Creative Cloud, no paid design tools.
- No custom software development (IDEs, GitHub, Docker) — we do not build SaaS.
- No server infrastructure, cloud computing (AWS, Azure) — we do not host custom platforms.
- No CRM beyond Systeme.io contacts.
- No complex marketing automation platforms — Systeme.io suffices.
- No sales engagement tools — we rely on marketing-led self-serve funnel.

---
*This tool stack supports the Digital Project Packs business model: content creation → pack packaging → Systeme.io funnel → email marketing, using only free/agent-generated tools and Systeme.io for v1.*
