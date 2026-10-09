<p align="center">
  <a href="https://onpage.dev"><img src="https://raw.githubusercontent.com/seoonpage/seo-mcp-server/main/assets/onpage-dev-banner.png" alt="OnPage.dev: free SEO and AI-visibility checks for AI assistants" width="720"></a>
</p>

<h3 align="center">The SEO scanner your AI assistant uses to fix your site itself.</h3>

<p align="center">
  <a href="https://onpage.dev">onpage.dev</a> ·
  <a href="https://onpage.dev/mcp">MCP server</a> ·
  <a href="https://onpage.dev/tools/">Free tools</a> ·
  <a href="https://github.com/seoonpage/seo-mcp-server">GitHub</a> ·
  <a href="https://onpage.dev/compare">Compare</a>
</p>

---

OnPage.dev checks pages for Google and for AI search, and gives your assistant 55 tools to run the whole loop: find what is wrong, write the fix, check it before deploy, ship it to WordPress or as a pull request, send the plan to the team, keep watching, and measure the traffic it won. Free, hosted, no account and no API key.

**Connect it in one minute.** Add this URL as a connector in Claude, ChatGPT, Cursor or VS Code:

```
https://onpage.dev/mcp
```

**What agents use it for**

- Audits with stable issue codes, ready fixes and JSON-LD, checked before deploy with `scan_html`
- Fixes shipped where the code lives: the exact Yoast SEO or Rank Math fields for WordPress, a Git pull request for Next.js, Nuxt, SvelteKit, Astro, Angular, React or Vue, or a Cloudflare Worker that fixes any CMS at the edge
- Every shipped fix logged and kept live: checked about every 6 hours, the restore code sent when a deploy undoes one, the result measured per fix with a rollback plan, a client-ready report, GA4 annotations and a GitHub Action that opens an issue when a deploy undoes a fix
- Competitor pages watched: every new section, schema or length jump, with the counter-move for your page
- GA4 debugged in a real browser: double counting, tracking before consent and a cookie banner that never passes consent on
- Local SEO and internal link equity: LocalBusiness markup, NAP consistency, a page per location, internal PageRank and click depth
- Client-side React, Vue and Angular apps loaded in a real browser, with what AI crawlers miss
- Core Web Vitals from real Chrome visitors, and server logs that show what Googlebot and AI crawlers really crawl
- Accessibility against WCAG 2.1 AA for the European Accessibility Act, ecommerce product pages, cookie consent and Consent Mode v2, and the answer format that wins featured snippets
- Hreflang for multilingual sites and trust signals (E-E-A-T) across the whole site
- Question coverage for AI Mode: the sub-questions AI search fans out for a topic, and which ones your page misses
- Topic clusters from Search Console: which page owns each topic, where pages compete and which topics have no page
- AI visibility: crawler access, llms.txt, entity graph and citability checks
- Fixes ranked by traffic, using the Search Console, GA4, Ahrefs or Semrush data already in the chat
- The first screen on phone, tablet and desktop in a real browser, and a screen reader view that shows every link, button and image announced without a name
- Action plans sent where the team works: Google Sheets (one formula, no connector), Slack, Notion, Linear, Jira or GitHub Issues
- Before and after impact measurement with Search Console, GA4 or Ahrefs data, against unchanged pages as a control group
- Daily watches that alert by RSS or webhook when a `noindex`, redirect or blocked AI crawler sneaks in, and IndexNow after every fix
- Content briefs from the pages that rank, 301 redirect maps for migrations, and shareable before and after links

**Also here**

- [seo-mcp-server](https://github.com/seoonpage/seo-mcp-server): the MCP server docs, a Claude Code plugin with `/seo-check` and skills, and a GitHub Action that blocks a deploy when SEO drops below your minimum.
- [How the score works](https://onpage.dev/methodology) and [what is new](https://onpage.dev/changelog).

Listed in the [official MCP Registry](https://registry.modelcontextprotocol.io) as `dev.onpage/onpage`.
