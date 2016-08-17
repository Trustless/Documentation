# Trustless - Token Management for Humans

Token Management Information System (TMIS)

Trustless TMIS provides an Ethereum user an open source standard system for trustlessly minting, monitoring, or manipulating any number of approved tokens in exchange for ether. This code heavily borrows from code originating from ConsenSys, Ethereum, and others leading the development of Ethereum token solutions.

## [Token Templates] (https://github.com/Trustless/Factory/tree/master/Token_Contracts/contracts)

Trustless Token Templates include libraries and components slated to build tokens derived from [EIP #20 Standard Tokens] (https://github.com/ethereum/EIPs/issues/20); the original token template: [Token.sol] (https://github.com/Trustless/Factory/blob/master/Token_Contracts/contracts/StandardToken.sol). This is a github repo.

## Token Registry

Trustless Token Registry is derived from [EIP #22 Standard Token Registries] (https://github.com/ethereum/EIPs/issues/22) which is based on blockchain-side namespaces. 

Tokens generated at a Token Factory will be able to automatically register via that Factory's Registry. This saves time, reduces errors, and accomodate other human friendly features such as automated Accounting. 

Tokens not deployed by a Token Factory may be registered directly by way of code pattern validation (expensive).

A managed 

## Token Factory

Trustless Token Factory is built to be Ethereum token minting-as-a-service residing completely on the blockchain, yet will be one of the services which can be accessibly managed via a graphical user interface. 

Tokens can be used in a variety of creative and perhaps even innovative ways. Tokens and 'token data sets' could be used to fulfill a diverse set of various requirements including but not limited to assigning permissions, recognizing achievements or even storing value. 

With strategic use of standard functions we forsee early relational database capability. For this reason our factory will consider Create, Read, Update and Destroy methods upon deployment of their tokens.  

## Token Accounting

Trustless Token Accounting is essentially a top-level Token Registry for reporting on any number of registries, monitoring every assortment of tokens, and accessing their metadata. Accounting will allow the TMIS to automatically populate a user's Wallet with all the "Trustless" Tokens the user holds.

## Token Trading

Trustless Token Trading (TTT) will allow Calls and Puts to be made as well as offer personal value rating systems for the tokens held in managed accounts. Essentially tokens you are placing to the market will be the preferred tokens spent and the tokens you are looking to buy become the tokens you prefer to recieve for services. 

## [Token Wallet] (https://github.com/Trustless/Wallet)

Trustless Token Wallet is a GUI (graphical user interface) which offer intuitive human interaction with the Token Accounting, Token Factory and Token Trading functions.
