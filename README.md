# Conversion-Rate-Challenge
The goal of this challenge is to build a model that predicts conversion rate and, based on the model, come up with ideas to improve revenue.

# Challenge Description
We have data about users who hit our site: whether they converted or not as well as some of their characteristics such as their country, the marketing channel, their age, whether they are repeat users and the number of pages visited during that session (as a proxy for site
activity/time spent on site).

Your project is to:
Predict conversion rate
Come up with recommendations for the product team and the marketing team to improve conversion rate.

Columns:
1. country : user country based on the IP address
2. age : user age. Self-reported at sign-in step
3. new_user : whether the user created the account during this session or had already an
4. account and simply came back to the site
5. source : marketing channel source
6. Ads: came to the site by clicking on an advertisement
7. Seo: came to the site by clicking on search results
8. Direct: came to the site by directly typing the URL on the browser
9. total_pages_visited: number of total pages visited during the session. This is a proxy for
10. time spent on site and engagement during the session.
11. converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything.

The company goal is to increase conversion rate: # conversions/ total sessions.
