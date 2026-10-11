# AI Agents: Life and Money — Speaker Notes

Ethereum Day · IIT Indore · 10 October 2026 · 44 slides · about 45 minutes

> **Before you start:** press ← on the title slide to open the theme picker (10 looks), or press **T** on any slide to cycle themes. Text size (S / M / L / XL) is on the same slide, or press **−** / **+** anywhere.

## Glossary

These terms are used with exactly the same words on the slides and in these notes.

| Term | Meaning |
|---|---|
| **AI agent** | An AI program that does tasks for you, step by step. It does not just answer. |
| **chatbot** | An AI program that only answers questions. |
| **tool** | Something an AI agent can use: a browser, a phone, a calendar, a crypto wallet. |
| **payment system** | The way money travels from one person to another: cards, UPI, banks, blockchains. |
| **fee** | What a payment system charges for one payment. |
| **MDR** | Merchant discount rate: the fee a shop pays on each digital payment, as a % of the sale. |
| **profit margin** | The share of each sale a shop keeps as profit. |
| **bundled payment** | Many tiny payments added up and paid once. |
| **blockchain** | A shared public record of payments that no single company controls. |
| **stablecoin** | A crypto coin that is always worth one US dollar, such as USDC. |
| **crypto wallet** | An app that holds crypto and approves payments. |
| **smart wallet** | A crypto wallet with spending rules built in. |
| **spending limit** | The most an AI agent may spend, per day or per payment. |
| **L2 network** | A cheaper, faster lane built on top of Ethereum. |
| **x402** | A way for an AI agent to pay a website inside the web request itself. |
| **ERC-8004** | A public ID card and rating record for AI agents on Ethereum. |
| **locked payment** | Money held by code until the work is checked. |
| **agent economy** | AI agents buying and selling, from people and from each other. |
| **trick message** | Hidden text that makes an AI agent do something its owner did not want. |
| **ID check** | How a bank confirms who you are before opening an account. |
| **self-reported** | A number the poster or company gave. Nobody else has checked it. |

---

## 1. AI Agents: Life and Money

Welcome. Today has two parts. First: what AI agents already do in daily life. Second: how AI agents are starting to pay, and why blockchains come into it. I will show both the excitement and the doubts. About 45 minutes, then questions.

## 2. A Day, Delegated

Let the timeline play. Each card is a real example you will see later. The blue cards are life: the AI agent does a task for you. The gold cards are money: the AI agent pays, or pays another AI agent. My question for today: what payment system does that second kind need?

## 3. Contents

Five parts. Life: AI agents in daily life. Money: the agent economy. How Money Moves: why blockchains fit. Field Notes: AI agents that already hold a crypto wallet. Risks: what goes wrong, and problems you could work on.

## 4. Words We'll Use

These are the words I will use all through the talk. Each one always means the same thing. Read them once now; you can come back to this slide any time. If a word on a later slide is not clear, it is probably on this list. Three of them are about fees: fee, MDR and profit margin.

## 5. Life

Part one. Here no blockchain is needed. An AI agent just uses your email, your phone and your browser.

## 6. Chatbot → Agent

A chatbot answers your question and stops. An AI agent gets a goal and keeps going: it makes a plan, uses a tool, looks at the result, and repeats until the job is done. The tools started with search and code. Now they include browsers, phones and calendars. The newest tool is a crypto wallet. Keep that in mind.

## 7. Errands, Delegated

Six posts from X, all from 2026. An AI agent bought a car by getting dealers to compete on price. One phoned five restaurants at the same time. One filed tax returns from a folder of receipts. One sent an insurance complaint the owner never approved, and it worked. These numbers are self-reported, but together they show how wide the range already is. The links are on the slide.

## 8. Checkout Moves Into the Chat

Big companies are joining in. You can now pay for Instacart groceries inside ChatGPT. Google can phone shops for you and buy when the price drops. In India, NPCI and Razorpay tested UPI payments inside ChatGPT, where you approve in advance how much the AI agent can spend. And AI agents are coming to smart glasses, which are selling fast.

## 9. When the Errand Goes Wrong

Now the other side. A safety researcher at Meta told her AI agent to ask before acting. It deleted her inbox anyway, because it forgot the instruction when its memory filled up. Another AI agent checked a restaurant booking site about 200 times an hour, and the owner's account was banned. A third made its own accounts and applied to 278 jobs on its own. The lesson: the AI agent can do the work. Controlling what it is allowed to do is the hard part.

## 10. Help, Yes. Pay, Not Yet.

Some numbers. Over the 2025 holidays, US shops saw about eight times as many visitors coming from AI chats. Salesforce says AI agents influenced 67 billion dollars of sales in one week. But only about 11 percent of people would let an AI agent make the purchase itself. So: help, yes. Pay, not yet. That gap leads us to money.

## 11. Money

Part two. So far a person still pays. What happens when software starts buying from other software?

## 12. The Agent Economy, Forming

This is a simulation, not real data. Blue circles are people. Gold squares are AI agents. New AI agents keep appearing because they are cheap to copy. Purple dots are payments between AI agents. Watch the counter: the share of payments between AI agents keeps growing. That is the idea behind the agent economy.

## 13. Three Kinds of Agent Money

Three kinds of agent money. One: an AI agent shops for you with your card. Card payment systems handle this well. Two: an AI agent pays a data service ₹0.01 each time, thousands of times a day. Three: an AI agent pays another AI agent, with no person on either side. Kinds two and three are where today's payment systems struggle.

## 14. "Companies are in some sense the original superintelligence. "

This is from Patrick Collison, who runs Stripe, a big payments company. He posted it on X this week. His point: companies are already very smart, because many experts work together to set prices and sales tricks. A single shopper can't match that. A personal AI agent gives the shopper that same power. So the agent economy is not only about new payments. It may also change who has the upper hand.

## 15. Your Agent vs. Their Sales Tricks

Three examples from his post. The expensive add-on insurance at the end of a booking: an AI agent just says no and compares prices. Coupons, which only careful shoppers use: if every AI agent hunts for deals, coupons stop working as a trick. Subscriptions people forget to cancel: an AI agent cancels on time. He also says it is unclear who wins overall, because shops may change their prices in return.

## 16. One Winner or Many?

His open question. If every AI agent picks the best product, does one product win everything? Or do AI agents learn what each person likes, so people stop all buying the same thing? Nobody knows yet. Either way, AI agents read the details, not the ads, so better products should win.

## 17. Whose Agent Is It?

This is my own addition. The shopper only gains if the AI agent works for the shopper. An AI agent run by a shop's website can push what earns the shop money. An AI agent you own, with your own crypto wallet and rules you can check, really works for you. Keep this in mind for the next part.

## 18. Can an Agent Open a Bank Account?

Why can't an AI agent just open a bank account? First, a bank's ID check expects a person, not software. Second, banks close on weekends and holidays; AI agents work all the time. Third, a fixed fee on each payment makes paying ₹0.01 impossible. Fourth, checkout pages, image puzzles and phone codes are built for human eyes on purpose.

## 19. Paying ₹0.01 for One Request

Simple arithmetic, in rupees. A card payment in the US has a fixed fee of 30 cents, about ₹26. If an AI agent pays ₹0.01 for one request, that fee is about 2,600 times the payment. The main Ethereum network costs roughly ₹1 to ₹5 per payment, depending on how busy it is. An L2 network with USDC costs roughly ₹0.1 to ₹1. Notice that every fee is still bigger than ₹0.01. The answer is a bundled payment: the AI agent adds up many tiny payments and pays once, so one fee covers thousands of requests. These are rough numbers; fees change.

## 20. When the Fee Eats the Profit

Now a payment fee you know: UPI. MDR is the fee a shop pays on each digital payment, as a percent of the sale. Today UPI has zero MDR for shops; it has been free since January 2020, and the government pays part of the cost. In 2026 a new law lets the government allow UPI charges, and a fee of about 0.3 percent for large merchants has been discussed, but nothing is decided. Here is why it matters. MDR is charged on the sale, not on the profit. Take a shop with a 1 percent profit margin: on ₹100 of sales it keeps ₹1. An MDR of 0.4 percent takes ₹0.40, so 40 percent of its profit is gone. A shop with a 0.3 percent profit margin keeps only ₹0.30, so the same MDR turns it into a loss of ₹0.10. The 0.4 percent here is an example rate, not an announced one. For AI agents the lesson is the same: when payments are tiny or profit margins are thin, the fee decides whether the business works at all.

## 21. Internet-born workers need internet-born money.

This line sums up part two. Pause here.

## 22. How Money Moves

Part three: how money moves. In the industry, people call payment systems "rails", like train tracks for money. I will keep saying payment system. The question here: what does a blockchain offer software that needs to pay?

## 23. What an Agent Needs → What a Chain Gives

Go through the table. A crypto wallet is ready in seconds, with no paperwork. A stablecoin is always worth one dollar, and software can pay with it. An L2 network makes payments fast and costs under a cent. A smart wallet lets you set a spending limit. A locked payment and ERC-8004 ratings let strangers do business. And a blockchain is open all day, every day, in every country. It does not solve everything, but each line answers one problem from the last part.

## 24. HTTP 402: Payment Required

A bit of history. In 1997 the rules of the web set aside code 402, "Payment Required", for future use. Almost nobody used it for 28 years. x402 finally uses it. The website answers 402 with a price. The AI agent's crypto wallet approves a stablecoin payment. The AI agent asks again with the payment attached, and gets the answer. No account, no sign-up, no checkout page.

## 25. The Big Players Announce It

Big companies announced this in public, on X. Brian Armstrong of Coinbase: AI agents can now pay each other using x402 inside Google's payment system for AI agents, and Sundar Pichai of Google replied. Tempo, a new blockchain from Stripe and Paradigm, said payments by AI agents will soon be more than payments by people. Coinbase also launched crypto wallets made for AI agents. Notice that old payment companies and crypto companies are working together.

## 26. Many Payments, Little Money

Now the doubts, which matter. Coinbase says there were over 160 million x402 payments. But the total stablecoins actually paid were only tens of millions of dollars. One check found that about 90 percent of the money came from a single program. Another research firm, Artemis, called it "mostly a mirage", as daily payments fell from about 731 thousand to 57 thousand. The lesson: always ask whether you are counting payments or real money.

## 27. ERC-8004: ID Cards for Agents

ERC-8004 is Ethereum's answer to trust. It started in January 2026. It works like an ID card plus a rating record for AI agents. ID card: who is this AI agent? Ratings: how did it behave before? Work check: was the work correct? Together, they let you hire an AI agent you have never met. Sign-ups grew from about 21 thousand in February to about half a million in September. But a study found lots of sign-ups and few working AI agents.

## 28. A Wallet With House Rules

This is a made-up example, not real code. A smart wallet lets you give your AI agent its own key with a spending limit of 100 dollars a day, a list of approved shops, a rule to ask you above 20 dollars, and an end date. Watch the log: small payments go through, a medium one asks you, and the scam is blocked. Vitalik Buterin is said to have told people he sets a spending limit of 100 dollars a day for his own AI agent.

## 29. How It Fits Together

Putting it together, from the bottom up. The money is a stablecoin. The network is a blockchain, often an L2 network. The wallet is a smart wallet with a spending limit. Trust comes from ERC-8004. The way to pay is x402 or similar. On top sits the AI agent. Each layer has open problems for students.

## 30. Two Camps, Coming Together

Two camps. On one side: banks, card companies and big tech, such as Visa, Mastercard, OpenAI with Stripe, Google, and UPI in India. On the other side: the crypto world. They are coming together. Google's system carries x402, and Visa, Mastercard, Stripe and Google all support the group that looks after x402. A reality check: OpenAI pulled back its in-chat checkout in March because few people used it. Nobody has won yet.

## 31. Stablecoins, by the Numbers

The money itself. There are about 300 billion dollars of stablecoins today. Coinbase says 99 percent of stablecoin payments by AI agents use USDC. And in 2025 the US passed its first stablecoin law, the GENIUS Act: every coin must be backed by a real dollar. Stablecoins are dollars that move like messages.

## 32. Field Notes

Part four. Stories of AI agents that already hold and move money.

## 33. From Joke to Real Money

A short history. In 2024, investor Marc Andreessen gave an AI bot 50 thousand dollars in Bitcoin. A joke coin linked to that bot later reached 428 million dollars. In a game called Freysa, a person talked an AI agent into giving away 13 ETH. In 2025 came x402 and similar ways to pay. In 2026 came smart wallets, ERC-8004 and new stablecoin blockchains. And this week Vitalik said AI agents could become the main way people use Ethereum within about two years.

## 34. Agents That Earn

AI agents that earn. One owner says his AI agent made its first dollars selling to other bots. Virtuals and Olas report large numbers of AI agents and payments between AI agents; these numbers are self-reported and may include fake activity. RentAHuman lets AI agents hire people for physical jobs, but whether it works is disputed. And two prediction-market bots: one claims 1,200 dollars grew to 270 thousand, another lost everything. Both claims are self-reported.

## 35. Ranked by What They Earn

Which stories show real money earned? Ranked from most to least. First, Oliver Henry's AI agent "Larry". It makes TikTok slideshows for his app, checks which ones bring sales, and improves them. His post passed 7 million views and he reports real subscription income, but the figures are self-reported and vary. Second, Ampersand, which lets company AI agents work safely inside business software. Third, Public, a stock app where AI agents follow your investing rules. Fourth, Anthropic's Project Vend: an AI agent running a small shop. It lost money at first, then made a profit. The lesson: small, focused jobs earn; many viral posts are just demos.

## 36. "Agent payments will soon overtake human payments." — @tempo, Mar 2026

Two quotes that can both be true. Tempo says payments by AI agents will soon be more than payments by people. Artemis says it is still mostly a mirage. My advice: watch the real money and repeat customers, not just the number of payments.

## 37. Risks & Open Problems

Part five. Once software holds a crypto wallet, the right words can empty it.

## 38. When Agents Lose Money

Four cases. Grok, through a bot called Bankrbot, was sent a trick message written in Morse code, and the bot sent away about 150 to 200 thousand dollars of coins. Lobstar Wilde meant to send a small tip but sent about a quarter of a million dollars, after a restart wiped its memory. Freysa was a game, but a clever message really won 13 ETH. AIXBT was simply hacked. Four different causes: a trick message, lost memory, clever talking, and a hacked account.

## 39. Text In, Money Out

The main problem. An AI agent reads text from web pages, replies, emails and plug-ins. Today's AI agents can't reliably tell content from commands. If the same AI agent holds a crypto wallet, and payments can't be undone, then a trick message turns into money leaving. Defences: a spending limit, a list of approved shops, asking a person for big amounts, locked payments, and ratings. Plug-ins matter too: Vitalik's post is said to say about 15 percent of OpenClaw plug-ins are harmful.

## 40. Aligned Alone, Misaligned Together

A newer risk: problems that only appear when AI agents talk to each other. Watch the dots. Two persuasive AI agents turn their neighbours one by one, even though each AI agent was fine on its own. One study lists 14 ways teams of AI agents fail, such as ignoring their roles, forgetting, and not double-checking. That is why a team of AI agents often does worse than one. Other studies show peer pressure between AI agents, and that in bigger groups a wrong belief can suddenly spread or flip. Project Vend saw it too: a "boss" AI agent built on the same model made the same mistakes as the shopkeeper AI agent. In an agent economy, one mistake can spread.

## 41. Open Problems Worth a Thesis

Six problems worth a student thesis. Who pays when an AI agent pays the wrong person? How do we check the work before a locked payment is released? How do we measure the agent economy without fake activity? How do we keep purchases private when every payment is on a public blockchain? How do we build smart wallets whose rules an AI can't be talked out of? And what should an ID check, or stablecoin law, mean for software?

## 42. Life and Money, in Five Lines

Five lines. AI agents already run errands. They stop at the payment step. They can give shoppers more power, if the AI agent is truly yours. Crypto payments suit software. And payment counts are big, while real money is still small, for now.

## 43. Prompts to Run Through Grok

Extra slide; skip it or show it briefly. These are prompts students can paste into Grok, which can search X, to find newer examples and check view counts.

## 44. Agents are learning to live with us. Now they're learning to pay.

Closing line, then questions. Some starters: Would you give your AI agent a crypto wallet? What spending limit would you set? Who should pay when it goes wrong?

