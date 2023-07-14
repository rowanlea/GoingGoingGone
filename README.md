# Going Going Gone
An architecture kata based off of the popular Neal Ford one.

## Scenario
An auction company wants to take their auctions online to a nationwide scale - customers choose the auction to participate in, wait until the auction begins, and then bid as if they were there in the room with the auctioneer.

## Users
worldwide bidders, that will scale up to hundreds of participants (per auction), potentially up to thousands of participants, and as many simultaneous auctions as possible
administrators controlling accounts and auction listings

## Requirements
- Auctions must be categorised and 'discoverable'
- Auctions must be as real-time as possible
- Auctions must be mixed live and online
- Video stream of the action after the fact
- Handle money exchange
- Participants must be tracked via a reputation index

## Constraints / Additional Context
- Auction company has no existing electronic system, they have somehow got by with paper records until now
- Auction company is expanding aggressively by merging with smaller competitors
- If nationwide auction is a success, replicate the model overseas
- Budget is not constrained - they will pay any amount for the best solution
- Company just exited a lawsuit where they settled a suit alleging fraud, and want to be able to track suspicious remote bidders
- They would like to be able to identify the most active bidders in order to offer them exclusives

## Facilitator Notes
The above requirements are deliberately not complete, to reflect the real-world scenario where we often need to ask customers questions to elicit further information or requirements. The below are important notes than can be shared with the groups, as and when they ask:
- They lost the lawsuit because they couldn’t provide evidence they hadn’t done what was claimed against them
- They have 1 building each in 50 different countries they would like to expand to in the future
- Each bought-out competitor doesn’t necessarily use the same tech stack
- Each bought-out competitor should aim to implement this technology
- There is no requirement to catalogue any historical auction data

