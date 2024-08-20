## Uniswap V4 Airdrop Points Hook

This is a Uniswap V4 hook that shows the basic functionality of creating a points systems based on a users swap of a specfic assets. 

The contract uses the `afterSwap` hook to calculate the amount of tokens and user has swapped and mint the respecitve "points" tokens for them.

A user can them claim their rewards in the contract by burning their points tokens. 

The hook is very simple and straight forward

To run in just clone this repo.

- Run `forge install`

- Run `forge test`

