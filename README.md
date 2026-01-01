# 🧩 Design-First Content Engine

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Next.js 15](https://img.shields.io/badge/Next.js-15-black.svg)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0+-38B2AC.svg)](https://tailwindcss.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-purple.svg)](https://openai.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-black.svg)](https://vercel.com)

**A context-aware publishing platform that transforms how content is created, adapted, and distributed**  
*From simple markdown to AI-powered multi-channel publishing*

---

## 🎯 Evolution Philosophy

This isn't just a blogging platform—it's a **Design-First Content System** that evolves through four distinct phases, each building upon the last with production-grade architecture and context-aware AI integration.

> **"I don't just build interfaces; I architect systems where design meets intelligence."**

---

## 🗺️ Project Evolution Roadmap

### **Phase 2.1 — MinimalBlog Engine**
*Foundation: Clean, performant, SEO-optimized*

**Core Features:**
- ✅ Markdown-based content management with live preview
- ✅ Automatic SEO optimization (meta tags, Open Graph, JSON-LD)
- ✅ Blazing fast static generation with incremental rebuilds
- ✅ Syntax highlighting for 100+ languages
- ✅ Responsive typography system with fluid scaling
- ✅ Full-text search with Fuse.js or Algolia integration
- ✅ RSS feed, sitemap, and robots.txt generation
- ✅ Dark/light mode with system preference detection

**Technical Architecture:**
```yaml
Framework: Next.js 15 (App Router + Server Components)
Styling: Tailwind CSS + CSS Modules for critical components
Content: Markdown/MDX with gray-matter parsing
Database: SQLite (development) / PostgreSQL (production)
Search: Fuse.js (client-side) / PostgreSQL FTS (server-side)
Deployment: Vercel with edge functions for global CDN
Performance: 95+ Lighthouse scores guaranteed
