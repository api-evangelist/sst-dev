# SST (sst-dev)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
