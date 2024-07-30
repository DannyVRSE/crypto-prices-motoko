## This Internet Computer dApp gets the crypto price from Coinbase API between a range of dates ##

The output looks like this:

```
 [
     [
         1682978460, <-- start timestamp
         5.714, <-- lowest price during time range
         5.718, <-- highest price during range
         5.714, <-- price at open
         5.714, <-- price at close
         243.5678 <-- volume of traded
     ],
 ]

```

## Tech stack
Motoko

## Installation

dfx setup: https://docs.google.com/document/d/e/2PACX-1vTNicu-xuf4EiLAehHIqgfpjAnPjzqMGT-xpZVvYaAWNyvzYK_Ceve_me4PVRIxpzH7ea5PAX9NxGwY/pub

$dfx start --clean --background

$dfx deploy

## Usage
startdate:Nat64 (unix timestamp )

end date:Nat64  (unix timestamp )

pair:Text (e.g ICP-USD)

## Useful

unix timestamp converter https://www.unixtimestamp.com/
