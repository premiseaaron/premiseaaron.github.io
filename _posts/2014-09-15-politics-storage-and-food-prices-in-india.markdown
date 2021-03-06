---
layout: post
title:  "Politics, Storage, and Food Prices in India"
date:   2014-09-15
cover_image: ../images/img/98sef9ef8.jpg
categories: Data Science

author:
  name: Nicholai Lidow
  bio: Data Science
  twitter: nlidow
  image: nicholai.jpg

---

India’s monsoon season, crucial for the nation’s agricultural production, got off to the weakest start in five years this season. The Ministry of Agriculture reported that during the first half of June, cumulative rainfall for India was 45% below average. Here at Premise, we’ve been keeping an eye on food prices throughout the country. As it turns out, the prices tell a much more interesting story than just drought. The prices reflect the nuances of India’s politics, as well as the shortcomings of its food storage infrastructure.

The delayed monsoon had severe effects on agriculture throughout India, with the most dramatic effects in the grain producing regions in northern and central India. Figure 1 shows the progression of the drought over the past six months using a satellite-derived measure of crop stress called evapotranspiration anomaly, or ETa for short. The “ETa Anomaly” compares the current ETa level with the historical average. Darker shades of red indicate more stress on the local crops due to drought, while green indicates greater water availability. Grey indicates historically normal levels.

Figure 1. The spread of drought in India
![Figure 1. The spread of drought in India](/images/img/sfs4rsts4r4s.jpg)



Between the beginning of March and the end of August, food prices in India rose about 10% according to our overall food price index (see Figure 2). These price changes broadly correspond to the onset of drought: prices rose steadily until early August, and then began falling soon after the delayed arrival of the monsoon. But the overall trend in food prices masks a more complicated dynamic. For example, Figure 2 shows that the prices for vegetables rose 30% over this time period, while the prices of grains such as rice rose only 10%, in line with the overall index. 

Figure 2. Rising prices in India
![Figure 2. Rising prices in India](/images/img/s4rs4t.png)

The relative stability of grains prices is puzzling, since the grain-producing regions were the hardest hit by the drought. Indian politics, however, offers an explanation. At the onset of the crisis, Prime Minister Narendra Modi [announced a program to stabilize grains prices](http://www.bloomberg.com/news/2014-06-25/crop-sowing-delayed-by-weak-india-monsoon-stoking-prices.html)  by offloading 5 million tonnes of rice, about a quarter of the country’s strategic stockpiles, and cracking down on food hoarders. This policy succeeded in keeping the price of vital grains in line with overall inflation. Vegetables, however, are too perishable to be stockpiled, and prices reacted strongly to the intensifying drought.


The picture becomes more interesting when we look at how food prices vary across India’s major cities. Figure 3 looks at the average ETa Anomaly value within 400km of three of India’s cities. Chennai, in India’s southeast was hit early and hard by the drought. Mumbai in the west and Kolkata in the east each experienced a later onset but more severe change in their ETa levels.

Figure 3. Drought in three Indian cities
![Figure 3. Drought in three Indian cities](/images/img/s4te5ut6.png)

Based on these patterns of drought, we would expect prices of vegetables to be steadily high in Chennai and rise sharply in Kolkata and Mumbai as the drought intensified through July. But, as shown in Figure 4, vegetable prices spiked most dramatically in Kolkata, even though the city did not experience as prolonged a drought as Chennai, nor as steep of a decline as Mumbai. By August, consumers in Kolkata were paying two-and-a-half times as much for produce as they did four months prior.

Figure 4. Vegetable prices in three Indian cities
![Figure 4. Vegetable prices in three Indian cities](/images/img/46yrhw.png)

Why did prices for vegetables rise so dramatically in Kolkata, despite the relatively moderate drought? For this answer, we have to look beyond electoral politics and consider India’s food storage infrastructure. An estimated 30% of India’s produce is rendered unfit for consumption due to spoilage after harvesting. The poorest storage infrastructure--and the highest post-harvest losses in the country--is in West Bengal, where Kolkata is located. [The state loses approximately $2.2 billion](http://articles.economictimes.indiatimes.com/2013-08-06/news/41131971_1_2-lakh-crore-cold-storage-rs-10) (Rs.13,600 crore) worth of produce each year. As our data show, people in Kolkata suffered twice the price increases than their compatriots in Mumbai or Chennai, both located in areas with superior storage infrastructure. Although state-driven price stabilization policies offer some short-term relief, ultimately India will have to upgrade its storage and transportation infrastructure if it hopes to improve the food security of its citizen


