

# *How to Sell Vintage Clothing with Generative Matchmaking*

The vintage clothing market suffers from a large gap between supply and demand, especially with respect to quality *men's* clothing as we explain below. 

Our goal is to sell items and find buyers. Basically serve as matchmaker for clothing items and buyers. 
We have an idea here, born from experience in my own personal search for quality used men's clothing. 
There is large market of vintage sellers, who mainly focus on women's clothing. 
We experienced many shops in Calgary, specifically, which did not have any men's selection. So here is opportunity. 
In our opinion a distinct strategy needs be provided or attempted to expand their markets to male buyers.

Here is the outline:

Again the vintage clothing market has gaps between supply and demand, namely the supply of quality used clothing acquired by the vintage sellers and the demand of the buyers market. 

In this memo we are specifically interested in *male buyers*. Here specifically the gap is largest. The popular idiom is that "men hate shopping". 

And yes, they do. But why? There is a psychological element here which we examine. Basically men are mission oriented and very judgemental. 

They do not want to waste their time searching through random racks for items that may or may not be there, which may or may not fit, at this or that price, etc.. 

Other people find this part of vintage hunting fun, but our working assumption is that the majority of men do not enjoy this. This makes for barrier between male buyers and the vintage stores. 

Our goal is to be matchmakers, and connect the market. Men *want* to look good, and vintage shops are *able* to make them look good. This is our objective.

Men are judgemental and mission oriented. So they want to immediately be catered to. In and out. A client shows up, with a profile, with some portfolio for their style, and you have to generate matchings for them from the available stockpile supply. 

*Basically you have to know what the client wants before they show up!* 

And here enters the opportunity for a generative model.

# Statement of Problem

In the vintage problem we want to construct and generate the utility or preference pairings $b(x,y)$ between item $x$ and buyer $y$. I.e., we look to predict whether the buyer will be hot or cold towards the item. Will the client have a disposition, with some probability reflected in $b(x,y)$, to trade scarce resources for the item?
Basically the vintage seller has a supply $X$, which is not well known and very opaque to the buyers $Y$. A buyer $y$ walks into the store, they have a null feeling to mostly everything except they react to the mannequins, etc.. The buyer has no sense of the client's preferences. The buyer did not even know this buyer exists before they physically walk into the store.


The standard model for vintage storefront is: you have random clothes in racks, you expect buyers to show up on location, search through the racks, identify an item which appeals to them which they are willing to purchase at the market price. There appears to us many potential "points of failure" in the chain of sale.

We think that men specifically want a customized mannequin, they want the vintage store to dress the mannequin completely in outfits and ensembles which appeal to the preferences of the buyer. Is it too much to ask?


Instagram is filled with girls who pick and sell vintage clothing. Here "vintage" could mean a premium literally "vintage" limited edition shirt, or vintage could mean a quality used clothing item which typically is not in production anymore. These sellers have a large supply of clothing, i.e. large stockpile. They pick from huge random bins alongside other pickers, and it's not at all clear what's going to sell. And who are they picking for?

This is a direct question to ask: do vintage stores pick clothes with the *hope* that the item is going to sell, with the hope that the right person is going to walk through the door and fall in love with it? We can do better.

# Abstract Formulation

We are given measures $\sigma, \tau$ on the supply $X$ and buyers $Y$, respectively. This means we don't have precise pointwise knowledge about $X,Y$, but rather measurable ("probabilistic") information.

We assume/postulate/hypothesize the existence of a reasonable stable preference pairing $$b: X\times Y \to \bf{R}.$$ This measures the "temperature" $b(x,y)$ of a buyer $y$ towards an item $x$. Naively we want to maximize the temperature, and emphasize (i.e. market, target, upsell) those items which make the client "warm". 

But the challenge is to generate this temperature, and to know the temperature with some confidence before the buyer walks into the store and sees the item! The problem here is *generating the preference function* given *new* supply (new finds $x$) and *new* buyers. 

# Parameters
Here enters the quantitative part and this is more difficult. 
*What are the relevant numerical statistics in the vintage problem?*








