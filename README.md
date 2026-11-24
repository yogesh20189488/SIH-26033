# Smart India Hackathon Workshop
# Date: 24/11/2026
## Reference Number: 26018320
## Name: YOGESH BALA GURU

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: 
1. Create a digital marketplace that:

     •      Connects farmers/FPOs directly with consumers and bulk buyers.
   
     •      Provides logistics support.
   
     •      Uses AI for demand forecasting and route optimization.

2. Benefits:

     •      Better prices for farmers.
   
     •      Lower prices for consumers.
   
     •      Reduced supply chain inefficiencies.

## Proposed Solution
1. Detailed explanation of the proposed solution.

   FarmDirect is a mobile and web marketplace that connects farmers and Farmer Producer Organizations (FPOs) directly with consumers, hotels and bulk buyers.

     •	  Farmers and FPOs list their produce with quantity, quality grade, price and available dates. Listing is possible by voice in regional languages (for example Tamil and Hindi) so that farmers with limited literacy can use it.

     • 	  Buyers browse by location and freshness, place single or bulk orders, and pay through UPI or other digital payment.

     •	  Logistics support is built in. Produce is collected at a village or FPO hub, and the platform arranges transport and delivery.

     •	  An AI engine forecasts demand and suggests a fair price band, and a route optimizer plans pickups and deliveries.

3. How it addresses the problem

     •	  The marketplace removes the middle layers (commission agents, multiple traders) between the farm and the buyer, so the farmer keeps a larger share and the buyer pays less.

     •	  A price-breakup screen shows how every order is split between the farmer, logistics and the platform fee, so the farmer’s share is visible.

     •	  Demand forecasting tells farmers what and how much buyers are likely to order, which reduces unsold stock and wastage.

     •	  Pooled route optimization combines orders from nearby farmers into shared trips, so small farmers can afford delivery.

4. Innovation and uniqueness of the solution

     •	  Price transparency: a visible breakup of farmer share, logistics cost and platform fee for every order.

     •	  Demand-led selling: AI forecasting that guides farmers before harvest, rather than only listing what is already harvested.

     •	  Pooled logistics: shared pickups and deliveries that make small loads affordable.

     •	  Inclusive access: voice listing and regional languages, with FPO help agents for farmers who need support.


## Technical Approach

<img width="761" height="392" alt="Screenshot 2026-11-23 111117" src="https://github.com/user-attachments/assets/716ca69b-44c7-4678-bd50-97e1d2609444" />

Diagram:
<img width="5100" height="2820" alt="FarmDirect_technical_architecture" src="https://github.com/user-attachments/assets/a1e103b9-c736-4daf-aa3a-275e8d4cc375" />


3. Methodology and process for implementation


   <img width="6440" height="1240" alt="FarmDirect_flowchart" src="https://github.com/user-attachments/assets/fc59fe3c-a94a-4040-983c-1fcb89569904" />

    Figure 1. Process flow of FarmDirect
   
    1.	Onboarding: farmers and FPOs register and list produce with quantity, grade, price and photos.
  
    2.	Ordering: consumers and bulk buyers browse, order and pay. The payment is held until delivery is confirmed.
   
    3.	AI engine: past orders, season and festival demand and mandi prices feed a forecasting model. It suggests a fair price band and expected demand.
  
    4.	Route optimization: orders in the same area are grouped, and OR-Tools plans the pickup and delivery routes for the vehicles.
   
    5.	Delivery and payout: the buyer confirms delivery and the farmer receives the payout through UPI.
   
    6.	Prototype scope: a working prototype with farmer listing, buyer ordering, the price-breakup screen and a route map for one area.


## Feasibility and Viability
1. Analysis of the feasibility of the idea

     •	  Technical: every component uses open-source tools or widely available APIs, so the system can be built by a small student team.

     •	  Operational: FPOs already exist and can onboard farmers in groups, which reduces the effort of reaching individual farmers.

     •	  Financial: a pilot in a single district keeps the starting cost low. Revenue can come from a small platform fee on each order.


2. Potential challenges and risks

     •	  Low adoption among farmers because of limited digital skills.

     •	  Freshness and quality of produce during transport.

     •	  Buyer trust and payment delays.

     •	  Little order data at the start, which weakens the forecasting.


3. Strategies for overcoming these challenges

     •	  Voice listing, regional languages and FPO help agents for farmers.

     •	  Photo-based grading, ratings and short delivery routes to protect quality.

     •	  Payment held until delivery is confirmed, so both sides are protected.

     •	  Start with seasonal averages and public price data, and improve the model as real 


## Impact and Benefits
1. Potential impact on the target audience

     •     Farmers and FPOs: direct access to buyers and a visible, fair share of the price.

     •	  Consumers: fresher produce at lower prices.

     •	  Hotels and bulk buyers: a reliable, traceable source with predictable supply.


3. Benefits of the solution

     •	  Social: gives small farmers market access and brings rural producers into digital trade.

     •	  Economic: better prices for farmers, lower prices for consumers and fewer supply chain inefficiencies.

     •	  Environmental: forecasting reduces unsold and wasted produce, and pooled routes reduce vehicle trips and fuel use.



## Research and References

1. Details / Links of the reference and research work

     •	Agmarknet (mandi price data): https://agmarknet.gov.in

     •	e-NAM, National Agriculture Market: https://enam.gov.in

     •	ONDC, Open Network for Digital Commerce: https://ondc.org

     •	Google OR-Tools, vehicle routing: https://developers.google.com/optimization/routing

     •	Prophet, time-series forecasting: https://facebook.github.io/prophet
  
     •	Smart India Hackathon: https://sih.gov.in
