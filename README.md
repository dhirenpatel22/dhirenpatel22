# Hi, I'm Dhiren Patel

Principal full-stack engineer and founder of Exivon Tech. For 13 years I've built and run web platforms for clients in North America, Europe, Canada, Asia, Australia, and the Middle East: enterprise WordPress, e-commerce, and the cloud infrastructure and AI tooling around them.

I work independently, either embedded in a client's team on contract or delivering full projects through Exivon Tech.

## What I work on

- **Enterprise web platforms**: WordPress at fleet scale (WP VIP, multisite, Gutenberg and Full Site Editing, `theme.json`), custom plugins, REST and GraphQL, Laravel. PHP 8 with Composer, PHPUnit and PHPCS/WPCS.
- **E-commerce**: WooCommerce (Memberships, Subscriptions, custom checkout, payment gateways), Shopify, Magento, custom PHP commerce, third-party travel booking integrations.
- **Cloud & DevOps**: Akamai Linode, Cloudflare (WAF, Origin CA, API), Ubuntu, nginx, PHP-FPM, MySQL/MariaDB, Redis, GitHub Actions CI, incident response and server hardening.
- **AI workflows & development**: Claude Code with custom skills, MCP connectors and permission rules; Python/FastAPI; Electron and React desktop tooling.

## Recent work

- **Publisher platform** (current, full-time contract): I own 39 WordPress sites on ~63 Linode servers and 87 Cloudflare zones. Audited 33 sites (464 findings), contained 6 live compromises (cryptominer, webshells, JS card skimmer) and closed ~111 GB of publicly exposed backups.
- **WordPress plugin overhaul**: rebuilt a WordPress.org plugin that had been closed for guideline violations as v2.0. Fixed XSS across 25 shortcodes, removed ~95,000 lines of vendored code, cut WPCS violations from ~3,728 to 29, and added 53 tests on Docker-based wp-env.
- **Membership directory sync**: two plugins that keep a WooCommerce Memberships/Subscriptions store and a read-only directory site in sync, using webhooks, a 15-minute incremental sync, a daily reconciliation with a 20% deletion guard, and a cursor-paginated REST feed.
- **Genie** (private): an Electron and React macOS app that isolates Claude Code per client, with a libsodium-encrypted vault unlocked by Touch ID, a Unix-socket secrets daemon and multi-Mac sync with lease-based locking. Shipped v1.2 to v1.7 in three weeks.

## ShieldScope – Site Security Scanner

My plugin in the official [WordPress.org directory](https://wordpress.org/plugins/shieldscope-site-security-scanner/), published July 2026. It runs a read-only security audit of a WordPress site and reports vulnerabilities, malware, outdated software and misconfigurations. No writes, no surprises.

It comes from the same hardening work I do on production sites: multi-layer authentication, input sanitization, and closing vulnerability classes before deployment.

## Numbers I stand behind

| Metric | Result |
|---|---|
| Experience | 13 years |
| Estate I run today | 39 sites · ~63 servers · 87 Cloudflare zones |
| Live compromises contained | 6, two with zero downtime |
| Platform scale | 100K+ users |
| Page load | 5s → 2.5s |
| Deployment errors | −70% via CI/CD |
| Core Web Vitals | +35% across portfolios |
| Uptime | 99.9% |
| Framework impact | Dev time cut 50% across 200+ projects |
| Maintenance portfolio | 80–90 WordPress projects |

## Certifications

Advanced Professional WordPress Developer (Automattic) · WP VIP ×3: Architecture, Security, Performance · OpenAI Partner ×4: AI Technical, AI Sales, ChatGPT Deployment, Codex Deployment Practitioner · Google Prompting Essentials

## Work with me

Contract or fractional engineering, or full project delivery through Exivon Tech.

[dhirenpatel.me](https://dhirenpatel.me) · [LinkedIn](https://www.linkedin.com/in/dhirenpatel22/) · [WordPress.org](https://profiles.wordpress.org/dhirenpatel22/) · [Stack Overflow](https://stackoverflow.com/users/3890887)

Contract inquiries: contact@dhirenpatel.me
