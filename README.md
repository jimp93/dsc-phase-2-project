## Project Overview

We are producing a new game show -- 'Flip' -- in which a group of contestants and a group of experts working for the show are both given a lump sum to buy a house to buy in King County, WA. Both teams then sell their house, and if the contestants make more profit than the experts, then they get to keep the money from the house sale. <br>

It is obviously in our best interest to minimise the chance of this happening. To this end, we analyze two years of housing sales from the county to generate a model showing how various features of a house are correlated to its sale price. <br>

We can then use his model to find the most undervalued houses on the market and maximise the chances of winning the contest. <br>

The inferential model revealed that being by the waterfront and the grade of the house multipled by the sqft of living space gave the biggest boost to prices. <br>

Location was also found to be a key factor, with the popularity of Medina, Clyde Hill, Capitol Hill and Queen Anne all giving houses in the area a higher valuation. <br>

The average prediction from the model is about 15 percent out, which means we can be confident of finding underpriced houses. Being wrong occassionally is acceptable as we need to lose the contest from time to time in order to keep the show interesting and win the ratings war.

<img src="images/logo.png" style="width: 700px;"/>

<br>
<br>

### Business Problem

To attract high ratings with an entertaining show that strikes a good balance between difficulty and achievability. <br>

This relies upon the expert team winnnig most of the time. <br>

We also need to make sure we stack the odds in out favour in order not to keep having to pay out the big prize.

<img src="images/Seattle.jpg" style="width: 700px;"/>
<br>
<br>

### The Data

Data drawn from the dataset of house sales in King County, WA, for 2014 and 2015.

<br>
<br>

### Methods

The dataset of almost 25,000 sales was analyzed to find the strength of relationships between features of a house and its achieved sale price. <br>

The end goal was to create an accurate model, using the features most related to the price, and which boosted them the most. <br>

To do this, we created a series of models, each with gradually fewer features as we got rid of those that were either irrelevant to the task, or which had little effect on price.

Each model was then put to the test with previously unseen data, and its perfomance calculated in terms of how accurately it could account for the actual price. <br>

In order to investigate the link between a house's location and its sale price, we added the city that the house's zipcode is registered to, or neighbourhood in the case of Seattle, as a new feature. <br>

<img src="images/seattle_heat.png" style="width: 700px;"/>
<br>
<br>

### Headline Results
<br>

The inferential model revealed that being by the waterfront and the grade of the house multipled by the sqft of living space gave the biggest boost to prices. <br>

Location was also found to be a key factor, with the popularity of Medina, Clyde Hill, Capitol Hill and Queen Anne all giving houses in the area a higher valuation. <br>

*  **the grade of the house multipled by the sqft of living space is the most common factor that gives the biggest boost to prices**

<img src="images/worldwide_bo.png" style="width: 700px;"/>

<br>
<br>

* **Location was also found to be a key factor, with the popularity of Medina, Clyde Hill, Capitol Hill and Queen Anne all giving houses in the area a higher sale price**
<br>

<img src="images/profit_v_genre.png" style="width: 700px;"/>
<br>
<br>

* **Being by the water increases the value of a house more than any other factor, but it is quite a rare feature so will only occassionally be relevant**
<br>

<img src="images/profit_v_genre.png" style="width: 700px;"/>
<br>
<br>

* **The number of bedrooms and bathrooms is less important than the size of the living space**
<br>

<img src="images/adventure_budget_pl_sub_scatter.png" style="width: 700px;"/>
<br>
<br>



### Conclusion

This analysis leads to three recommendations for the show's producers to maximise the odds of winning each week, while keeping the show competitive enough to attract viewers

**Location, Location, Location** 

* The expert's should look for underpriced properties in , , and 

**Big is beautiful**

* Bigger properties add onto the sale value, and a large space combined with a high grade is rocket fuel for prices. Don't be distracted by bathrooms and bedrooms

**Pacific views**

* The most desirable feature is a waterfront property, but their rarity means finding such a bargain will not be the main weekly consideration


### Next steps

*  Keep collecting data on latest sale prices as we need to be ahead of the game in discerning shifts in trends, and in knowing which places are hot, and which are not
 

