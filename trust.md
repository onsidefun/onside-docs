# Trust

## The jackpot is a ledger

The jackpot number on the homepage is not a marketing counter and not a vibe. Every flow in the routing table writes a row into a public jackpot ledger, and the displayed number is the sum of those rows. The live feed next to it shows mints as they land, with the paying wallet and the amount.

## Payments are verified

A ticket order only activates after its payment receipt is verified on Solana. No verified receipt, no ticket. The same applies to marketplace sales once they open: game rights move only after the payment is proven on chain.

## You hold your assets

Tickets are Metaplex Core NFTs in your own wallet. Boost and Revive cards live in your in-game inventory bound to your wallet. We never custody your funds: payments go from your wallet to the treasury, and the winning payout goes to whichever wallet holds the winning ticket.

## The payouts are verified too

When the season is settled, the final-table placements are declared on the ledger and every one of the eight payouts gets its own receipt. The treasury sends each seat's USDC share to the wallet holding that ticket NFT, tagged with that payout's own memo, and the backend reads each transaction back from Solana and checks the memo, the exact amount and the destination before marking it paid. The public jackpot number drains seat by seat, by exactly the paid amounts, on the same ledger everyone watched all season, until it reads zero. If you bought a final-table ticket on the marketplace, its payout goes to you, because the claim lives in the NFT.

## Devnet now, mainnet at kickoff

The whole machine, from minting through match days, eliminations, merges, marketplace settlement and all eight final-table payouts, is running end to end on Solana devnet today, and the numbers on the homepage stream from it live. Mainnet flips on for the opener on June 11. Same code, same splits, real money.
