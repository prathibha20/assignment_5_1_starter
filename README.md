My findings are as follows:

Some data in the dataset needed cleaning, such columns: coupon, bar, age, income. Some columns held data type of 'object' instead of string or int. These have been updated respectively.
We made observations of columns that contained NaN values and made note of this for later when working with the datasets.
I decided that we cannot drop the rows where there are some NaN values, as the row may contain some other pertinent data. Instead, when we run our searches, we can simply excluded NaN values based on our search criteria.
We made observations of what proportion of the total observations chose to accept the coupon
We used a bar plot to visual the coupon column:


Via our beautiful plot, here we can see how many coupons were used for each type. The visualization is very easy on the eye!

Next we used a histogram to visualize the temperature column:



Via our beautiful plot, here we can see the count(occurences) of temperatures when users were surveyed for coupon usage! Very easily to gain insight from the plot, and we can see that the largest aggregate is among where temperatures was equal to or greater than 80 degrees.

Next we took a look at the use of Bar coupons. This was very exciting

We created a new dataframe specificially related to coupon type of "Bar"

We then gathered numbers and made calculations of proportions of where bar coupons were accepted by patrons. This number was 827 (41.001%)

We then made a comparison of the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.

The results here were insightful:

The total acceptance of of those who went to a bar 3 or fewer times in a month was 666

The total acceptance of of those who went to a bar more times in a month was 153

The percentage of people who accepted, and went to the bar 3 or fewer times was 81.31868131868131 %

Next we looked to compare teh acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to all others.

After calculations, we found that:

The acceptance rate of those who go to a bar more than once a month and are over the age of 25 is 70.46979865771812 %

The acceptance rate of those who go to a bar more than once a month and are under the age of 25 is 29.53020134228188 %

Yes there is a difference. A very large difference!!

We then went on to use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.

After calculations, we have found:

The acceptance rate between drives who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry was: 71.32486388384754 %

Those who did not accept was: 28.67513611615245 %

We then went to compare the acceptance rates between those passengers who:

go to bars more than once a month, had passengers that were not a kid, and were not widowed OR

go to bars more than once a month and are under the age of 30 OR

go to cheap restaurants more than 4 times a month and income is less than 50K.

After calculations we found:

The acceptance rate of those who go to bars more than once a month and had passengers that were not a kid and were not widowed was: 71.32486388384754 %
The acceptance rate of those who go to bars more than once a month and under the age of 30 is: 72.17391304347827 %
The acceptance rate of those who go to cheap restaurants more than 4x per month and have an income less than 50k is: 60.07020623080298 %
We then went to draw a hypothesis abotu passengers who accepted teh bar coupons. And based on these observations, I hypothesize that passengers who accepted the bar coupons: were not widowed; are likely to go to the bar if they are passengers under 30 and do not have kids; are typically male; typically go when the weather is sunny.

Next I had an opportunity to draw an independent investigation. In this round I chose to focus on "Coffee House" coupon category, as we saw earlier that this was our #1 used coupon over all offerings and acceptances of coupons! I was eager to gain some insights here.

I first wanted to look at where folks were headed when those chose to redeem the coupons. I chose a bar plot to gain insights into this and the results are compelling.



Here we have quickly found that users were headed to no urgent place. This was interesting. It lead me wonder about who is buying coffee and redeeming coupons, what occupations do they hold, marital status, etc.
Thus, I wanted to gain insights into gender and marital status so I drew up another plot to take a look at this and gain insights into whether it was more males or females redeeming the coupons and are they unmarried w/ partner, single, married, divorced, or widowed. Lets take a look at the plot and gain insights:


From our plot, we can see that overall, females purchased more coffee than males. And in our female group, most were married. Very interesting
I also decided to have a look at Redemption by gender and occupation. I was particularly interested in finding what occupations of people where amongst our most active group of users who redeemed coffee house coupons. The results are compelling:


From our beautiful plot, we can see that the highest number of redeemers of the coupon were Students, the unemployed, and computer and mathematical. We also see that the highest group, students, Males redeemed more coupons than females. The acceptance rate here was 63.46% !
# assignment_5_1_starter
