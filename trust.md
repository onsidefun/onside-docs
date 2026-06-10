# Trust

## The jackpot is a ledger

The jackpot number on the homepage is not a marketing counter and not a vibe. Every flow in the routing table writes a row into a public jackpot ledger, and the displayed number is the sum of those rows. The live feed next to it shows mints as they land, with the paying wallet and the amount.

## Payments are verified

A ticket order only activates after its payment receipt is verified on Solana. No verified receipt, no ticket. The same applies to marketplace sales once they open: game rights move only after the payment is proven on chain.

## You hold your assets

Tickets are Metaplex Core NFTs in your own wallet. Boost and Revive cards live in your in-game inventory bound to your wallet. We never custody your funds: payments go from your wallet to the treasury, and the winning payout goes to whichever wallet holds the winning ticket.

## The payout is verified too

When the season is settled, the winning ticket is declared on the ledger and the payout gets its own receipt. The treasury sends the full jackpot in USDC to the wallet holding the winning ticket NFT, tagged with a payout memo, and the backend reads that transaction back from Solana and checks the memo, the amount and the destination before marking the jackpot paid. The public jackpot number drains by exactly the paid amount, on the same ledger everyone watched all season. If you bought the winning ticket on the marketplace, the payout goes to you, because the claim lives in the NFT.

## Devnet now, mainnet at kickoff

The whole machine, from minting through match days, eliminations, marketplace settlement and the final jackpot payout, is running end to end on Solana devnet today, and the numbers on the homepage stream from it live. Mainnet flips on for the opener on June 11. Same code, same splits, real money.
