# uk proxy: why free ones keep failing, which British IP type actually works, and what it costs

Search "uk proxy" and you'll get a wall of results that answer a slightly different question than the one you asked. Half of them are VPN affiliate pages. The other half sell you a £9-a-month "UK proxy" that turns out to be one shared datacenter IP in London that a sneaker site blocked two years ago.

The actual question underneath the keyword is usually narrower than it looks: you need requests to leave the internet from a British IP address, you need them to keep working, and you'd like to know what a reasonable price is before you put a card down. Some people need this once a week. Some need it ten thousand times an hour. Those two people should not buy the same thing.

This piece walks through what a UK proxy actually does, where the cheap options break, and what one provider — 9Proxy — offers specifically for UK work, including current prices and a few things worth knowing before you pay.

## What people are actually trying to do with a UK IP

The use cases behind this keyword are more specific than "be anonymous." Roughly, they fall into five groups:

- **SERP checking.** Marketers verifying what a page ranks for when Google serves results from Manchester instead of Manila. Ranking data genuinely shifts by region, which is why city-level targeting matters more here than country-level.
- **Retail and price monitoring.** UK e-commerce sites show different prices, stock and shipping options to local visitors. Scraping them from outside the UK gets you either the wrong data or a block.
- **Ad verification.** Confirming a campaign actually appears to UK users, on the right placements, without being filtered out as bot traffic.
- **Account management.** Running UK social or marketplace accounts from a consistent British address, usually alongside an antidetect browser.
- **Accessing UK-only content.** Streaming, forums, regional banking portals, and the general category of "this site doesn't load for me."

One-off streaming is a VPN job. Anything repeating, automated, or done at volume is a proxy job, and the difference matters because VPN providers optimize for a human clicking a button, not a script holding a session.

## Residential, datacenter, ISP, mobile: pick the wrong one and the rest is wasted money

"UK proxy" collapses four very different products into one phrase. They're not interchangeable.

| Type | What the IP looks like to the target site | Works well for | Where it falls down |
| --- | --- | --- | --- |
| Datacenter | A server in a hosting block | Bulk scraping of low-protection sites; speed-critical jobs | Detected fast on social platforms, retail, ticketing, finance |
| Residential | A real home connection via a UK ISP | Anything with real bot protection; localised data | Slower than datacenter; individual IPs expire after hours |
| ISP / static residential | Residential trust, datacenter speed | Long-lived accounts that need one fixed address for months | Pricier per IP; smaller pools |
| Mobile | A real 3G/4G/5G carrier address | Highest-trust scenarios, app testing, tough platforms | The most expensive per unit by a wide margin |

If you searched "uk proxy" because a site kept throwing captchas at you, residential is what you want. Datacenter IPs are cheap and fast and they're also the first thing every anti-bot vendor flags.

There's a second fork most guides skip: do you need **a fixed number of IPs** or **a lot of requests**? That decision determines your bill far more than which provider you pick.

## Why free UK proxy lists fall apart

Free proxy lists exist, and they work exactly once. The IPs come from public scrapes, get hammered by thousands of people within hours, and end up on commercial blocklists before you finish configuring them. The symptoms are familiar: timeouts on half your requests, captchas on every page, sessions dropping mid-task, and pages that load with the layout stripped out.

There's also a security angle worth a sentence rather than a lecture. An unknown proxy sees your traffic. If it isn't encrypting properly or it injects content, that's your problem to discover later.

For a one-off check, a free proxy is a fine way to confirm the concept. For anything you'd be annoyed to redo, paid residential IPs are the cheaper option once you count the hours you'll spend babysitting failures.

## 9Proxy's UK coverage, from the outside

9Proxy is a residential proxy provider that pools IPs from real consumer devices. Its advertised network is 20M+ residential IPs across 90+ countries, spread over 8,000+ servers with a stated 99.95% uptime. It supports HTTP, HTTPS and SOCKS5.

For UK specifically, the published per-country pool figures put the British inventory at roughly 446,000 IPs. That's one of the deeper European pools in the network — comparable to France (~490,000) and Germany (~385,590), and behind the US (~572,600) and Canada (~530,800). If your targets are UK retail, UK search results, or UK social platforms, that's a workable supply.

Two things it does *not* sell: datacenter proxies and ISP/static residential proxies. Mobile is handled through a separate mobile management tool rather than as a listed product line. So if your UK workflow needs a permanent static address for a long-lived account, 9Proxy alone won't cover it — you'd pair it with a second provider or look elsewhere.

### IP-based UK proxies

With this model you buy a fixed number of residential IPs and use them as you like. The key terms:

- **Unlimited bandwidth per IP** while it's active. Scrape 100 pages or 10,000 through the same address — the price doesn't move.
- **Unused IPs never expire.** No monthly clock running.
- **IP lifespan runs from a few hours to about 24 hours**, depending on the individual address. That's normal for genuine residential connections and it's the main reason heavy scraping sessions usually rotate.
- **You need the desktop app.** IP-based routing works through local port forwarding in the 9Proxy client, authenticated with the app or with proxy authentication enabled.
- **One IP is consumed each time you forward it to a port**, which is the accounting detail that surprises people.

### GB-based UK proxies

The bandwidth model works differently and suits a different job:

- You pay for data consumed, not addresses, and can generate unlimited proxy endpoints.
- Sessions are either rotating (new IP on a schedule) or sticky (hold one IP for a configured duration).
- **Targeting goes down to country, state, city, ZIP code and ISP** — this is the level that makes "UK proxy" genuinely useful for local SEO and regional pricing work.
- Traffic stays valid for **180 days**, which matters if your UK work is project-based rather than continuous.
- No desktop app needed; everything runs from the dashboard with username/password or IP whitelisting.

Two features reduce waste regardless of which model you choose. If a proxy fails within the first 60 seconds of activation, you get the credit back automatically — most providers count a dead IP as consumed. And the Today List lets you reuse any proxy from the last 24 hours at no extra charge, which is helpful when a session ends early or you're testing locations one by one.

## The full 9Proxy price list

Prices below are the published figures following the 1 June 2026 adjustment, which raised IP-based and bundle pricing while leaving GB-based plans untouched. Treat these as reference points and confirm the checkout total — third-party listings lag, and one aggregator still quotes an older pricing page with no numeric tiers at all.

### IP-based packages (pay per IP, unlimited bandwidth)

| Package | Price per IP | Total | Purchase |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | Sign up to buy IPs |
| 500 IPs | $0.144 | $72 | Sign up to buy IPs |
| 1,000 IPs + 500 bonus | $0.084 | $126 | Sign up to buy IPs |
| 2,500 IPs | $0.084 | $210 | Sign up to buy IPs |
| 5,000 IPs | $0.072 | $360 | Sign up to buy IPs |
| 15,000 IPs | $0.048 | $720 | Sign up to buy IPs |
| 25,000 IPs | $0.035 | $863 | Sign up to buy IPs |
| 50,000 IPs | $0.029 | $1,438 | Sign up to buy IPs |
| 100,000 IPs (Business) | $0.023 | $2,300 | Sign up to buy IPs |
| 200,000 IPs (Business) | $0.021 | $4,140 | Sign up to buy IPs |
| 500,000 IPs (Business) | $0.018 | $8,625 | Sign up to buy IPs |

### GB-based packages (pay per GB, rotating or sticky)

| Package | Price per GB | Total | Validity | Purchase |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | Sign up to buy GB |
| 50 GB + 5 bonus | $2.10 | $105 | 180 days | Sign up to buy GB |
| 100 GB | $1.50 | $150 | 180 days | Sign up to buy GB |
| 200 GB | $1.00 | $200 | 180 days | Sign up to buy GB |
| 1,000 GB | $0.80 | $800 | 180 days | Sign up to buy GB |
| 2,000 GB | $0.75 | $1,500 | 180 days | Sign up to buy GB |
| Enterprise GB | Custom (down to $0.68/GB at the largest tiers) | Custom | Unlimited | Sign up to buy GB |

Enterprise also adds team mode — one owner plus up to five members, with per-member traffic controls, shared bandwidth that doesn't expire and activity logs.

### Bundle packages (IPs + traffic)

| Bundle | Contents | Price | Purchase |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | Sign up for bundle pricing |
| Popular | 1,500 IPs + 50 GB | $180 | Sign up for bundle pricing |
| Pro | 5,000 IPs + 500 GB | $720 | Sign up for bundle pricing |

Bundles exist for the mixed workload: stable IPs for account-bound tasks, plus flexible traffic for high-rotation scraping. Both halves are drawn from the same balance.

### What the June 2026 change actually did

Worth flagging because a lot of directory listings haven't caught up. At the 100-IP tier the price moved from $0.20 to $0.24 per IP. The old "from $0.015/IP" headline you'll still see quoted on comparison sites came from the 500,000-IP business tier, which now sits at $0.018/IP. GB-based pricing was left alone, so if your UK work is rotation-heavy and bandwidth-light, nothing changed for you.

Payment methods include credit cards, crypto (USDT, BTC, ETH and others), Google Pay, Apple Pay and Alipay. There's no subscription — you top up a balance and spend it.

## Setting up a UK proxy: the two paths

**If you're on a GB-based plan**, setup is browser-only. Sign in to the dashboard, open the proxy generator, filter by country (UK), then narrow to state, city, ZIP or ISP if you need a specific market. Choose rotating or sticky, pick HTTP or SOCKS5, and export the endpoint as a list or in your preferred format. Credentials work with username/password or IP whitelisting, so cloud instances and CI environments don't need a client installed.

**If you're on an IP-based plan**, the path runs through the desktop client. On Linux there's a CLI, and it's blunt:


9proxy proxy -c UK -p 60000


That forwards a UK residential IP to port 60000 on localhost. Test it before wiring it into anything:


curl -x socks5://127.0.0.1:60000 https://ipinfo.io/json


If the response shows a UK location, the session is live. The same command pattern takes `-n` to pull from the Today List, which reuses proxies active in the last 24 hours without burning new ones. Useful when you're validating that a particular UK city behaves the way you expect.

For lightweight checks without any install, the browser-based Proxy2Web tool shows device status, IP details and live activity. For pipelines, there's a public API for programmatic generation and rotation.

## The reliability question you should ask before paying

In June 2026, 9Proxy went down. The website stopped loading, the desktop app timed out, prepaid IP and GB balances became unusable, and support went quiet. On 29 June the company posted a short "service disruption" notice on Facebook and its BlackHatWorld seller account — no cause, no estimated restoration time. The blackout ran roughly two and a half weeks.

The site came back around 15 July. By mid-August, third-party tracking reported that GB-based plans were working again while IP-based plans were still listed as under maintenance without a confirmed date. Independent analysis of the domain records showed no seizure indicators — a routine registrar lock, Cloudflare nameservers unchanged, registration paid through February 2027, and no law-enforcement banner — which points to an outage rather than a takedown. That distinction matters, because 2026 also produced genuine enforcement actions against other networks in this space.

What this means practically, not dramatically:

- Buy small and test against your actual target before committing to volume. The 100-IP and 5 GB tiers cost $24 and $15 respectively — that's the real trial, because there's no standard free tier.
- Don't park a year of budget in any single proxy provider. Not this one, not anyone.
- If an IP dies in the first minute, the 60-second refund covers it. Beyond that window, replacing a dead address is a manual support request — and user complaints about that process are the most common negative theme in third-party reviews, alongside the outage itself.
- Aggregated review scores are genuinely mixed. One review platform puts the provider near 4.8 on its own scoring and 4.33 from users, with praise for stability in Dolphin Anty and AdsPower; another aggregates a much lower figure driven by the outage and the replacement window. Both reflect real users.

That's the honest picture: functional, cheap, and carrying a reliability history you should price in rather than ignore.

## Pay per IP or pay per GB for UK work?

This is the decision that most often turns out wrong, and it's worth thirty seconds.

**Choose IP-based if** your UK work involves long sessions, heavy pages, video, or unpredictable data volume. Examples: holding a logged-in UK account, crawling large UK retail catalogues in one pass, downloading media through a British address. The unlimited bandwidth per IP means a data-heavy job costs the same as a light one.

**Choose GB-based if** you're making many short requests against a small number of pages, and location precision matters. Examples: UK SERP checks across ten cities, ad verification, price spot-checks, API polling. Rotation is handled for you and unused traffic sits for 180 days.

**Choose a bundle if** you genuinely need both, which happens more often on mixed UK campaigns than most buyers expect.

One constraint to keep in mind: IP-based routing requires the desktop client, so it won't drop straight into a cloud function or a container without a local forward. GB-based works from the dashboard and suits serverless environments from the start.

## Questions that come up before buying a UK proxy

**Is a UK proxy the same as a UK VPN?** No. A VPN tunnels all your device traffic to one server and is built around a person using a browser. A proxy routes specific requests and is built around tools, scripts and many concurrent sessions. For streaming once a week, a VPN is simpler and cheaper.

**Will a residential UK IP unblock UK-only sites?** Generally yes, because the address belongs to a real UK ISP connection. Whether a given service permits proxy access is set by that service's terms, so check before building a workflow around it.

**Is there a free trial?** Information on this is inconsistent across sources — some describe a limited trial available on request, while review sites state there's no free trial. Treat the smallest package as the practical evaluation, and note the 60-second refund on activation failures.

**Do I have to subscribe monthly?** No. Pricing is balance-based. Unused IPs from an IP-based purchase don't expire, and GB traffic holds for 180 days (or indefinitely on Enterprise).

**Can I target a specific UK city?** On GB-based plans, yes — down to city, ZIP code and ISP. On IP-based plans you can filter the pool by country, state, city, ZIP or ISP when selecting a proxy to forward.

## Bottom line

If you searched "uk proxy" because something kept blocking you, the fix is residential IPs from a UK pool, not another free list. What you're really choosing is a billing model: pay per IP when your bandwidth is heavy and your sessions are long, pay per GB when your requests are many, small and spread across locations.

9Proxy makes the most sense at the low end and the high end — the $24 entry package and the volume tiers where per-IP costs drop below two cents. In the middle, check whether a bundle beats buying both halves separately. And take the June 2026 outage seriously: start with a small package, test it against the exact UK sites you care about, and keep a second provider in your back pocket.

👉 Create a 9Proxy account and check the current UK pricing before the next price revision lands.
