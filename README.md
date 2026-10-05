# ipburger pricing: residential, ISP, mobile and dedicated IP costs, plus when $1/GB pay-as-you-go wins

IPBurger's pricing page shows you two completely different kinds of numbers, and that's the first thing to sort out before comparing anything. Residential and mobile proxies are sold as monthly bandwidth: pick a gigabyte allowance, pay a monthly fee. ISP, fresh and private dedicated IPs are sold per address, with traffic included. A "$14.41" and a "$79" on that same page aren't the same unit, so putting them next to each other in a spreadsheet is a category error.

The short version of what you'll find at the top of the page: residential starts at **$79/month for 7 GB**, the cheapest per-IP product is a private dedicated address at **$4.58/month** (billed annually), and there's no free trial — your first order is your test.

Below is every published tier, what the ladder actually rewards you for, and where a pay-as-you-go model gets cheaper in ways the monthly grid can't match.

## How IPBurger bills: two models, not one

There are two pricing mechanics:

| Model | Products | What you're buying |
| --- | --- | --- |
| Per GB, monthly | Residential, mobile | A bandwidth allowance you use up each billing period |
| Per IP, monthly | ISP (static residential), fresh dedicated, private dedicated | An address that's yours alone, unlimited traffic |

Everything is month-to-month with no long-term contract, and IPBurger's own FAQ says you can cancel, upgrade, downgrade or switch products from the dashboard at any time. If you burn through your bandwidth before the month ends, you top up the balance or move up a tier. Payments accepted: major cards, PayPal, and crypto including Bitcoin.

One thing worth flagging honestly: IPBurger's pricing comparison row lists residential as starting "from $59/mo with 10 GB included," while the residential product page starts at $79 for 7 GB. Those two figures don't reconcile, and I'm not going to guess which is current — check the number at checkout before you commit to anything.

## IPBurger residential proxy pricing, tier by tier

IPBurger splits residential into two pools, and the difference matters more than the price gap.

**Premium plans** use the full 100M+ rotating IP pool across 195+ countries and 2,014 cities, with ASN filtering (Verizon, AT&T, T-Mobile and hundreds more), user/pass authentication, session control up to 30-minute sticky IPs, and unlimited concurrent sessions.

**Regular plans** run a smaller pool (listed at 10M+ IPs across 195 countries) and still support country, region, city and ISP-level targeting with persistent sticky sessions.

| Plan | Traffic | Price | Per GB | Sub-users |
| --- | --- | --- | --- | --- |
| Premium Starter | 7 GB | $79/mo | $11.29 | 2 |
| Premium Plus | 16 GB | $149/mo | $9.31 | 4 |
| Premium Pro | 32 GB | $249/mo | $7.78 | 6 |
| Premium Enterprise | 100 GB | $699/mo | $7.00 | — |
| Regular | 8 GB | $69/mo | $8.63 | — |
| Regular | 18 GB | $129/mo | $7.17 | — |
| Regular | 38 GB | $229/mo | $6.03 | — |
| Regular | ~100 GB | $559/mo | $5.60 | — |

The interesting part isn't the headline rate, it's the shape of the curve. Going from 7 GB to 32 GB cuts your cost per gigabyte by about 31%. Going from 100 GB to 300 GB cuts it by nothing, because the premium ladder stops discounting at the 100 GB step. At most providers the 500 GB and 1 TB tiers are where the real savings live. Here, committing to a terabyte costs you the same per gigabyte as buying 100 GB.

Do the arithmetic on realistic monthly volumes rather than the grid:

- **30 GB/month** lands on the 25–38 GB step at $7.78/GB, so roughly **$233** for the month
- **100 GB/month** lands on the final step at $7.00/GB, so **$700**

Sticky sessions are capped at 30 minutes, which is fine for multi-step checkout or offer verification, less fine if your workflow needs an address to survive longer than that.

## Per-IP pricing: ISP, fresh and private dedicated

This is where IPBurger's product line gets more distinctive. These three products are exclusive addresses, not pool traffic.

| Product | Entry price | What's included | Locations |
| --- | --- | --- | --- |
| ISP (static residential) | from $14.41/mo per IP, billed annually | Static real-ISP address, unlimited traffic, up to 5 devices | 6 countries: US, UK, CA, DE, FR, AU |
| Fresh dedicated — Basic | $9.58/mo | 1 never-used dedicated IP, unlimited traffic, Chrome & Firefox extension, PayPal/eBay/Amazon/FB use cases | US, UK, DE, CA, FR, SG and others |
| Fresh dedicated — Plus | $18.33/mo | 2 fresh IPs | same |
| Fresh dedicated — Pro | $25.83/mo | 3 fresh IPs | same |
| Fresh dedicated — Enterprise | $1,000+/mo | Bulk, 100+ IPs, dedicated account manager, VIP support, custom integrations | same |
| Private dedicated — Basic/Plus/Pro | $4.58 / $12.08 / $18.75/mo | 1 / 3 / 5 private dedicated IPs, unlimited traffic | 5 countries |
| Mobile | from $69/mo with 10 GB included (pricing table) | Carrier-rotated 4G/5G IPs, 100+ countries, rotating or sticky up to 30 min | 100+ |

Two caveats on these numbers. First, ISP pricing is listed from $14.41 per IP per month on an annual commitment; independent trackers put the monthly-billing rate for the same product at $29.95 per IP, so the advertised entry figure depends on paying for a year up front. Second, mobile is the softest number on the page — the pricing comparison row says $69/mo with 10 GB, while third-party reviews quote mobile starting at $99/mo for 5 GB. Confirm the mobile tier directly before budgeting for it.

The structural point: the "fresh" IP range is marketed as addresses that have never been used (roughly 180 days of resting, per IPBurger's own copy), which is why the pricing exists at all. You're paying for IP history, not for bandwidth.

## What the price grid leaves out

Three things the numbers don't tell you, all of which affect the real cost.

**No free trial.** There's no way to run a benchmark on IPBurger before paying. Your first order is the test.

**A narrow refund window.** One independent review documents refunds only within 3 days of payment and only if you've used under 0.5 GB on residential plans. Other trackers report no refund window at all. Either way, "test it and decide" isn't really on the table.

**Thin trial economics.** Caproxy's breakdown of the cheapest honest way to evaluate the network lands at around $33 for five dedicated datacenter IPs, $29.95 for a single ISP address on monthly billing, or roughly $56 for 5 GB of residential traffic. That's your pre-commitment spend if you want to check latency and success rates against your own targets.

On reputation: IPBurger points to an "Excellent" Trustpilot standing with 400+ reviews, but third-party review sites report inconsistent Trustpilot scores, and at least one directory pegs its editorial rating at 3.9/5. Treat the vendor-published performance figures (99.95% success rate, 0.84s residential response, 99.99% uptime) as claims rather than benchmarks.

## Where IPBurger's price stops making sense

The pattern is consistent across the third-party pricing studies: IPBurger is competitive when you're buying **addresses**, and expensive when you're buying **gigabytes**.

At 100 GB/month of rotating residential traffic, IPBurger charges $700. Third-party comparisons put the same volume at roughly $150–$220 with other providers. At the entry step the gap is worse in percentage terms — about $90 for 8 GB at IPBurger.

The verdict from independent reviews is unusually blunt about the split:

> Paying IPBurger's per-gigabyte rate is a reasonable decision in exactly one situation: a few gigabytes a month for occasional geo-checks, ad verification, or a few hundred product pages — where the absolute invoice is small enough that the per-GB premium becomes noise.

There's a second dimension most price tables skip: **the model, not just the rate**. A monthly bandwidth allowance expires. Buy 5 GB, use 2 GB, and the rest is gone at the end of the period. That's a real cost driver for teams with lumpy workloads — one heavy week, three quiet ones.

That's the gap DataImpulse built its pricing around, and it's where the comparison gets more useful than a per-GB ranking.

## The pay-as-you-go alternative: DataImpulse's full price list

DataImpulse runs a 90M+ IP network across 195 countries and prices everything as pay-as-you-go traffic that **never expires**. Buy 5 GB or 5 TB, use it today or six months from now, and nothing resets. No subscription, no fair-use throttling, no expiry games.

Here's the complete published rate card across all four proxy types:

| Proxy type | Entry package | Standard rate | Bulk rate | Billing |
| --- | --- | --- | --- | --- |
| Residential | $5 for 5 GB | $1/GB | $0.80/GB at 1 TB · $0.70/GB at 5 TB | PAYG, traffic never expires |
| Datacenter | $5 for 10 GB | $0.50/GB | $50/100 GB · $450/1 TB ($0.45/GB) · custom from $2,250 at 5 TB+ | PAYG |
| Mobile | $5 for 2.5 GB | $2/GB | $50/25 GB · $1,600/1 TB ($1.60/GB) · custom from $8,000 at 5 TB+ | PAYG |
| Premium residential | $5 for 1 GB | $5/GB | $50 for 10 GB · custom from $20,000 at 5 TB+ | PAYG |

Same volume, both providers:

| Monthly residential volume | IPBurger | DataImpulse |
| --- | --- | --- |
| 30 GB | ~$233 (25–38 GB tier at $7.78/GB) | $30 at $1/GB |
| 100 GB | $700 (top discounted tier at $7.00/GB) | $100 at $1/GB |

The rest of the DataImpulse spec sheet, for the parts that affect whether it actually fits your workload:

- HTTP/HTTPS on port 823, SOCKS5 on port 824, rotating or sticky sessions (default 30 minutes, configurable up to 120)
- Country targeting included in the base rate; state, city, ZIP and ASN filters are billed at **2×** on standard residential, so a city-targeted 100 GB job runs about $200 rather than $100. Confirm the current billing treatment with support before you build a budget around it
- Sticky sessions are set by `sessid` in the username, which is what makes it workable for per-profile anti-detect browsers
- Integration blueprints for Scrapy, Puppeteer, Selenium, Playwright, Multilogin, AdsPower and Zapier, plus snippets in Python, Node.js, PHP, C#, Go, Ruby and cURL
- No built-in web scraping API. TechRadar's review is direct about this: DataImpulse sells raw proxy connections and a Gateway API, and you write the retry, parsing and CAPTCHA logic yourself
- Published 99.51% success rate, G2 rating of 4.8/5, 24/7 human support, and a 7-day refund policy for new users

👉 [Check DataImpulse's pay-as-you-go rates before you commit to a monthly ladder](https://bit.ly/dataimPulse)

**Where this comparison breaks down, and it's worth being clear about it:** DataImpulse doesn't sell static ISP addresses or exclusive never-used dedicated IPs. Its four products are residential, premium residential, mobile and datacenter. If your work is keeping marketplace, PayPal or ad accounts alive on addresses nobody else touches, the $14.41 ISP IP and the $9.58 fresh dedicated IP are the reason IPBurger's price list exists — and no per-GB rate on the market replaces them.

If instead your work is measured in gigabytes, the math is hard to argue with. At $1/GB, 100 GB of residential traffic costs $100 and the unused portion doesn't evaporate at the end of the month.

👉 [Grab the $5 / 5 GB residential starter and see how it performs on your targets](https://bit.ly/dataimPulse)

## A practical way to decide

Match the product to the job, not the provider to a brand preference:

- **Account management on platforms that ban first and ask later** — ISP or private dedicated IPs. Budget the per-IP price, accept the 30-minute sticky cap on rotating plans as irrelevant here, and treat IP history as the actual purchase.
- **Creating new accounts with no prior footprint** — fresh dedicated IPs, $9.58/month for the first address with unlimited traffic.
- **Social or platform testing where carrier IPs matter** — mobile, but verify the current rate first; this is the least consistent number on the page.
- **High-volume scraping, SERP work, price monitoring** — the per-GB ladder punishes you the moment volume grows. This is where a pay-as-you-go pool at $1/GB or a datacenter tier at $0.50/GB changes the invoice by an order of magnitude.

👉 [Buy DataImpulse datacenter traffic at $0.50/GB for speed-first scraping jobs](https://bit.ly/dataimPulse)

## FAQ

**Does IPBurger price per GB or per IP?**
Both, depending on the product. Residential and mobile are priced by monthly bandwidth in GB. ISP, fresh dedicated, private dedicated and mobile-adjacent dedicated products are priced per IP per month with unlimited traffic.

**Is there an IPBurger free trial?**
No. There's no advertised free trial, and the refund terms are narrow — one tracker documents refunds only within 3 days and under 0.5 GB of residential usage, others report no refund window. Scale your first order accordingly.

**What's the cheapest way to test IPBurger?**
The lowest-commitment entry points are around $33 for five dedicated datacenter IPs at $6.60 each, $29.95 for a single ISP address on monthly billing, or roughly $56 for a 5 GB residential order.

**How much is IPBurger residential, really?**
The published product-page ladder is $79 for 7 GB, $149 for 16 GB, $249 for 32 GB and $699 for 100 GB on the premium pool, with a smaller-pool regular line starting at $69 for 8 GB. That works out to $11.29/GB at entry and $7.00/GB at the top.

**Can I change or cancel plans?**
Yes. IPBurger bills monthly with no long-term contract, and its FAQ says you can upgrade, downgrade or switch products from the dashboard, and top up when you hit your bandwidth limit.

**Is IPBurger cheaper than DataImpulse per gigabyte?**
On residential traffic, no — it's roughly seven to eleven times the entry rate. At 100 GB, that's $700 versus $100. The comparison flips for exclusive static addresses, which DataImpulse doesn't sell at all.

**Does unused traffic expire at IPBurger?**
Residential and mobile are monthly bandwidth allowances, so budget for the period. If you want unused gigabytes to carry over indefinitely, that's the pay-as-you-go model, not the subscription model.

## The bottom line

ipburger pricing splits cleanly into two stories. If you need a static ISP address that nobody else is using, or a never-used IP to open accounts on, the per-IP rates are the product — and the per-gigabyte premium on this provider is irrelevant to your decision. If you need volume, the ladder stops rewarding you at 100 GB, there's no trial to soften the risk, and the short refund window means your first invoice is the test.

For everyone whose cost is driven by traffic rather than by address exclusivity, the cheaper move is a pay-as-you-go balance where the gigabytes keep indefinitely at $1/GB residential or $0.50/GB datacenter.

👉 [Compare DataImpulse's residential, mobile and datacenter pricing and start with $5](https://bit.ly/dataimPulse)
