# Case Study - Fintech Bootcamp

## Overview and Origin

Stripe, Inc incorporated in 2010 and was founded by teenage entrepreneurs John and Patrick Collison - Irish-born brothers who dropped out of Harvard and MIT to fix payments on the internet.  The brothers showed early signs of entreprenueral stardom selling their first business in 2008, Auctomatic, at the ages of 17 and 19 making them millionaires over night.  Eight years later in 2016 - after Stripe's valuation of $9.2 billion, John and Patrick became the world's youngest billionaires. [^note]  The idea came about in 2010 out of the founder's personal experience of the difficulty in setting up e-commerce websites on their own projects.  

> *“Stripe really did come about because we were really appalled by how hard it was to charge for things online.”* — John Collison

The brothers found it a worthy challenge and over the course of two weeks prototyped a solution that processed their first credit card transaction.  Being avid developers themselves - they beta tested their solution with the developer community and made quick iterations that grew in popularity as a "developer friendly" option for businesses to start receiving online payments immediately.  Their product was a welcomed contrast to having to wait in some instances days or weeks for merchant account approval if given at all.
    
The simple goal was to make it as easy as possible to implement and the earliest versions of Stripe's setup only required the following 7 lines of code being added to a business checkout page to start receiving online payments.

**Stripe's Sample Checkout Code**   
```
<form action="/purchase" method="POST">
<script
    src="https://checkout.stripe.com/checkout.js"
    class="stripe-button"
    data-key="pk_test_TYooMQauvdEDq54NiTphI7jx"
    data-name="Custom t-shirt"
    data-description="Your custom designed t-shirt"
    data-amount="{{ORDER_AMOUNT}}"
    data-currency="usd">
</script>
</form>
```
The brothers saw a massive opportunity with obvious hurdles.

    > *As we built Auctomatic, we interacted with dozens of small and medium-sized business, and we learned how hard it was to accept payments as an online business.  People would apply for a merchant account, and it required heaps of paperwork and an elaborate approval process.  Many business were rejected because they didn't have a history of receipts -- but how were they supposed to have a business history if they couldn't get a merchant account?  And even if they could get a merchant account, they got one product - the ability to accept credit card payments in a single transaction.  This didn't allow for recurrring payments, marketplaces, or other complex types of transactions.    Nor did it allow businesses to capture data associated with their transactions.  This system didn't make sense.  People could build services and products that reached people around the world through the Internet, yet they couldn't get paid.  It got us thinking that there had to be a better way of doing things.* - John Collison

Stripe finished Series G Funding as of April 2020.  They have currently raised $1.6 billion from lead VC firms like Sequioia Capital, General Catalist, Tiger Global Management and DST Global.  As of 2020 - Stripe's latest valuation of $35 billion makes it the most valuable private fintech in the U.S.


## Business Activities:

Stripe's mission is "to increase the GDP of the internet" by creating a suite of APIs that give businesses of every size the ability to accept payments and manage their business online. They are focused on the economic infrastructure for the internet by providing a range of flexible tools for businesses to customize their payment processes.

Prior to Stripe - business online was no small challenge having to navigate the financial system of setting up merchant accounts, currency challenges for international transactions and setting up complex transactions like recurring payments.    Stripe's services helped customers bypass these hurdles which allowed them to focus on growing their businesses and not the technical quirks of taking payments online.

What started out with the idea of simplifying payment setup for the internet has now morphed into a mission of impacting economic growth around the world.  That now includes products like Stripe Connect for social commerce and online marketplaces as we see with Shopify, and more recently the creation of Atlas which helps international businesses quickly create a valid legal presence in the United States with tax ids and bank accounts broadening their reach.  Stripe sees itself as the champion for frictionless trade across boarders.

A quick background on the lifecycle of a credit card transaction for context.  

### Steps to CC Transaction

- 1.  Merchant contracts with payment gateway
- 2.  Payment gateway receives the transaction request and submits it to the merchant bank's processor using a secure site connection
- 3.  Merchang bank's processor sends the transaction to the CC network who then forwards the transaction reques to the issuing bank for the customer's credit card.
- 4.  Issuing bank then accepts or refuses teh transaction based on the transaction and customer's available funds and sends the results back to the credit card network.  
- 5.  Credit card network  transmits the results to the merchant bank's processor which then sends the results to the payment gateway.  
- 6.  The results of trans were saved and available to the merchant and customer.  If trans was approved the customer's credi-card issung bank would send funds to the CC network, which then sends funds to the merchant's bank.  Round trip process taking < 3 seconds with funds being available to the merchant within two to four business days.





handle billions of dollars worth of transactions annually. 

It supports a range of development languages, including Ruby, Python, PHP and Java. 

Furthermore, Stripe supports more than a hundred currencies, and offers features such as mobile payments, 
subscription billing and one-click checkout. Users also get access to a dashboard where they can visualize transactions. 
Clearly, then, this is a feature-rich payment gateway, although Stripe does demand a lot more technological knowledge from the user than most providers.

Stripe offers a particular advantage to merchants based in Europe, as card processing fees for European cards are 1.4% + 20p per transaction. 
For non-European cards processing fees are a more standard 2.9%, plus $0.30 per charge. Additionally, for larger volume needs, it has a customized plan with volume discounts.


* **Who is the company's intended customer?  Is there any information about the market size of this set of customers? What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)**


Businesses receiving payments online with a developer first reputation.  

**Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)**


Recent move to Machine Learning for their lending platform.

Radar (Fraud product) using AI to analyze fradulant charges.  


## Landscape:

* **What domain of the financial industry is the company in?**

    Stripe is in the Financial Services and SaaS sector centered around internet infrastructure for payment processing and transaction management.

* **What have been the major trends and innovations of this domain over the last 5-10 years?**

    - mobile trends

    - online shopping trends

    n 2019, retail e-commerce sales worldwide amounted to 3.53 trillion US dollars and e-retail revenues are projected to grow to 6.54 trillion US dollars in 2022. Online shopping is one of the most popular online activities worldwide.

    According to a 2017 study by Capgemini and BNP Paribas, people worldwide will make 726 billion digital transactions by 2020.
[todo]

* **What are the other major companies in this domain?**

    Braintree Payment Solutions also provides white-labeled tools for mobile developers to process payments.  Braintree was originally founded in 2007 and later purchased by Paypal for $800 million in 2013.  In 2018 - Braintree processed 6 Billion in transactions as one of Paypal's services.  Top customers for Braintree include Uber, TaskRabbit.  Adyen is another well known competitor in the payments space.  Based out of Amsterdam and founded in 2016 - Adyen opened up payments online, offline and in applications.  Known customers include Netflix, Spotify, Dropbox and ifood.

    Braintree and Adyen serve mostly as the role of payment gateways and do not solve some of the more nuanced problems of recurring payments and subscription billing.

    According to Stripe - they are handlings hundreds of billions of dollars worth in transactions annually.

    Other direct competitors:

    - Square
    - 2Checkout
    - Authorize.net
    - 2Checkout
    - Payline Data

    Stripe has inherit competition with the industry incumbents.  




## Results

**What has been the business impact of this company so far?**



**What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?**



* How is your company performing relative to competitors in the same domain?


## Recommendations

**If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)**

**Why do you think that offering this product or service would benefit the company?**

**What technologies would this additional product or service utilize?**

**Why are these technologies appropriate for your solution?**

---
---
# Sources

[^1]: HelloWorld




Here's a simple footnote and here's a longer one.[^bignote]



* https://builtin.com/fintech/fintech-payments-companies-examples

* https://www.techradar.com/best/best-payment-gateways

    
* https://en.wikipedia.org/wiki/Stripe_(company)

* https://techcrunch.com/2012/05/20/the-story-behind-payment-disruptor-stripe-com-and-its-founder-patrick-collison/#:~:text=John%20and%20Patrick%20first%20started,had%20processed%20their%20first%20transaction.

* https://www.fundera.com/blog/stripe-competitors

* https://www.crunchbase.com/organization/stripe/

* https://www.stripe.com

* https://www.businessinsider.com/meet-the-youngest-billionaires-in-the-world

* https://www.braintreepayments.com/blog/reflections-on-our-growth-in-2018-and-beyond

* https://www.statista.com/statistics/379046/worldwide-retail-e-commerce-sales/







Headquarters: San Francisco

Its software platform lets businesses accept online payments, with customers ranging from small websites to Amazon and Facebook. In 2019, Stripe launched a new corporate credit card and small business loans, which are automatically repaid from payments it processes for borrowers. 

Bona fides: Processes hundreds of billions of dollars a year in transactions for companies like Lyft, Target and Shopify.



![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)  
---


---
# stripe_case_study
