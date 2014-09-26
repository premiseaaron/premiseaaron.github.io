---
layout: post
title:  "Introducing Premise’s Coca-Cola Index"
date:   2014-09-18
cover_image: ../images/img/98sef9ef8.jpg
categories: Data Science

author:
  name: Allen Tran
  bio: Data Science
  twitter: nlidow
  image: allen.jpg

---

From Chennai to Rio, New York to Shanghai, Coca-Cola is one of the most ubiquitous goods in the world. Whether in the old school glass bottle, a plastic liter or an aluminum can, Coke can be found on nearly every shelf in every store across the globe. What’s more, though, is that Coke also happens to be an eerily accurate bellwether for what’s happening in a country’s economy, which is why Premise is introducing the Coca-Cola Index.

For years, The Economist has published its “Big Mac Index,” which uses the price of Big Macs across countries to offer rudimentary medium-to-long term forecasts of FX rates. Countries where Big Macs are relatively expensive are said to have currencies that are overvalued. Residents living in countries where Big Macs are expensive will import Big Macs from a cheaper country, driving down the value of their domestic currency.  Hence overvaluations should predict subsequent depreciations, along with the reverse scenario.

Unlike Big Macs, Coke is tradeable and consumed across a much wider range of income groups, making it a better match to the underlying theory. Moreover, the price of Coke is better at capturing broader price pressures as Coke retailers have greater flexibility in pricing.

To construct the index, we used data and observations of Coke available for purchase in stores in the US, China, Argentina and Brazil. Since Coke comes in a variety of sizes and shapes, we adjusted each observed price for bulk discounts and package type so that the data reflects prices of 1.5 liter bottles of Coca-Cola. (FYI, you save 33% on average if you purchase a Coca-Cola product twice the volume.) 

Figure 1: Price of Coca-Cola (1.25L) in USD
![Figure 1: Price of Coca-Cola (1.25L) in USD](/images/img/xxx.jpg)

Two things stand out: first, the price in China is absurdly cheap, roughly half the price compared to the US and Brazil. Second, the price in Argentina was much higher than in the US but rapidly fell during the first quarter of 2014.  The rapid fall is consistent with the start of the price accord in Argentina which froze the price of 1.5 liter bottles of Coke in major supermarkets to 12.50 Argentinian Pesos ($1.57 in USD).  Interestingly, this freeze appears effective only for a couple of months with continuing inflation in Coca-Cola products of other non price controlled sizes.  Prices in Brazil were much more stable, although prices begin an upward trend that coincides with the beginning of the 2014 World Cup.

Like the Big Mac, the price of Coke sold in a supermarket reflects the cost of a wide range of inputs: sugar, rent, manufacturing labor and the labor of retail workers. If we assume that the price of Coke is broadly representative of the price level, then we can infer likely movements of exchange rates. Countries with a relatively high price level will try to import goods from other countries with cheaper goods, weakening the domestic exchange rate.

Figure 3: Implied valuations of FX rates
![Figure 3: Implied valuations of FX rates](/images/img/xxx.jpg)

The implied valuation of the Chinese Renminbi (RMB) is consistent with the US Treasury’s [statement](http://www.treasury.gov/resource-center/international/exchange-rate-policies/Documents/2013-10-30_FULL%20FX%20REPORT_FINAL.pdf) that the RMB is “significantly undervalued.”  China is unique among the countries here as their exchange rate is more or less fixed, implying that the undervaluation will not resolve itself naturally via market forces.  Regardless, the consistent 50% undervaluation illustrates the extent to which the RMB would appreciate under a floating regime. 

Relative to the RMB, the Argentine Peso (ARS) and the Brazilian Real (BRL) are much closer to a fair valuation.  The price accord in Argentina appeared to be successful in lowering the price level of some goods and the associated overvaluation of the ARS.  However, the price accords were a one-time level shift, with persistent high inflation continuing to drive the overvaluation of the ARS.  This overvaluation is consistent with market expectations of further depreciation in the ARS. 

The BRL looks relatively stable although there is a clear run up in prices and overvaluation in the BRL which coincides with the months prior to the 2014 World Cup.  Interestingly, Coca-Cola prices (and likely broader price pressures) remained high even after the World Cup, evidence of price stickiness. 
