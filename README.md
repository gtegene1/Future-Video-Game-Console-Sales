# Future-Video-Game-Console-Sales
Using past console sales data, we will attempt to use machine learning to predict how much this current generation console will sell and predict how much the next console (iteration) will sell on release date.

Executives, when deciding the release date of a new console, want to know how many consoles are going to sell the first day/week/month.  Video game consoles are historically sold at a slight loss to the company. To make the loss back, accessories, online additives, and games are sold at a slight premium to offset it. If they know a console is being released, they want to time the accessory release, new games and online additions properly as well.

Using machine learning, and outside information we will estimate the following: how much will the PS5 sell throughout the rest of its lifecycle. The PS5 is estimated to be approximately 70% done with its current lifecycle, as rumors of its successor, the PS6 is in development at Sony.  

We want to use the PS1, PS2, PS3, PS4, and PS5 sales at release until they are discontinued to estimate the PS6 sales during its lifetime.  To do this, we must make some assumptions and establish parameters, as things have changed during each console’s sales lifecycle.

Each console has had a newer, slim model drop about halfway through its lifecycle.  This also in turns lead to a slight price drop, usually before the holidays. Noting this, sales will increase.

The PS3 will skew the machine learning process negatively, as the PS3 came out just before the housing market crash and recession, at a whopping $500 in 2007, noting that people will have less money to spend during a recession on entertainment.

Both the PS4 and PS5 have had pro models, a half step up in game performance, release about 3-4 years after the initial console dropped. Around this time, the base model usually gets a slight discount, and the premium model will be slightly more expensive than the original MSRP of the console at launch. For this project, we will lump in both base model and Pro models into sales figures monthly, but further research can be done to highlight if the Pro models sell well, and if they cannibalize the base model sales.

The PS5 also had supply chain issues during COVID when it was released, so while sales data is high, we can expect some delay in the first couple of months to a couple of years regarding sales amount.

Another important thing to note. Each console was released in tandem with new games specifically designed to attract customer, called launch titles. We are assuming that the PS6 will launch with 20 launch titles, as each system previously was released with at least 12.

<ins> ###Reasons for machine learning 
Using basic mathematical models like linear regressions, polynomial regressions and even multiple regression models in realistic scenarios such as game console sales would not work for this case.

Video game consoles, video games in general, face heavy competition within the industry and outside. Within, premium video games, that cost, compete with freemium games. Outside, video games compete with all forms of entertainment: movies, music, tv shows, reading, anything one can do in their free time is a substitute. 

Knowing this, accurate console sales at launch and throughout its lifecycle, needs to consider the average person’s other interests, time, and money. Like highlighted earlier, the reason the PS3 did not do well was partially due to the recession 1 year after launch, but also the high price and lack of first party games, ‘system sellers. 

