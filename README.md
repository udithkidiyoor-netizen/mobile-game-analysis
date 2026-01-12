# mobile-game-analysis

### Problem Statement
* How does player engagement influence in-game purchases?
* Which behavioral signals indicate monetization opportunities?
* Can early engagement predict purchase likelihood?

### Dataset Characteristics
* Demographics (Age, Gender, Country, Device)
* Gameplay metrics (Session Count, Average Session Length)
* Monetization data (In-App Purchase Amount, Spending Segment)
* Purchase timing (First Purchase Days After Install)

### Analysis
* Players with high engagement tend to be high spenders, but high engagement does not mean high spending and the scatterplot proves it so...

   Feature	Coefficient
  6	EarlyPurchase	2.497700
  5	TotalEngagement	0.510127
  1	Gender	0.189766
  0	Age	-0.089529
  2	Device	-0.132441
  3	SessionCount	-0.338769
  4	AverageSessionLength	-0.443278

* Early spenders signal higer average spending.
