# Trust

## The jackpot is a ledger

The jackpot number on the homepage is not a marketing counter and not a vibe. Every flow in the routing table writes a row into a public jackpot ledger, and the displayed number is the sum of those rows. The live feed next to it shows mints as they land, with the paying wallet and the amount.

## Payments are verified

A ticket order only activates after its payment receipt is verified on Solana. No verified receipt, no ticket. The same applies to marketplace sales once they open: game rights move only after the payment is proven on chain.

## You hold your assets

Tickets are Metaplex Core NFTs in your own wallet. Boost and Revive cards live in your in-game inventory bound to your wallet. We never custody your funds: payments go from your wallet to the jackpot vault, a Squads 2-of-3 multisig on mainnet, and every final-table payout is a memo-tagged USDC transfer to whichever wallet holds that seat's ticket.

## Look it up yourself

Every address that touches your money is public. Paste any of these into Solscan or any Solana explorer and watch the flows live.

| What | Address |
| --- | --- |
| Jackpot vault, gets 90% of every entry | `4h5RAYeTJY2jr2gMiAaKB9aSJvEme6e2yG9QmdB9fE8M` |
| Ops vault, gets the other 10% | `VmHZdBoWjAVKPEMu3Km8QCgrpZCC5X3o5iSXo356suw` |
| The 2-of-3 Squads multisig that controls both vaults | `35D4KyqY53cJJF31jYdNYtj9Lw2Nsrypz7Ba3PkT2KBf` |
| Ticket collection (Metaplex Core) | `6WL9ghwMDfHSqLUheWPfAHuQ6NxQVW2jKaprqbeA9Xhs` |
| Payment reference key, rides on every entry payment | `onsidex2R2kNkAnhT7AphtdUMJj4Gb7duNxchkYYU39` |

Both vaults sit behind the same Squads v4 multisig: every outgoing transfer needs two of three signatures, one of them on a hardware wallet. No single hot key can touch the pot. Pay in USDC and it lands in the jackpot vault as USDC. Pay in SOL and it lands as SOL, at the price locked when you hit mint, and the treasury converts in the open from the same address.

## The payouts are verified too

When the season is settled, the final-table placements are declared on the ledger and every one of the eight payouts gets its own receipt. The treasury sends each seat's USDC share to the wallet holding that ticket NFT, tagged with that payout's own memo, and the backend reads each transaction back from Solana and checks the memo, the exact amount and the destination before marking it paid. The public jackpot number drains seat by seat, by exactly the paid amounts, on the same ledger everyone watched all season, until it reads zero. If you bought a final-table ticket on the marketplace, its payout goes to you, because the claim lives in the NFT.

## Proven on devnet, live on mainnet

The whole machine, from minting through match days, eliminations, marketplace settlement and all eight final-table payouts, ran end to end on Solana devnet before launch. Mainnet runs the exact same code and the same splits, with real money, starting with the opener on June 11.
