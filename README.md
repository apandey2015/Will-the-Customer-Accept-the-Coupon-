# Will-the-Customer-Accept-the-Coupon-
The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.
Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Overview

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).


Findings

Investigating the Bar Coupons

 ![cat](https://github.com/user-attachments/assets/37df82fb-6661-4354-87b4-d7c9e46c89ae)
 ![cat2](https://github.com/user-attachments/assets/db415270-ee0d-41a9-873c-6d9f98666b04)

# Majority of drivers who went to the bar went alone. Drivers with kids visited the bar the least.
# Around 41% of the bar coupons were accepted compared to the 56% of the total coupons accepted.
# 76% of the drivers accepted the coupons who go to the bar more than 4 times a month compared to acceptance rate of 37% for those who went to a bar 3 or fewer times a month 
# Acceptance rate of drivers who go to a bar more than once a month and are over the age of 25 is around 70%, which is very similar to the acceptance rate of drivers who go to a bar more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry, which is around 71%

 

Investigation Coffee House coupons
 
# Majority of drivers who went to the bar went alone. Drivers with kids visited the bar the least.
# Drivers who went to a coffee house 3 or fewer times a month and who went to a coffee house 4 or more times a month accepted the coupons around 50%
# The acceptance rate of coupons for both genders is around 50%

Next steps and recommendations:

Time of the day and acceptance of coupons can be anlayzed to identify if drivers accept the coupons at a certain time of the day.
Restaurant types and time of the day can be combined to check the acceptance of the coupons.
Income group and the acceptance of coupons can be analyzed.
All the above can help identify the ideal conditions to push the coupons for maximum acceptance.

https://github.com/apandey2015/Will-the-Customer-Accept-the-Coupon-/blob/main/Will%20a%20Customer%20Accept%20the%20Coupon.ipynb
