# Builder Notes on Coinbase Smart Wallet (Account Abstraction)

Smart Wallet lowers the friction of getting users onchain, especially on Base.  
From a builder’s point of view, the strongest part is how familiar the developer flow feels while still giving AA benefits.

## What feels right
- **Progressive onboarding.** Being able to start without forcing seed phrases helps conversion for non-crypto users.
- **Sponsor/Paymaster design.** Clear path to gas sponsorship unlocks practical UX patterns for growth cycles and trials.
- **SDK structure.** The interfaces are predictable; it’s easy to add one feature at a time without rewriting the app.

## Small suggestions
1. **End-to-end “first tx” sample.** A single minimal page that does connect → sign → send on Base, with comments for each step.  
2. **Error glossary.** A short table for common AA errors (invalid nonce, paymaster reject, missing policy) with quick fixes.  
3. **Next.js recipe.** A one-file example using `app/` router and server actions would cut setup time for modern stacks.

## Why it matters
The fastest way to grow Base is to let apps ship a working flow on day one.  
Smart Wallet is already close; a few extra examples would turn “evaluation” into “adoption”.

> Less friction, more shipping. That’s how Base wins new users.
