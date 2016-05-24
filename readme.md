# Sponsored Search Auctions

## Repository
<https://github.com/philipjlin/Sponsored_Search_Auctions>

## Description
This repository contains python scripts that define bidding agents that will participate in generalized second-price position auctions (GSP) and Vickrey-Clark-Groves auctions (VCG) for ad slots over a period of 24 hours with 30 minute slot intervals.

The agents designed can be constrained by a fixed budget, and in certain auctions reserve prices will be present. Agents will utilize several bidding strategies, including classic definitions of truthful bidding and balanced bidding.

## Files
* auction.py - Simulates sponsored search auction with either gsp or vcg implementation
* gsp.py - Implementation of GSP auction
* history.py - Gets an agent's bidding information from a previous round
* pjl14bb.py - Balanced bidding agent
* pjl14budget.py - Budget constrained bidding agent
* stats.py - Returns utility and revenue stats of a completed auction
* test_bb.py - Tests the bids of the balanced bidding agent
* test_gsp.py - Tests the GSP auction mechanism implementation
* test_vcg.py - Tests the VCG auction mechanism implementation
* truthful.py - Truthful bidding agent
* util.py - Utility functions used in the auctions
* vcg.py - Implementation of VCG auction

## References
Auction code provided as part of Harvard University CS186 course, David Parkes.
