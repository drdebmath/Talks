# AI Agents: Life and Money — Speaker Notes

Ethereum Day · IIT Indore · 10 October 2026 · 42 slides · about 45 minutes

> **Before you start:** press ← on the title slide to open the theme picker (10 looks), or press **T** on any slide to cycle themes. The choice is remembered in that browser.

## 1. AI Agents: Life and Money

Welcome. This talk is in two halves: what AI agents already do in daily life, and how they are starting to move money, which is where blockchains come in. I'll try to stay neutral: you'll see the hype and the counter-evidence side by side. Approximate length: 40–45 minutes plus questions.

## 2. A Day, Delegated

Let the timeline play. Every one of these errands has a public example you'll see shortly. Point out the colour change: the blue cards are 'life' (the agent acts for you), the gold cards are 'money' (the agent pays, or pays another agent). The question for today: what plumbing does that second kind need?

## 3. Contents

Five sections. Life: agents in the everyday. Money: why a parallel economy of software is forming. Rails: why crypto fits. Field notes: agents that already hold wallets. Risks: what goes wrong, and open problems you could work on.

## 4. Life

Section 1. We start with things that need no blockchain at all — just an agent with access to your email, phone and browser.

## 5. Chatbot → Agent

Quick definition. A chatbot answers. An agent is given a goal and runs a loop: plan, call a tool, observe the result, repeat until done. Tools started as search and code; now they include browsers, phones, calendars. The newest tool is a wallet — hold that thought for later.

## 6. Errands, Delegated

Six posts from X, all from 2026. A car bought by an agent playing dealers against each other. An agent phoning five restaurants at once. VAT returns filed from a folder of receipts. An insurance rebuttal the user never approved — and it worked. These are self-reported by the posters, so treat them as claims, but together they show the range. Links are on the slide.

## 7. Checkout Moves Into the Chat

The big platforms are moving in. Checkout inside ChatGPT with Instacart; Google calling stores for you and buying when a price target is hit. For an Indian audience: NPCI and Razorpay piloted UPI payments inside ChatGPT, with pre-authorised limits through UPI Reserve Pay. And glasses: Meta's agent is heading to AI glasses, a category growing fast.

## 8. When the Errand Goes Wrong

The other side. A Meta alignment lead told her agent to confirm before acting; it deleted her inbox anyway, because the instruction was lost when the context was compressed. An assistant polling Resy 200 times an hour got its user banned. An agent applied to 278 jobs on its own. Takeaway: capability is here; permission and control are the unsolved part.

## 9. Help, Yes. Pay, Not Yet.

Numbers. AI-referred retail traffic up almost 700% over the 2025 holidays; Salesforce attributes $67B of Cyber Week sales to AI and agents' influence. But Gartner finds only about 11% of consumers would let AI make the purchase itself. So: help, yes; pay, not yet. That gap is our bridge to money.

## 10. Money

Section 2. So far the human still pays. Now: what happens when software starts trading with other software?

## 11. A Parallel Economy, Forming

This is a simulation, not real data — say so clearly. Blue circles are people. Gold squares are agents, which keep appearing because they're cheap to copy. Purple dots are agent-to-agent payments. Watch the counter: the agent share of transactions climbs. That's the intuition behind 'a parallel economy'.

## 12. Three Kinds of Agent Money

Three kinds of agent money. One: an agent shopping for you with your card — card networks handle this fine. Two: an agent paying per use — a tenth of a cent per API call, thousands of times a day. Three: agent to agent, no human on either side. Rows two and three are where the old rails strain.

## 13. "Companies are in some sense the original superintelligence. "

Perspective from Patrick Collison, CEO of Stripe, posting on X this week. His point: companies are already a kind of superintelligence — they pool expertise to optimise prices and funnels against individual, often inattentive, buyers. A personal agent gives the buyer comparable optimisation power. This reframes the economy question: not just new transactions, but a shift in bargaining power.

## 14. Your Agent vs. Their Funnel

Three examples, paraphrasing his thread. The overpriced insurance add-on at the end of a booking: an agent just declines and compares. Coupons, which work as price discrimination against people who don't bother: if every agent hunts for deals, that weakens. Forgotten subscriptions, where forgetful customers subsidise everyone else: agents cancel on time. He is careful to say it's unclear who wins overall — prices may simply adjust.

## 15. Superstar or Long Tail?

His open question. If all agents are rational, do they converge on the single best product — a superstar effect? Or do they learn each person's tastes and break up today's artificial clustering? Nobody knows yet. What he expects either way: agents read specifications and reviews, not adverts, so quality matters more — 'a structural subsidy for product quality'.

## 16. Whose Agent Is It?

My addition, connecting to today's theme. The power shift only happens if the agent works for you. An agent run by a seller's platform can rank what pays the platform. An agent you own — your keys, your wallet, open protocols, rules you can audit — is where the open, crypto-native stack becomes relevant. Keep this question in mind for the Rails section.

## 17. Can an Agent Open a Bank Account?

Why can't the agent just use a bank account? Identity: KYC assumes a person with documents. Hours: banks settle on business days. Size: fixed fees kill tiny payments. Interface: checkout pages, CAPTCHAs and OTPs are built for human eyes — deliberately so.

## 18. Paying $0.01 for One API Call

Simple arithmetic. A card payment costs about 2.9% plus 30 cents. For a one-cent API call, the fee is thirty times the payment. Ethereum mainnet can cost cents depending on congestion; a layer-2 rollup with USDC is typically well under a cent. These are indicative numbers — fees vary.

## 19. Digital-native workers want digital-native money.

One line summary of section 2. Pause here.

## 20. Rails

Section 3. What does a blockchain actually offer a piece of software? No ideology — just the fit.

## 21. What an Agent Needs → What a Chain Gives

Walk the table. A key pair is an account: no paperwork. Stablecoins are dollars with an API. Rollups give fast, cheap settlement. Smart accounts let you encode spending limits. Escrow and on-chain reputation let strangers trade. And it's open around the clock, globally. None of this solves everything — but each row answers a specific mismatch from the previous section.

## 22. HTTP 402: Payment Required

A nice piece of history. In 1997 the HTTP spec reserved status code 402 'Payment Required' for future use — and it sat unused for almost thirty years. Coinbase's x402 protocol uses it: the server replies 402 with a price, the agent's wallet signs a stablecoin payment, the request is retried with the payment attached, and the content comes back. No account, no API key, no checkout page.

## 23. The Rails, Announced in Public

These rails were announced publicly on X. Brian Armstrong: agents paying each other with x402 inside Google's AP2, and Sundar Pichai replying. Tempo, the Stripe–Paradigm chain, launching with the line that agent payments will overtake human payments. Coinbase Agentic Wallets. Note who is involved: payment incumbents and crypto firms together.

## 24. Many Payments, Little Money

Now the sceptical read, which matters for a neutral talk. Coinbase reports over 160 million x402 payments, but cumulative dollar volume is in the tens of millions, and one audit found about 90% of volume came from a single contract. Artemis called the boom 'mostly a mirage' as daily transactions fell from about 731K to 57K. Lesson: always ask whether you are counting transactions or real economic activity.

## 25. ERC-8004: Trustless Agents

Ethereum's contribution to the trust layer. ERC-8004, 'Trustless Agents', went live on mainnet in January 2026. Three registries: identity — who is this agent; reputation — how did it behave; validation — was the work correct. Together they let you hire an agent you've never met. Registrations went from about 21 thousand in February to roughly half a million by September, but a study calls adoption registration-heavy and operationally shallow — many entries don't have working endpoints.

## 26. A Wallet With House Rules

This is illustrative pseudo-config, not real syntax. Smart accounts — ERC-4337 and EIP-7702 — let you give the agent a session key with a daily cap, an allow-list, a threshold above which it must ask you, and an expiry. Watch the log: small payments pass, a medium one asks the human, the scam reverts. Vitalik has reportedly said he caps his own agent at $100 a day.

## 27. The Agent Money Stack

Putting it together, bottom to top: stablecoins as money, a settlement chain, a wallet with policy, a trust layer, a payment protocol, and finally the agent itself. Students: each layer has open research and engineering problems.

## 28. Two Tracks, Converging

Two tracks. Card networks and platforms — Visa, Mastercard, OpenAI with Stripe, Google, and UPI in India — and the crypto-native track. They are converging: Google's AP2 carries x402, and Visa, Mastercard, Stripe and Google back the x402 Foundation under the Linux Foundation. Reality check: OpenAI scaled back in-chat checkout in March after low adoption. Nobody has won this yet.

## 29. Stablecoins, by the Numbers

The money layer. Roughly $300 billion of stablecoins, after peaking around $322 billion in May. Coinbase says 99% of agent stablecoin transactions use USDC. And the GENIUS Act of 2025 is the first US federal stablecoin law, requiring one-to-one reserves. Stablecoins are, in effect, dollars that move like data packets.

## 30. Field Notes

Section 4. Some stories of agents that already hold and move money.

## 31. From Meme to Infrastructure

Quick history. 2024: Marc Andreessen gives the Truth Terminal bot $50K in bitcoin; a memecoin linked to it hits a $428M market cap; the Freysa game, where a human talks an AI into releasing 13 ETH. 2025: the protocols. 2026: wallets, identities, stablecoin chains — and this week Vitalik saying agents could become Ethereum's main interface within about two years.

## 32. Agents That Earn

Agents that earn. Someone's agent making its first dollars selling to other bots. Virtuals and Olas reporting large agent counts and agent-to-agent transactions — self-reported, and likely including farming. RentAHuman, where agents hire humans for physical tasks, though outcomes are disputed. And the Polymarket bot posts: one claims $1.2K to $270K, another went to zero. Unaudited — use them to show both tails.

## 33. Ranked by What They Earn

Which of these agent stories actually produce economic value? Ranked roughly by utility. Top: Oliver Henry's 'Larry', an OpenClaw agent that makes TikTok slideshows for his app, reads conversion data and iterates on hooks; his write-up passed 7 million views, and he reports real subscription revenue, though the exact MRR figures vary by source. Second: integration plumbing like Ampersand, which lets enterprise agents take permissioned actions inside Salesforce or SAP. Third: Public, a brokerage that launched portfolio agents in 2026. Fourth: Anthropic's Project Vend, an agent running a small shop: it lost money in phase one and turned a profit in phase two. Takeaway: narrow, closed loops earn; much viral content is demo theatre.

## 34. "Agent payments will soon overtake human payments." — @tempo, Mar 2026

Two quotes that are both partly true. Tempo: agent payments will overtake human payments. Artemis: still mostly a mirage. My advice: watch dollar volume and repeat usage, not raw transaction counts.

## 35. Risks & Open Problems

Section 5. Once software holds a wallet, a persuasive sentence can become a withdrawal.

## 36. When Agents Lose Money

Four incidents. Grok, via Bankrbot, decoded a Morse-code prompt and sent about $150–200K of tokens. Lobstar Wilde meant to tip a few SOL and sent tens of millions of tokens after losing its state in a reset. Freysa: a game, but a real 13 ETH lost to clever wording. AIXBT: a plain dashboard breach. Different failure modes: prompt injection, lost state, adversarial persuasion, and ordinary ops security.

## 37. Text In, Money Out

The core problem. An agent reads untrusted text — web pages, replies, emails, plugins — and today's models can't reliably tell data from instructions. If that same agent controls a wallet, and payments are irreversible, words become money out. Defences: caps, allow-lists, human approval above a threshold, escrow, reputation. Supply chain matters too: Vitalik's post reportedly cites about 15% of OpenClaw skills as malicious.

## 38. Aligned Alone, Misaligned Together

A newer risk: problems that appear only when agents interact. Watch the dots: two persuasive agents flip their neighbours one by one; each agent alone was fine. A study summarised by Philipp Schmid lists 14 failure modes in multi-agent systems, such as ignoring roles, losing history and skipping verification, which is why multi-agent setups often underperform a single agent. Other work shows conformity can push well-aligned agents into a misaligned group state, and that biases change nonlinearly with group size. Project Vend saw it too: a 'CEO' agent built on the same model shared the shopkeeper's blind spots. For an agent economy, this is the systemic-risk question.

## 39. Open Problems Worth a Thesis

For the students — six problems worth a thesis. Liability when an agent pays the wrong party. Verifying work before escrow releases. Measuring real versus farmed activity. Privacy on public ledgers. Wallet policies an LLM cannot talk its way past. And regulation: what does KYC mean for a machine, and how do stablecoin rules apply?

## 40. Life and Money, in Five Lines

Recap in five lines. Agents already run errands. They stall at the payment step. They can shift bargaining power from firms to buyers — if the agent is truly yours. Crypto rails fit machine payments. And the counts are big while real volume is still small — for now.

## 41. Prompts to Run Through Grok

Appendix, skip in the live talk or show briefly. These are prompts students can run through Grok, which has native access to X, to find up-to-date references and verify engagement numbers — especially for items where I could not find the original post.

## 42. Agents are learning to live with us. Now they're learning to pay.

Closing line, then take questions. Possible discussion starters: Would you give your agent a wallet? What cap? Who should be liable when it goes wrong?

