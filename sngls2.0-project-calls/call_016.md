# snglsDAO Project Call 16 Notes

### Meeting Date/Time: Thursday Jan 16, 2020 at 15:00 GMT
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/SingularDTV/snglsdao-pm/issues/17)
### [Audio/Video of the meeting]()
Moderator: Troy Murray

Scribe: Dragos Rizescu

Attendees: Milad Mostavi, Dragos Rizescu, Tyler Ward, Hartej Sawhney, Jack Cheng, Eric Chan, Mark Tsyrulnik, & Troy Murray

## Tech
Troy and Tyler were discussing to decentralize everything, put the entire website on ipfs, ens, Troy has the snglsdao.eth secured
> Milad: pretty simple, only html and JS, no backend, should be no issues
Problem is to resolve the url with ENS — not all browsers support this, Opera maybe
Workaround is to put the url into Metamask or have the domain with .link at the end — snglsdao.eth.link, someone made this service available
Another problem is with SSL certificates
Breakout on Tuesday Q:
> Blaize: has multiple questions on the SC setup repositories — which one is used where?
> Milad: Tokit.io for generate tokens, don’t need to touch them
The Sngls token contracts are the ones you need to look into to make the swap
Keep in mind to remove the Reward part of the token, just a token and build the swap function
> Blaize: we have already deployed the tokens on mainnet, so they should be findable
> Milad: Yes
> Blaize: Payments — the payment repo has payment per content, but doesn’t have listing, validator fee payment — is the functionality eveyrthing
> Milad: The listing fee, validator fee is part of the DAO, part of the Mining module
What you can do for the token contract, add dynamic support for all ERC20 tokens — for example the DAI token address changed, right now only works with Ether
The goal is to support any token for payments on Breaker for example
> Blaize: Swap token, what we do with old tokens, burn them?
> Milad: The only way you can burn them is to send them to the 0 address, but you can block them in the contract

## Marketing Asia
- Report on the market and exchanges information — send out next Monday, Jack writing the report
- Any updates from Binance, coinmarketcap — no updates
- Chinese new year promotion, kick start next week, material designed, working

## Marketing US/Europe
- Completed the rebrands of the emails, all setup, checking that everything is in place
- Continue to follow quality as the no1 metric — look at open rates, we are building a community and look that the community is engaged
- More robust updates next week
- For the Breaker we have ads launched, but it takes time to get everything approved on the platforms
- TLDR; a lot is getting done and that is going to show in the following weeks
