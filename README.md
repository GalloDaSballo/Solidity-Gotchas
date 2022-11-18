# Solidity-Gotchas
List of Gotchas for Security Research

## Overflow
0.8 doesn't check for overflow, is there any casting? Can you break invariants with it? 

## Reentrancy
Are we updating any variables after performing an external call?

## Arbitrary Address or Data
Can we inject an untrusted address? Can we use it to break invariants?

## Safe Refund / Cancel
If funds should be retrieved, can this be done safely or is there a risk? Can you envision a scenario in which the risk causes a loss? Can you generate the risk at will or do you need some external factor?
