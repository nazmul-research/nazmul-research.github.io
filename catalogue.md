# Nazmul Portfolio CMS — Product Catalogue

## Executive Summary
Nazmul Portfolio CMS is a production-ready personal brand platform designed for researchers, engineers, and technical professionals who need to publish work, manage credibility signals, and convert profile visitors into opportunities.

It combines a polished public website (Home, Projects, Research, About, Blog, Contact) with a secure admin CMS that supports content workflows, media uploads, user roles, backup/export-import, and account recovery.

The platform is optimized for practical outcomes:
- Showcase technical credibility quickly
- Keep content current without developer bottlenecks
- Capture collaboration and consulting inquiries
- Provide a clear, trustworthy professional narrative

Live Site: <https://nazmul-portfolio-blond.vercel.app/>

---

## Product Vision & Mission
### Vision
Build the most practical personal-brand CMS for technical professionals to communicate expertise with clarity and authority.

### Mission
Enable experts to publish, update, and present their body of work in minutes—without sacrificing design quality, security, or conversion performance.

---

## Problem Statement
Most personal websites fail at one or more of the following:
- Hard to update without coding
- Inconsistent content structure across pages
- Weak credibility presentation (research, projects, career story)
- Poor admin usability on mobile
- Fragile content backup/recovery process
- No secure, usable auth flows for real operations

Result: outdated profiles, missed opportunities, lower trust.

---

## Solution Overview
Nazmul Portfolio CMS delivers:
- A complete public-facing professional site
- Role-based admin dashboard for non-technical updates
- Structured content systems for Blog, Projects, Research, About, Contact
- Media and CV management
- Export/import backup controls
- Security features: lockout, password reset, 2FA, audit logs

---

## Key Features
### 1) Public Website Experience
- Home with featured projects and contact chips
- Projects listing + dedicated project detail pages
- Research publications page
- About page with structured profile narrative
- Blog with categories, filters, preview, code support
- Contact page generated from CMS data
- Dark/light mode support and responsive layout

### 2) Content Management
- Site settings management
- About CMS with three structured fields:
  - Summary
  - Career Experience
  - Academic Background
- Project CMS with:
  - Title
  - Multi-image upload
  - Excerpt (auto-generate option)
  - Details
  - Demo URL + optional GitHub URL
  - Featured toggle
- Research CMS with publication CRUD
- Blog CMS with advanced writing tools

### 3) Writing System
- Markdown-style formatting
- Inline and block code rendering
- Copy code action for readers
- Link rendering (markdown + bare URLs)
- Cover image + multi-image slider support
- Draft/publish workflow with editor-focused UX

### 4) Security & Admin Controls
- Admin users with role controls
- Password policy support
- 2FA enable/disable + recovery codes
- Session revocation actions
- Forgot/reset password flow
- Audit logging

### 5) Operations & Recovery
- One-click JSON export backup
- Import backup with dry-run and confirmation gates
- Owner-only import application

---

## Benefits for Users
### For Visitors
- Instantly understand expertise and credibility
- Access clean project and research narratives
- Better reading experience for technical content
- Clear paths to contact and collaboration

### For Site Owner
- Faster updates without code edits
- Professional consistency across all pages
- Better control over data and backup safety
- Scalable content workflow for long-term growth

---

## Use Cases
- Academic/researcher personal website
- Technical consultant portfolio
- Robotics/AI engineer professional profile
- Founder/operator credibility site
- Speaker/application-ready profile site

---

## Competitive Advantage
- Purpose-built for technical personal branding (not generic brochure templates)
- Integrated Research + Projects + Blog + About in one content system
- Security and admin controls beyond basic portfolio builders
- Backup/export-import workflow uncommon in personal sites
- High-quality UI with practical CMS ergonomics

---

## Technical Architecture Overview
- Frontend: Next.js (App Router)
- Data Layer: Prisma ORM
- Database: PostgreSQL (Neon)
- Auth: NextAuth with credential flow + role checks
- Deployment: Vercel
- Media: DB-backed media assets with API delivery
- Admin: server actions + validation + audit logs

---

## Pricing Strategy
### Recommended Model
#### Starter (Free)
- Core pages + standard CMS
- Basic blog and project/research management

#### Pro ($19–$49/month)
- Advanced backups and restore workflow
- Enhanced analytics and conversion reporting
- Priority customization support

#### Custom (Agency/Enterprise)
- White-label variant
- Custom integrations and workflows
- Dedicated support and SLA

---

## Why Choose Us
- Built for real technical professionals, not generic marketing pages
- Strong balance of design quality and operational control
- Clear conversion pathways for opportunities and collaborations
- Secure enough for production, simple enough for daily use

---

## Call to Action
If you want a serious technical brand presence that is easy to manage and built to convert, deploy Nazmul Portfolio CMS and start publishing with confidence.

---

# CMS-Ready Content Structure

## Page: Home
### Page Title
Home

### SEO Meta Title
Nazmul Islam | AI, Robotics, and Technical Portfolio

### SEO Meta Description
Explore Nazmul Islam’s projects, research, and technical writing in AI, robotics, and healthcare technology.

### Hero Section
- Headline: Build, Research, and Ship with Precision
- Subheadline: A practical portfolio of AI systems, robotics work, research contributions, and engineering execution.
- CTA: View Projects

### Section Blocks
#### Featured Work
A curated set of projects that demonstrate applied engineering, research depth, and delivery focus.

#### Research Highlights
Publications and research outcomes focused on robotics, sensing, and intelligent systems.

#### Technical Writing
Clear, practical writing on systems, implementation decisions, and lessons from real builds.

#### Contact Access
Direct communication channels for collaboration, consulting, and speaking opportunities.

### FAQ
- What does Nazmul specialize in?
- How can I collaborate?
- Where can I read research output?

### Footer Call-to-Action
Start a conversation about your next technical initiative.

---

## Page: Projects
### Page Title
Projects

### SEO Meta Title
Projects | Nazmul Islam Portfolio

### SEO Meta Description
Browse engineering projects with concise summaries, technical context, demos, and source references.

### Hero Section
- Headline: Projects That Move from Idea to Implementation
- Subheadline: Practical systems across robotics, AI, and applied engineering.
- CTA: Explore Featured Projects

### Section Blocks
#### Project Library
A searchable, visual collection of projects with clear outcomes and technical framing.

#### Demo and Repository Access
Quick access to live demos and optional source repositories for deeper review.

#### Detailed Case View
Each project has a dedicated detail page for full context, architecture, and media.

### FAQ
- Are demos available for all projects?
- Is source code public for each project?
- Can I request implementation details?

### Footer Call-to-Action
Review project details and request a technical walkthrough.

---

## Page: Research
### Page Title
Research

### SEO Meta Title
Research Publications | Nazmul Islam

### SEO Meta Description
Review selected research publications with year, venue, title, authors, and publication links.

### Hero Section
- Headline: Research Contributions with Practical Direction
- Subheadline: Publications focused on robotics, sensing, and intelligent healthcare systems.
- CTA: Read Publications

### Section Blocks
#### Publication List
Structured entries for quick evaluation: year, venue, title, and authors.

#### Access Links
Direct links to publication sources for verification and citation.

### FAQ
- What are the primary research domains?
- Where are publications hosted?
- Are collaboration opportunities open?

### Footer Call-to-Action
Discuss potential research collaboration or applied translation.

---

## Page: About
### Page Title
About

### SEO Meta Title
About Nazmul Islam | Background, Career, and Academic Profile

### SEO Meta Description
Learn about Nazmul Islam’s summary, career experience, academic background, and CV.

### Hero Section
- Headline: The Story Behind the Work
- Subheadline: A concise profile of technical focus, professional trajectory, and academic foundation.
- CTA: Download CV

### Section Blocks
#### Summary
A clear overview of current focus areas, strengths, and mission.

#### Career Experience
Role history and practical industry execution across technical domains.

#### Academic Background
Educational foundation and research trajectory shaping current work.

### FAQ
- Where is Nazmul currently based academically?
- Which domains define current focus?
- How can I access the CV?

### Footer Call-to-Action
Use this profile as your quick due-diligence reference.

---

## Page: Blog
### Page Title
Blog

### SEO Meta Title
Technical Blog | Nazmul Islam

### SEO Meta Description
Read practical technical writing, project notes, and research-adjacent insights from Nazmul Islam.

### Hero Section
- Headline: Technical Writing for Real Builders
- Subheadline: Personal updates, technical rabbit holes, and practical reflections.
- CTA: Read Latest Post

### Section Blocks
#### Filtered Reading Experience
Search and filter by category, year, month, and title for scalable archive browsing.

#### Reader-Centric Post Design
Code blocks, progress indicators, TOC, and content navigation optimized for deep reading.

#### Share and Discover
Built-in sharing, related content, and navigation to increase content reach.

### FAQ
- How often are new posts published?
- Are posts category-tagged?
- Can I share articles directly?

### Footer Call-to-Action
Follow ongoing technical notes and implementation insights.

---

## Page: Contact
### Page Title
Contact

### SEO Meta Title
Contact Nazmul Islam | Collaborations and Inquiries

### SEO Meta Description
Reach Nazmul Islam for collaborations, consulting, research, and technical discussions.

### Hero Section
- Headline: Let’s Build or Research Together
- Subheadline: Direct channels for project work, partnerships, and technical conversations.
- CTA: Send an Inquiry

### Section Blocks
#### Direct Contact Methods
Email, mobile, WhatsApp, and professional profiles in one place.

#### Professional Networks
Access LinkedIn, GitHub, and research profiles for background and context.

### FAQ
- Which channel is best for urgent contact?
- Are consulting engagements available?
- Can I reach out for research collaboration?

### Footer Call-to-Action
Start the conversation with your project or research objective.

---

# Visual References

## Homepage
![Homepage Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/)

## Projects
![Projects Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/projects)

## Research
![Research Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/research)

## About
![About Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/about)

## Blog
![Blog Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/blog)

## Contact
![Contact Screenshot](https://image.thum.io/get/width/1400/https://nazmul-portfolio-blond.vercel.app/contact)
