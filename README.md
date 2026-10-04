# buy residential ip: per-IP vs per-GB billing, what you really pay, and how to get set up without wasting budget

Most people searching this phrase are one click away from paying and still not sure what they're buying. That's not indecision — the pricing is genuinely confusing. Residential proxy sellers quote in two different units, and the number that looks cheaper is often the one that costs more.

Two questions decide almost everything:

1. **Are you buying addresses or bandwidth?** Per-IP and per-GB plans are not two ways of paying for the same thing. They shape how you build your workflow.
2. **Does the balance expire?** A cheap 5 GB pack that dies in six months is not cheap if your project runs twice a year.

Everything below uses 9Proxy as the working example, because it sells both models side by side and publishes its rates, which makes the comparison concrete instead of theoretical.

## What you're actually buying when you buy a residential IP

A residential IP is an address that belongs to a real internet connection — someone's home line, routed through a device that opted into a proxy network. When your request leaves that address, the site you're hitting sees a normal household visitor from a specific city, not a rented server in a data center.

That distinction is the whole product. Data center IPs are fast and cheap and get flagged in bulk. Static ISP proxies give you a stable address registered to a carrier, but the pool is small and the price per address is high. Residential pools are the widest and the least suspicious, at the cost of addresses that rotate and don't last forever.

For 9Proxy specifically, the network is advertised at 20M+ residential IPs across 90+ countries, with targeting down to country, state, city, ZIP code and even ISP level. Protocols are HTTP, HTTPS and SOCKS5. It supports both rotating sessions and sticky ones, which matters: account work needs the same address across many requests, while scraping usually wants a fresh one every few hundred.

If your job doesn't need a real household footprint, you don't need to buy a residential IP at all. Buy data center proxies and save the money. The premium only pays for itself on targets that screen by IP reputation.

## Per-IP or per-GB: the choice that decides your bill

Here's how the two models behave in practice.

**Per-IP.** You buy a fixed number of addresses and get unlimited bandwidth on each one. On 9Proxy, unused IPs never expire, and each IP stays live for a few hours up to around 24 hours depending on the exit node. Cost is flat and predictable: 10,000 pages through one IP costs the same as 100.

This model is built for work that keeps a session alive — logged-in accounts, carts, multi-step flows, or any target that gets twitchy when the address changes mid-task. It also suits heavy payload scraping where you genuinely can't forecast bandwidth. One catch worth knowing before you buy: the per-IP model runs through 9Proxy's desktop app, which handles local port forwarding, rather than straight from the browser dashboard.

**Per-GB.** You buy traffic and generate as many endpoints as you want from the pool. Rotation is automatic per request or per session, and 9Proxy meters what you actually consume. Packages carry 180-day validity, with enterprise tiers dropping the expiry entirely.

Pick this when requests are light and numerous: SERP checks, ad verification, price sampling, geo-checking, API polling, anything where you want a different city on every call and each response is a few dozen kilobytes.

The mistake people make is buying IPs for a rotation-heavy job and then watching most of them sit idle, or buying GB for a long session and burning traffic on retries caused by the address changing under them. Rough rule: if you can name the accounts or sessions you're keeping alive, buy IPs. If you can only describe the volume of requests, buy GB.

## Full 9Proxy pricing: every package currently listed

The company raised IP-based and bundle prices on 1 June 2026 — its first adjustment since launch. GB-based pricing was left alone. The tables below reflect the post-adjustment rates.

### Residential proxies by IP (unlimited bandwidth, IPs don't expire)

| Package | Price per IP | Total | Buy |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | [Buy the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | [Buy the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $0.084 | $126 | [Buy 1,000 IPs with 500 bonus](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | [Buy the 2,500 IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | [Buy the 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | [Buy the 15,000 IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | [Buy the 25,000 IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | [Buy the 50,000 IP package](https://bit.ly/9-Proxy) |
| 100,000 IPs (business) | $0.023 | $2,300 | [Buy the 100,000 IP package](https://bit.ly/9-Proxy) |
| 200,000 IPs (business) | $0.021 | $4,140 | [Buy the 200,000 IP package](https://bit.ly/9-Proxy) |
| 500,000 IPs (business) | $0.018 | $8,625 | [Buy the 500,000 IP package](https://bit.ly/9-Proxy) |

### Residential proxies by GB (180-day validity)

| Package | Price per GB | Total | Buy |
| --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | [Buy the 5 GB pack](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $2.10 | $105 | [Buy the 50 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | [Buy the 100 GB pack](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | [Buy the 200 GB pack](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | [Buy the 1,000 GB pack](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | [Buy the 2,000 GB pack](https://bit.ly/9-Proxy) |

### Enterprise GB (no expiry)

| Package | Price per GB | Total | Buy |
| --- | --- | --- | --- |
| 3,000 GB | $0.72 | $2,160 | [Buy the 3,000 GB enterprise pack](https://bit.ly/9-Proxy) |
| 6,000 GB | $0.70 | $4,200 | [Buy the 6,000 GB enterprise pack](https://bit.ly/9-Proxy) |
| 10,000 GB | $0.68 | $6,800 | [Buy the 10,000 GB enterprise pack](https://bit.ly/9-Proxy) |

### Bundle packages (IPs plus traffic, 180-day traffic validity)

| Bundle | Contents | Price | Buy |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [Buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | [Buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [Buy the Pro bundle](https://bit.ly/9-Proxy) |

Two things are worth naming outright. First, the entry price on the GB side looks like $3.00/GB, but that's a 5 GB test pack — at 2,000 GB you're paying a quarter of that. The advertised "from $0.018/IP" and "from $0.68/GB" figures only exist at the top of each ladder. Second, the bundles aren't simply cheaper than buying the parts; they're for people who need both behaviours in one project, and the 180-day window on the traffic half is the actual benefit.

## The fine print that changes your real cost

Published rates are where the comparison starts, not where it ends. Four details move the number.

**Expiry.** GB packages run 180 days from purchase. If your workload is seasonal — a quarterly audit, a campaign spike — you'll be buying the same gigabytes again next cycle. Enterprise GB tiers remove that clock, which is why their per-GB rate being "only" a few cents lower isn't the main reason to choose them.

**Unused IPs.** Per-IP packages don't expire until you've used the addresses, so bulk buying ahead of a project doesn't burn money. If you resell to clients or run campaigns in waves, that's the difference between inventory and waste.

**Recycling.** The Today List lets you reuse any proxy from the previous 24 hours at no extra charge. 9Proxy's own materials put the saving at roughly 20–30% for recurring tasks that hit the same targets. On a 500 IP package with a nightly price check, that's not a rounding error. There's also an auto-refresh that swaps out dead IPs within about a minute instead of waiting for your retry logic to notice.

**Failed connections.** The company's policy is a credit for any proxy that fails to connect within the first minute of use. Small in principle, useful in practice when a job hangs on one bad exit node at 2 a.m.

None of this replaces testing. Third-party write-ups report sub-second average response times and success rates in the high 90s on mainstream targets, but those numbers come from vendor-adjacent pages and your target mix is not their target mix. Buy the smallest pack that's still meaningful for your use case, run your own list through it, and only then decide whether to scale. A $24 or $15 test is cheaper than a mistaken $720 commitment.

One more practical point: residential proxies are for legitimate work — competitor research, price monitoring, ad verification, authorised testing, your own accounts. Buying a residential IP doesn't change what a target site's terms allow, and mixing the two up is how people end up with banned accounts and no refund.

## How to buy: sign-up to first request

The flow is short, and the only real decision is the one above.

1. **Create the account.** 👉 [Open a 9Proxy account and register your invite code](https://bit.ly/9-Proxy) — every link on this page goes through the same sign-up route, so the invite code carries over when you register. Creating the account doesn't commit you to a package.
2. **Top up the balance and pick a package.** Pricing is balance-based: you buy a package, the value lands in your account, and you spend it on the model you chose. Card and crypto are the payment routes listed on the site.
3. **Choose how you connect.** The desktop app gives you the per-IP flow with port forwarding and optional proxy authentication. Proxy2Web is the zero-install option using username/password credentials, which is enough for browser checks and quick geo-verification. There's a public API if you'd rather drive sessions from code, and SOCKS5 support means anti-detect browsers like AdsPower, Dolphin Anty and Multilogin, plus proxychains and custom Python scripts, work without conversion tricks.
4. **Set targeting and rotation.** Pick country, then city or state where available, then decide sticky or rotating. For per-IP work, rotation is opt-in through the Auto Rotation Proxy on selected ports rather than automatic.
5. **Run a real test batch against a real target** before scaling your package up, and track success rate per region rather than as one global number. Regional ban curves differ wildly, and that's usually where a "the proxies don't work" complaint actually comes from.

Support runs 24/7 through Telegram, email and a ticket system if a session misbehaves mid-job.

## Matching a package to a job

- **Testing whether proxies are even your problem:** 5 GB at $15. Small, expiring, and fine for the purpose.
- **Nightly SERP tracking or price sampling on a handful of targets:** 50 GB at $105 covers a lot of light requests, and the Today List stretches it further.
- **Twenty to fifty accounts across a few regions:** the 100 IP pack at $24 or the 500 IP pack at $72, depending on how many profiles you're keeping separate.
- **Agency work with several clients and mixed workloads:** the Popular bundle at $180, because some tasks want pinned addresses and others just want volume.
- **Continuous monitoring across thousands of targets:** 1,000 GB at $800 with the dashboard-driven GB flow and its automatic rotation, rather than babysitting IP inventory.
- **Resellers and platform operators:** the 50,000 IP tier at $1,438 is where the per-address rate drops far enough to leave margin.

If you're between two tiers and genuinely unsure, buy the smaller one. Both IP packages and GB packages can be topped up later, and the per-unit discounts on the next tier up rarely justify paying for capacity you haven't measured yet.

## FAQ

**Is per-IP or per-GB cheaper?** There's no universal answer; it depends on payload size relative to request count. Heavy pages through a few sessions favour per-IP. Light requests across many rotating endpoints favour per-GB. Work out your average response size in kilobytes first — the arithmetic usually makes the choice obvious.

**Do unused residential IPs expire?** On per-IP packages, no — they stay in your account until used. GB packages have 180-day validity, except enterprise tiers, which don't expire.

**Can I target a specific city, ZIP or ISP?** Yes — targeting goes down to country, state, city, ZIP code and ISP level, which is what makes localised price and ad checks meaningful.

**Which protocols are supported?** HTTP, HTTPS and SOCKS5, with username/password or IP whitelist authentication on the GB side.

**How is this different from static ISP proxies?** Static ISP addresses sit on data center infrastructure registered to a carrier and stay fixed. Residential addresses are real household connections that rotate and last hours rather than indefinitely. If you need one permanent address per account for a year, residential isn't the right product.

**How many people share an IP?** That's worth asking any provider directly before you commit, and 9Proxy's support is reachable 24/7 for exactly this kind of question. If a vendor won't answer, price the plan as shared regardless of what it's called.

**How does the invite code work?** Open 👉 [the 9Proxy sign-up page with the invite code attached](https://bit.ly/9-Proxy) and the code is applied to the new account during registration; any discount it carries shows up in the account before you pay.
