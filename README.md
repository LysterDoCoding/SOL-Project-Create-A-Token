# SOL-Project-Create-A-Token

This project aims to offer you a basic knowledge of how to produce a token and how it works. The code I'm about to teach you will answer the questions of how and why, and the project will give you an understanding of how this works.

## Description
Token.sol is a straightforward contract demonstrating how to mint and burn tokens based on your total number of tokens. For example, if you have 1500 tokens, you can burn at least 500 tokens, and the balance will be 1000 tokens, but if you burn 1500 tokens while you still have a token of 1000, it will not change and will remain 1000 since you cannot burn another 1500 tokens when all that is left is 1000. Said it enables you to produce, transfer, and track the tokens being processed on this project.

## Getting Started
What are the requirements for this to work? The first is an Ethereum environment. Numerous Ethereum environments are available; you can look them up in Google or other Search engines. Be careful that you do your research first before you start coding in an Ethereum Environment. I use one called Remix - Ethereum IDE, which can be used on our desktop or web browsers. 

Here are the basic steps:

## Installing
- We'll need to set up an environment where you can use Ethereum and anything else that supports Ethereum, such as certain IDEs like Metamask, Remix, Geth, etc.
- Once you've decided on an IDE, open the Token.sol file and execute it in that IDE.

## Executing the program
- In the Remix - Ethereum IDE, you can click the Solidity Compiler Icon first on the left side screen if you don't have the auto compiler set.
- Following that, we go on to the Deploy and execute transaction icon, which allows you to interact with the mint and burn functions as much as you like.
- This program has two major functions: (mint) you will add tokens to your supplied address, and (burn) you will withdraw tokens from your specified address based on the quantity.

## Authors
- Sotto, Lyster Andrew D.
- Phone No. (09912966800)
- Facebook: Lyster Andrew D. Sotto (lyster.sotto.69)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
