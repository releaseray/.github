<div align="center">

# ReleaseRay

**Transform merged code into persona-perfect release notes**

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Postgres](https://img.shields.io/badge/Postgres-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

[Website](https://releaseray.com) • [Documentation](https://www.releaseray.com/docs) • [Blog](https://www.releaseray.com/blog) 

</div>

---

## 👋 Welcome to ReleaseRay

ReleaseRay automates the entire release notes workflow—from ingesting merged PRs and issues to generating audience-specific release notes using AI, and publishing to multiple channels with one click.

**Stop manually writing release notes. Start shipping better communication.**

### 🎯 What We Do

- **📥 Smart Ingestion** — Automatically pull merged PRs and issues via GitHub/GitLab webhooks
- **🤖 AI-Powered Classification** — Group and categorize changes using OpenAI GPT-5-mini
- **👥 Persona-Specific Outputs** — Generate tailored release notes for Engineers, Internal Teams (CSM), and Customers
- **📤 Multi-Channel Publishing** — One-click publishing to GitHub Releases, GitLab Releases, Intercom Help Center, Slack, Email, and hosted changelogs
- **📊 ROI Analytics** — Track engagement, measure impact, and get weekly ROI email digests

### 🛠️ Built With Modern Tech

ReleaseRay is built with a production-grade, enterprise-ready stack:

```
Frontend:     Next.js 15 • TypeScript • Tailwind CSS • shadcn/ui • Framer Motion
Backend:      Next.js Server Actions & API Routes • Prisma ORM
Database:     PostgreSQL (Supabase) with automated migrations
Workers:      BullMQ with Upstash Redis for background jobs
AI/LLM:       OpenAI gpt-5-mini with Zod schema validation
Auth:         Supabase Auth with GitHub OAuth
Hosting:      Vercel (apps) + Fly.io (workers) + Upstash (Redis)
```

## 🚀 Featured Projects

### [📦 releaseray](https://github.com/releaseray/releaseray)
**Main SaaS Platform** — Full-stack release note automation platform with AI-powered generation and multi-channel publishing.

### [🔧 releaseray-cli](https://github.com/releaseray/releaseray-cli) *(coming soon)*
**Command-Line Interface** — Generate release notes locally without needing the full SaaS platform.

### [🧩 releaseray-action](https://github.com/releaseray/releaseray-action) *(coming soon)*
**GitHub Action** — Automate release notes generation directly in your CI/CD pipeline.

## 💡 Getting Started

### For Users
1. **Sign up** at [releaseray.com](https://releaseray.com)
2. **Connect** your GitHub or GitLab repository
3. **Configure** webhook ingestion
4. **Generate** your first AI-powered release notes
5. **Publish** to your preferred channels

### For Contributors
We welcome contributions from the community! Here's how to get started:

1. **Read our [Contributing Guide](https://github.com/releaseray/releaseray/blob/main/CONTRIBUTING.md)**
2. **Check [Good First Issues](https://github.com/releaseray/releaseray/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)**
3. **Join our [Discord Community](https://discord.gg/releaseray)**
4. **Review our [Code of Conduct](https://github.com/releaseray/releaseray/blob/main/CODE_OF_CONDUCT.md)**

## 🌟 Why Teams Choose ReleaseRay

> "ReleaseRay cut our release communication time from 2 hours to 5 minutes. Our customers finally understand what we shipped."  
> — **Engineering Team Lead, Series B SaaS**

> "The persona-specific outputs mean our CSMs get internal context while customers get clean, benefit-focused updates."  
> — **Head of Product, Enterprise Software**

- ✅ **Save 10+ hours per week** on manual release note writing
- ✅ **Increase customer engagement** with clear, tailored communication
- ✅ **Improve team alignment** with consistent release documentation
- ✅ **Reduce support tickets** by proactively communicating changes

## 📚 Resources

- **[Documentation](https://releaseray.com/docs)** — Complete setup guides, API references, and tutorials
- **[Blog](https://releaseray.com/blog)** — Release notes best practices, case studies, and product updates
- **[API Reference](https://docs.releaseray.com/api)** — REST API documentation for integrations
- **[Changelog](https://releaseray.com/changelog)** — See how we use ReleaseRay to document our own releases

## 🤝 Community & Support

- **[GitHub Discussions](https://github.com/orgs/releaseray/discussions)** — Ask questions and discuss features
- **Email Support** — [support@releaseray.com](mailto:support@releaseray.com)

## 🏢 Enterprise

ReleaseRay offers enterprise plans with:
- **Self-hosted deployment** options
- **Custom LLM models** and prompts
- **Advanced security** features (SSO, SAML, audit logs)
- **Dedicated support** and onboarding
- **Custom integrations** and API access

[Contact Sales](mailto:sales@releaseray.com) to learn more.

## 🔐 Security

Security is a top priority. We follow industry best practices:
- Multi-tier rate limiting
- Webhook signature verification
- SQL injection prevention
- Row-level security (RLS) in database
- Automated security scanning in CI

Found a security issue? Please report it responsibly to [security@releaseray.com](mailto:security@releaseray.com).

## 📊 By the Numbers

- **7** publishing channels (GitHub Releases, CHANGELOG.md, Hosted, Slack, Teams, Intercom, Email)
- **3** default personas (Engineer, Internal, Customer)
- **Up to 8** total personas with custom persona support (Team plan)
- **AI-powered** classification and generation with GPT-5-mini

## 📝 License

ReleaseRay is **proprietary software**. All rights reserved.

For licensing inquiries, contact [legal@releaseray.com](mailto:legal@releaseray.com).

---

<div align="center">

**[Get Started Free](https://releaseray.com/)** • **[View Documentation](https://www.releaseray.com/docs)** 

Made with ❤️ for engineering teams who value clear communication

© 2025 ReleaseRay. All Rights Reserved.

</div>

