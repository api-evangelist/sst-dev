# SST (sst-dev)

SST is an open source TypeScript framework for building full-stack applications on your own infrastructure. Originally known as Serverless Stack, it now ships as a single `sst.config.ts` file that uses Pulumi and Terraform providers under the hood to deploy components across AWS, Cloudflare, and 150+ other providers. SST covers Lambda functions, containers, queues, buckets, databases, cron jobs, and front-end frameworks like Next.js, Remix, Astro, and SvelteKit, with resource linking that wires components together without hardcoded ARNs. SST Console adds a hosted dashboard for logs, issues, deployments, and autodeploy from Git.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/sst-dev/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** Open Source

## Tags

- Serverless, Infrastructure as Code, AWS, Cloudflare, TypeScript, Full-Stack, Functions, Containers, Open Source, Framework

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### SST Framework

The SST framework is an open source CLI and component library distributed via npm (`sst`) and as a Go-based CLI. Developers describe their full-stack application in a single `sst.config.ts` file using SST components (e.g. `sst.aws.Function`, `sst.aws.Bucket`, `sst.aws.Nextjs`, `sst.cloudflare.Worker`) plus any of the 150+ Pulumi/Terraform providers. The CLI (`sst init`, `sst dev`, `sst deploy`, `sst diff`, `sst remove`, `sst secret`, `sst shell`, `sst tunnel`, `sst refresh`, `sst state`) drives local development with live Lambda tunneling and production deployment with stage namespacing. The SDK exposes linked resources at runtime so app code never hardcodes infrastructure identifiers.

**Human URL:** [https://sst.dev/docs](https://sst.dev/docs)

#### Tags

- Framework, CLI, Components, TypeScript, Serverless

#### Properties

- [Documentation](https://sst.dev/docs)
- [Getting Started](https://sst.dev/docs/start)
- [Tutorial / Learn](https://sst.dev/docs/learn)
- [GitHub](https://github.com/sst/sst)
- [Changelog (Releases)](https://github.com/sst/sst/releases)
- [CLI Reference](https://sst.dev/docs/reference/cli)
- [SDK Reference](https://sst.dev/docs/reference/sdk)
- [All Components & Providers](https://sst.dev/docs/all-providers)
- [Examples](https://sst.dev/docs/examples)
- [License (MIT)](https://github.com/sst/sst/blob/dev/LICENSE)

### SST Console

SST Console is a hosted SaaS dashboard at console.sst.dev that connects to SST apps deployed to AWS. It surfaces CloudWatch logs, real-time issue detection for Node.js Lambdas and containers (with source maps and Slack/email alerts), per-update permalinks showing resource diffs and build logs, autodeploy from GitHub branches and pull requests, live `sst dev` session logs, and full resource visibility. The Console only supports apps deployed to AWS today. Personal stages are free; production-tier workspaces above 350 active resources are billed per resource per month.

**Human URL:** [https://sst.dev/docs/console](https://sst.dev/docs/console)

#### Tags

- Console, Dashboard, Monitoring, Logs, Deployments, Autodeploy

#### Properties

- [Documentation](https://sst.dev/docs/console)
- [Portal — console.sst.dev](https://console.sst.dev)
- [Sign Up](https://console.sst.dev)
- [Pricing](https://sst.dev/docs/console#pricing)
- [Autodeploy](https://sst.dev/docs/console#autodeploy)
- [Issues](https://sst.dev/docs/console#issues)
- [Console GitHub Repo](https://github.com/sst/console)

## Common Properties

- [Website](https://sst.dev)
- [Documentation](https://sst.dev/docs)
- [GitHub Organization](https://github.com/sst)
- [GitHub Repo — SST Framework](https://github.com/sst/sst)
- [GitHub Repo — SST Console](https://github.com/sst/console)
- [GitHub Repo — OpenAuth](https://github.com/sst/openauth)
- [GitHub Repo — OpenCode](https://github.com/sst/opencode)
- [GitHub Repo — OpenControl](https://github.com/sst/opencontrol)
- [Blog](https://sst.dev/blog)
- [Discord](https://sst.dev/discord)
- [Twitter / X](https://twitter.com/SST_dev)
- [YouTube](https://www.youtube.com/c/sst-dev)
- [Guide (guide.sst.dev)](https://guide.sst.dev)
- [Examples](https://sst.dev/docs/examples)
- [npm — `sst`](https://www.npmjs.com/package/sst)
- [Homebrew Tap](https://github.com/sst/homebrew-tap)
- [License — MIT](https://github.com/sst/sst/blob/dev/LICENSE)

## Notes

SST is maintained by Anomaly Innovations (parent of the `sst` GitHub org, which now redirects to `anomalyco`). The GitHub repo URL `github.com/sst/sst` remains the canonical reference. The original v2 framework (now in `sst/v2`) was a CDK-based deployer; today's SST (v3+, formerly internally called "Ion") is Pulumi/Terraform-based and is the actively maintained line.

The same team ships sibling open source projects that are not part of SST itself: OpenAuth (universal standards-based auth provider), OpenCode (open source coding agent), OpenControl (AI for infrastructure), and models.dev (open AI model database). Each of those would be profiled as its own API Evangelist entry.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

**X:** apievangelist

**URL:** [https://apievangelist.com](https://apievangelist.com)
