# PAA_5_1
#Practical Assignment Module 5
  - Added Basic visualization diagrams on coupons.csv
    Refer https://github.com/lakshmip8217/PAA_5_1/blob/main/prompt.ipynb for all the visualizations
#Brief explanation of the each visualization updated in prompt.ipynb
  - Ref step [4] What proportion of the total observations chose to accept the coupon?
    Used pie chart to show portion of each accepted coupons based on the destination, this will give more clarify of the passenger preferences based on the destination
  - Ref step [5] Use a bar plot to visualize the coupon column.
    Bar plot shows the different types of coupons offered and usage of each of them by their frequency, to get acceptance rate based on type of the coupon.
  - Ref step [6] Use a histogram to visualize the temperature column.
    Temperatures between 75 to 80 are the timings, where coupons are effectively used by the drivers, than other timings given. This ensures that drivers first priority 
    to make use of the coupon offered is current weather conditions.
#Some of more general visualizations
  - Coupons usage by age and has_childern columns
    Box plot has been defined and data shows that Drivers age group without childern are accepting the coupons than the with kids. Also age group 21 and 26 are the ones
    accepting the coupons higher than other age groups.
  - A scatter plot on the passenger type and coupons accepted
    Each passenger is equally likely to accept the coupon irrespective of other constraints.
  - A bar plot on coupons used vs income
    Drivers with income of 25,000 to 37,499 are highly accepting toCoupon_GEQ5min, whereas toCoupon_GEQ15min & toCoupon_GEX25min are equal likely to accept the coupon irrespective of 
    the income range.
#Investigating Bar coupons
  - 1 created a bar_coupons_df with coupon type Bar
  - 2 What proportion of bar coupons were accepted?
      Pie chart shows that 59% of the bar coupons are accepted and remaining 41% are not used
  - 3 Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
      Bar plot on the passengers went to bar 3 or less times is higher than the passenger went to bar more than 3 times
  - 4 Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?
      Bar plot on the drivers went to bar more than once and are age of 25 are equally accepted the coupon with other age groups.
  - 5 Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than          farming, fishing, or forestry.
      Drivers of the given criteria are equally likely to accept the coupon
  - 6 Compare the acceptance rates between those drivers who:
        a) go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
        b) go to bars more than once a month and are under the age of 30 OR
        c) go to cheap restaurants more than 4 times a month and income is less than 50K.
      Assumption: RestaurantLessThan20 is considered as a cheap restaurant
        condition c does not have a matching records with given dataset, hence this group is not available in the bar plot.
        Bar plot on condition a and b are equally likely to accept the coupon.
  - 7 Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?
      Drivers who accepted the bar coupons are likely to exhibit behaviors and characteristics that align with being socially active and
      budget-conscious
#Independent Investigation
  - Created a bar plot on the passengers buying CarryAway food considering the age
     Assumptions: Passenger type alone is treated as a Driver
     Based on the above assumption, Drivers of age 21 is highly accepted the coupon where as passenger type partner is the lowest ones to redeem the coupons.
     
    
