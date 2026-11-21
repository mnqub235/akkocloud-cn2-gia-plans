# CN2 GIA VPS Provider: Which AkkoCloud Plan Actually Fits, What the Route Really Covers, and Where the Metering Bites (Full San Jose and Frankfurt Plan Table)

If you want a China-optimised box and AkkoCloud is on your shortlist, the plan most people should buy is the San Jose **KVM-CN2-B1 mini annual special**: 1 vCPU, 1 GB RAM, 20 GB SSD and 1,200 GB of bidirectional traffic on a 1 Gbps port for ¥699 a year, works out to roughly $8.70 a month. Drop to the **A2 mini** at ¥449 a year if 800 GB of bidirectional traffic covers you. Move up only when you need 2 GB of RAM or more than 3 TB of transfer, because above the entry tier you are mostly buying bandwidth, not CPU.

Both entry plans run the same network: China Telecom reaches the server over CN2 GIA, and the return path for Telecom, Unicom and Mobile all goes out over CN2 GIA. That routing detail, the bidirectional metering and the refund terms decide whether this provider suits you, so the rest of this page takes them in that order.

> **Quick pick:** San Jose KVM-CN2-B1 mini annual special, ¥699/year (~$8.70/mo), 1 vCPU / 1 GB / 20 GB SSD / 1,200 GB bidirectional on 1 Gbps. Best value for a proxy, API gateway or low-traffic site with mainland users. No mainland audience at all? Skip GIA entirely and buy a cheap Tier 1 box somewhere else.
>
> 👉 [Check current AkkoCloud plan availability and pricing](https://bit.ly/akkocloud)

## Full AkkoCloud San Jose plan table

All twelve current San Jose SKUs are below, including the three legacy `-old` variants that still appear on the cart page with identical specs to their current counterparts.

| Plan | vCPU / RAM / SSD | Port and traffic | Price (CNY) | Order |
| --- | --- | --- | --- | --- |
| KVM-CN2-A2 mini (annual special) | 1 / 1 GB / 15 GB | 1 Gbps · 800 GB bidirectional | ¥449/yr (~$5.60/mo) | [Order A2 mini](https://bit.ly/akkocloud) |
| KVM-CN2-B1 mini (annual special) | 1 / 1 GB / 20 GB | 1 Gbps · 1,200 GB bidirectional | ¥699/yr (~$8.71/mo) | [Order B1 mini](https://bit.ly/akkocloud) |
| KVM-CN2-B1 | 1 / 1.5 GB / 20 GB | 1 Gbps · 1,500 GB bidirectional | ¥110/mo (~$16.45) | [Order B1](https://bit.ly/akkocloud) |
| KVM-CN2-B2 | 1 / 2 GB / 30 GB | 1 Gbps · 3,000 GB bidirectional | ¥233/mo (~$34.85) | [Order B2](https://bit.ly/akkocloud) |
| KVM-CN2-C1 | 1 / 2 GB / 30 GB | 1 Gbps · 4,000 GB bidirectional | ¥388.88/mo (~$58) | [Order C1](https://bit.ly/akkocloud) |
| KVM-CN2-D1 | 2 / 2 GB / 20 GB | 1 Gbps · 6,000 GB bidirectional | ¥588.88/mo (~$88) | [Order D1](https://bit.ly/akkocloud) |
| KVM-CN2-E1 | 4 / 8 GB / 60 GB | 1 Gbps · 9,000 GB bidirectional | ¥888.88/mo (~$133) | [Order E1](https://bit.ly/akkocloud) |
| KVM-CN2-F1 | 4 / 8 GB / 60 GB | 1 Gbps · 12,000 GB bidirectional | ¥1,188.88/mo (~$178) | [Order F1](https://bit.ly/akkocloud) |
| KVM-CN2-U1 | 2 / 2 GB / 20 GB | 30 Mbps · unmetered | ¥1,200/mo (~$179) | [Order U1](https://bit.ly/akkocloud) |
| KVM-CN2-U2 | 4 / 8 GB / 50 GB | 50 Mbps · unmetered | ¥2,100/mo (~$314) | [Order U2](https://bit.ly/akkocloud) |
| KVM-CN2-U3 | 4 / 8 GB / 80 GB | 100 Mbps · unmetered | ¥4,200/mo (~$628) | [Order U3](https://bit.ly/akkocloud) |
| KVM-CN2-U4 | 8 / 16 GB / 100 GB | 200 Mbps · unmetered | ¥8,400/mo (~$1,256) | [Order U4](https://bit.ly/akkocloud) |

Two things about this table before you read a price. First, the currency: AkkoCloud quotes in CNY on its Chinese-language cart, and the dollar figures are conversions at roughly ¥6.7 to the dollar, so your card issuer's rate will shift them a little. Second, the price source: the publicly indexed cart page lists configurations but not prices, so the CNY figures above come from a third-party plan database compiled from AkkoCloud's plan table and last checked on 17 October 2026. They were not confirmed against the live cart. Treat them as a starting point and read the number on the order page before paying.

Every San Jose plan lists a single IPv4 address and no IPv6 block. If you need IPv6 for your stack, this lineup does not advertise it.

## Frankfurt runs the same plan names on a longer path

AkkoCloud also sells a Frankfurt, Germany lineup labelled CN2 GIA with the same A2 mini through U4 naming. Storage sizes are not published for this location, so the table below covers only what is listed.

| Plan | vCPU / RAM | Port | Price (CNY) |
| --- | --- | --- | --- |
| KVM-CN2-A2 mini (annual special) | 1 / 1 GB | 1 Gbps | ¥449/yr (~$5.60/mo) |
| KVM-CN2-B1 mini (annual special) | 1 / 1 GB | 1 Gbps | ¥699/yr (~$8.71/mo) |
| KVM-CN2-B1 | 1 / 2 GB | 1 Gbps | ¥129.99/mo (~$19.44) |
| KVM-CN2-B2 | 1 / 2 GB | 1 Gbps | ¥299.99/mo (~$44.87) |
| KVM-CN2-C1 | 1 / 2 GB | 1 Gbps | ¥459.99/mo (~$68.80) |
| KVM-CN2-D1 | 2 / 4 GB | 1 Gbps | ¥699.99/mo (~$104.69) |
| KVM-CN2-E1 | 4 / 8 GB | 1 Gbps | ¥1,049.99/mo (~$157.04) |
| KVM-CN2-F1 | 4 / 8 GB | 1 Gbps | ¥1,399.99/mo (~$209.38) |
| KVM-CN2-U1 | 2 / 2 GB | 30 Mbps | ¥1,200/mo (~$179.47) |
| KVM-CN2-U2 | 4 / 8 GB | 50 Mbps | ¥2,100/mo (~$314.08) |
| KVM-CN2-U3 | 4 / 8 GB | 100 Mbps | ¥4,200/mo (~$628.16) |
| KVM-CN2-U4 | 8 / 16 GB | 200 Mbps | ¥8,400/mo (~$1,256.32) |

Frankfurt costs more per core than San Jose at every tier above the annual specials, and the round trip to China is physically longer. If your users are in mainland China or East Asia, San Jose is the location to argue with; Frankfurt only makes sense when European latency matters more than Chinese latency but you still want the GIA return path.

## What the price ladder actually buys

Look at the four 1 vCPU / 2 GB plans in a row: B2 at ¥233, C1 at ¥388.88. Same CPU, same RAM, same 30 GB disk. The only difference is 3,000 GB versus 4,000 GB of bidirectional traffic. That extra terabyte costs ¥155.88 a month. Meanwhile stepping from B2 to D1 costs ¥355.88 more and gets you a second vCPU plus 3,000 GB more transfer.

So the C1 tier is the awkward one in the family. If you are close to 3 TB and need headroom, D1 gives you more of everything for about twice the step-up. C1 exists mostly for people who want to stay on one core for licensing or workload reasons.

The U series deserves its own warning. U1 is ¥1,200 a month for 2 vCPU, 2 GB and a flat 30 Mbps. D1 is ¥588.88 a month for the same 2 vCPU and 2 GB with 6,000 GB of bidirectional transfer on a 1 Gbps port. A 30 Mbps port pinned at full tilt moves about 324 GB a day one way, or roughly 9.7 TB a month. You need to be pushing close to 10 TB a month before the unmetered 30 Mbps plan beats the metered one on price, and by then you probably want U2 or U3 anyway. "Unmetered" here means a hard port cap, not unlimited speed.

👉 [Compare the metered and unmetered tiers on the order page](https://bit.ly/akkocloud)

## Is the CN2 GIA claim real? Read the direction, not the badge

CN2 is China Telecom's second-generation backbone. CN2 GT (Global Transit) is the cheaper tier: shared capacity, more contention, and visible jitter when China's evening peak hits between 19:00 and 23:00. CN2 GIA (Global Internet Access) is the premium tier with more dedicated capacity, fewer hops and steadier loss figures during that same window. That peak-hour difference is the entire product. A route that looks fine at 10 a.m. Beijing time tells you nothing.

AkkoCloud's own wording on the San Jose listing is precise, and it is more limited than most "three-network optimised" marketing: **Telecom inbound over CN2 GIA, and the return path over CN2 GIA for all three carriers** (Telecom, Unicom, Mobile). Inbound traffic from China Unicom and China Mobile users to your server is not advertised as premium. If your audience is mostly on Unicom or Mobile and you care about upload-heavy or interactive workloads, test the actual path with a traceroute before you commit a year of prepayment.

A fully built China-facing network would carry Telecom on CN2 GIA, Unicom on AS9929 and Mobile on CMI in both directions. Single-carrier GIA with a three-carrier return is a common and cheaper compromise; it is not the same thing as a symmetric three-network premium route, and the price reflects that.

## How to test before you pay

AkkoCloud publishes its own looking glass for the San Jose node under the `sjclg` hostname on its main domain, plus one for a London node under `lonlg`. Use them rather than guessing.

1. Ping the looking-glass IP from a machine on the same Chinese ISP as your users, once at 15:00 Beijing time and again at 21:00. The second number is the one that matters.
2. Run a traceroute in both directions if the panel allows it. You want to see the China Telecom 59.43.x.x range on the path for Telecom traffic.
3. Push a real file through the looking glass's download test rather than trusting a speed-test city picker.
4. Repeat on a weekday evening. Weekend routing can differ.

The caveat that catches people: the looking-glass IP is a test address. It does not guarantee your assigned IP sits in the same /24, and AkkoCloud explicitly does not guarantee a native IP. The terms of service state that a non-native IP is not grounds for a refund. If your workload depends on a particular IP geolocation or on streaming-unlock behaviour, assume nothing and test the box after delivery, inside whatever refund window you can negotiate in writing.

## Bidirectional metering changes your maths

Every metered San Jose plan counts traffic in both directions. The A2 mini's 800 GB is 800 GB total, not 800 GB outbound. In practice that is roughly 400 GB up and 400 GB down if your traffic is symmetric, which is far less headroom than the number suggests to anyone used to outbound-only metering.

Concrete example: a proxy or VPN endpoint typically runs close to 1:1, so a 1,200 GB plan gives you about 600 GB each way. A site serving static pages with small uploads runs maybe 1:8, so the same plan stretches much further. Work out which shape your traffic has before picking a tier, and remember that backups, OS updates and package downloads from the box all count as outbound.

The three legacy `-old` SKUs on the cart page (C1 old, U1 old, E1 old) carry the same specifications and metering as their current versions. They are leftovers from an earlier pricing round, not a separate product line.

## Year one versus year two, and what renewal will cost

The two annual specials are the only plans with a published annual price, and they are not simply discounted versions of the monthly plans:

- **A2 mini** at ¥449/yr: 1 vCPU, 1 GB, 15 GB SSD, 800 GB bidirectional.
- **B1 mini** at ¥699/yr: 1 vCPU, 1 GB, 20 GB SSD, 1,200 GB bidirectional.

The jump from one to the other is ¥250 a year, about $37, for 400 GB more bidirectional traffic and 5 GB more disk. That is roughly $0.09 per extra gigabyte, which is cheaper than any monthly tier will sell you transfer. If you expect to sit between the two, buy the B1 mini.

The B1 monthly plan is a different machine: ¥110 a month, 1.5 GB RAM and 1,500 GB of traffic, which totals ¥1,320 a year. So the annual special is not a 47% discount on the same box; it is a smaller box at a lower yearly commitment. Anyone comparing "¥699/yr versus ¥110/mo" as if they were the same product will end up disappointed by the RAM.

Renewal prices for the annual specials are not published in anything I could verify. Budget year two at the same ¥449 and ¥699 and confirm the renewal figure on the order page before checkout, because promotional first-term pricing that reverts to list price is standard practice among Chinese-market hosts and this lineup gives you no written guarantee either way.

👉 [Confirm the current renewal price before you commit](https://bit.ly/akkocloud)

## How AkkoCloud sits against the usual CN2 GIA names

Three providers come up constantly in this search, and the entry prices differ by more than the marketing suggests.

| Provider / plan | Config | Port and traffic | Price | Notes |
| --- | --- | --- | --- | --- |
| AkkoCloud KVM-CN2-A2 mini | 1 vCPU / 1 GB / 15 GB SSD | 1 Gbps · 800 GB bidirectional | ¥449/yr (~$5.60/mo) | Telecom inbound GIA, three-carrier GIA return |
| HostDare CSSD0 | 1 core / 768 MB / 10 GB NVMe | 30 Mbps · 250 GB/mo | $40.99/yr | LA, CN2 GIA + CU + CM optimised; 3-day refund, may be refused above 20% monthly bandwidth use |
| HostDare CSSD1 | 1 core / 1 GB / 25 GB NVMe | 50 Mbps · 500 GB/mo | $60.99/yr | Same policy; Windows allowed but licence not included |
| ByteVirt VPS-512 | 512 MB / 15 GB SSD | 100 Mbps · 500 GB/mo | $66.00/yr | LA, CN2 GIA; listed as 0 available; throttled to 1 Mbps after overage |
| ByteVirt VPS-3072 | 3 cores / 3 GB / 60 GB SSD | 500 Mbps · 3 TB/mo | $36.30/mo | 8 in stock at last check; same overage throttle |
| DMIT LAX Pro.TINY (third-party listing) | 1 vCore / 2 GB / 20 GB SSD | 1 Gbps · 1 TB/mo | $9.90/mo or $88.88/yr | Premium tier uses CN2 GIA; DMIT's own pricing page not verified here |

The pattern: HostDare is cheaper on paper but caps you at a 30 to 50 Mbps port, ByteVirt's cheapest CN2 GIA boxes are out of stock while its in-stock tiers are monthly, and DMIT's entry Premium plan is roughly double AkkoCloud's annual special. AkkoCloud's differentiator is a 1 Gbps port at the entry price, which matters for bursty traffic and interactive sessions. Its weakness is that everything above the two annual specials is monthly-billed and priced accordingly, and the 1 vCPU / 2 GB middle tiers are poor value per yuan.

## Who should not buy this

If you have no users, customers or team members in mainland China, do not buy a CN2 GIA plan from anyone. You are paying a routing premium for a path nobody uses, and a plain Tier 1 BGP box in the same city will be cheaper and just as fast for your traffic.

If you need managed support, a control panel, or a Windows licence bundled with the server, this is a self-managed KVM product and none of that is advertised.

If your monthly transfer is above roughly 6 TB in one direction, the metered San Jose tiers stop making financial sense and you are pushed into the U series, where a 30 Mbps unmetered plan costs more than double a 6 TB metered plan with the same CPU and RAM.

## FAQ

**Is CN2 GIA worth the premium over CN2 GT?**
Only if your traffic peaks during China's 19:00–23:00 window. GIA buys dedicated capacity and lower jitter at exactly that time; GT shares capacity and degrades first. For batch jobs that run at 4 a.m., the premium buys little.

**San Jose, Frankfurt or London?**
San Jose for mainland and East Asian users. Frankfurt only if European latency outranks Chinese latency. AkkoCloud runs a London looking glass, but no London plan data is published, so it is not a buying option here.

**Will the renewal price go up?**
Unknown. The annual specials are quoted at ¥449 and ¥699 for the first term, and no renewal figure is published. Check the order page.

**Can I get a refund if the IP is not native or does not unlock a streaming service?**
The San Jose listing says a non-native IP is not grounds for a refund and points to terms of service that rule out refunds generally. Test inside the first hours of delivery and keep expectations low.

**What does bidirectional traffic mean?**
Upload and download both come out of the same allowance. A 1,200 GB plan is roughly 600 GB each way on symmetric traffic.

**Is there IPv6?**
Not on the San Jose plans, which list one IPv4 address each.

## The decision, in one place

- Under 400 GB each way per month, price-sensitive: **KVM-CN2-A2 mini**, ¥449/yr.
- 400 to 600 GB each way, or you want the extra 5 GB of disk: **KVM-CN2-B1 mini**, ¥699/yr.
- You need 2 GB RAM and 3 TB of headroom, monthly billing: **KVM-CN2-B2**, ¥233/mo.
- You need a second core and 6 TB: **KVM-CN2-D1**, ¥588.88/mo. Skip C1.
- You genuinely move more than 9 TB a month: **U1**, ¥1,200/mo, and only after you have priced U2.
- No mainland users: buy nothing here.

Before you pay, do three things: ping the San Jose looking glass at 21:00 Beijing time, confirm the renewal figure on the order page, and read the terms of service on refunds. The route is real; the fine print is where the money goes.

👉 [Open the AkkoCloud order page and confirm current San Jose pricing](https://bit.ly/akkocloud)
