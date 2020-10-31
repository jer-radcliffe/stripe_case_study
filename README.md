# Case Study - Stripe, Inc.

## by Jeremy Radcliffe
### October 2020

---

## Overview and Origin

Teenage entrepreneurs John and Patrick Collison started Stripe, Inc in 2010 after the Irish-born brothers experienced first hand the complexity of trying to charge for goods and services on the internet.

The brothers, college drop outs at Harvard and MIT, showed early signs of entrepreneurial chops selling their first e-commerce business, Auctomatic, in 2008.   The sale made the seventeen and nineteen year olds millionaires over night.  Eight years later in 2016 - after Stripe's valuation of $9.2 billion, John and Patrick became the world's youngest billionaires. The concept of Stripe came about in 2010 out of the founder's personal experience of the difficulty in setting up e-commerce websites on their own projects.  <sup>1</sup>

> *“Stripe really did come about because we were really appalled by how hard it was to charge for things online.”* — John Collison <sup>2</sup>

In 2009 the brothers tackled the payment challenge and over the course of two weeks prototyped a solution that processed their first credit card transaction.  Being avid developers themselves - they beta tested their solution with the developer community.  Their quick iterations grew in popularity as a "developer friendly" option for businesses to start receiving online payments immediately.  Developers welcomed Stripe as a contrast to having to wait in some instances days or weeks for merchant account approval, if approval was given at all.<sup>3</sup>  
    
The goal was to make it as easy as possible to implement Stripe and the earliest versions of Stripe's setup only required the following 7 lines of code on a checkout page to start receiving online payments.

**Stripe's Sample Checkout Code**   <sup><sup>4</sup></sup>

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

> *“We wanted it to be extremely simple to integrate. You should be able to start charging credit cards immediately. There shouldn’t be any latency. You shouldn’t have to talk to anybody. The information you have to give shouldn’t be pages long… Google Checkout and PayPal are these confusing things, and we wondered why they hadn’t solved these issues.”* — Patrick Collison <sup>5</sup>


The brothers saw a massive opportunity that at that point nobody else had been able to upend.

> *As we built Auctomatic, we interacted with dozens of small and medium-sized business, and we learned how hard it was to accept payments as an online business.  People would apply for a merchant account, and it required heaps of paperwork and an elaborate approval process.  Many business were rejected because they didn't have a history of receipts -- but how were they supposed to have a business history if they couldn't get a merchant account?  And even if they could get a merchant account, they got one product - the ability to accept credit card payments in a single transaction.  This didn't allow for recurrring payments, marketplaces, or other complex types of transactions.    Nor did it allow businesses to capture data associated with their transactions.  This system didn't make sense.  People could build services and products that reached people around the world through the Internet, yet they couldn't get paid.  It got us thinking that there had to be a better way of doing things.* - John Collison <sup>6</sup>

Stripe finished Series G Funding as of April 2020.  They have currently raised $1.6 billion from lead VC firms like Sequioia Capital, General Catalist, Tiger Global Management and DST Global.  As of 2020 - Stripe's latest valuation of $35 billion makes it the most valuable private fintech in the U.S.<sup>6</sup>


## Business Activities:

Stripe's mission is "to increase the GDP of the internet" by creating a suite of APIs that give businesses of every size the ability to accept payments and manage their business online. They are focused on the economic infrastructure for the internet by providing a range of flexible tools for businesses to customize their payment processes.<sup>7</sup>

Prior to Stripe - doing business online was no small challenge trying to navigate the financial system of setting up merchant accounts, currency challenges for international transactions or complex transactions like recurring payments.  Stripe's services helps customers bypass these hurdles allowing them to focus on growing their businesses and not the technical quirks of taking payments online.

What started out with the idea of simplifying payment setup for the internet has now morphed into a mission of impacting economic growth around the world.  That now includes products like Stripe Connect for social commerce and online marketplaces as we see with Shopify, and more recently the creation of Atlas which helps international businesses quickly create a valid legal presence in the United States with tax ids and bank accounts broadening their reach.<sup>8</sup>  Stripe sees itself as the champion for frictionless trade across boarders.

### **Background**
#### **Steps to a Credit Card Transaction** <sup>6</sup>

You experience it on a daily basis but it's worth diving into the process of what happens when a customer uses their credit card with a merchant.

- 1.  Merchant contracts with payment gateway
- 2.  Payment gateway receives the transaction request and submits it to the merchant bank's processor using a secure site connection
- 3.  Merchant bank's processor sends the transaction to the credit car network who then forwards the transaction request to the issuing bank for the customer's credit card.
- 4.  Issuing bank then accepts or refuses the transaction based on the transaction and customer's available funds and sends the results back to the credit card network.  
- 5.  Credit card network  transmits the results to the merchant bank's processor which then sends the results to the payment gateway.  
- 6.  The results of transaction were saved and available to the merchant and customer.  If transaction was approved the customer's credi-card issuing bank would send funds to the credit card network, which then sends funds to the merchant's bank.  Round trip process taking < 3 seconds with funds being available to the merchant within two to four business days.

![Credit Card Process](images/cc-process.png) <sup>Robert Siegel and Ryan Kissick, “Stripe: Increasing the GDP of the Internet” HBS No. E601 (Stanford Graduate School of Business, 2016), http://hbsp.harvard.edu, accessed October 2020</sup>


### People who make things on the web

> “Our target audience is the people making things on the web” - Patrick Collison <sup>2</sup>

Stripe is positioning it's suite of apis and services to serve the internet shopper.  With projected retail e-commerce sales worldwide to be over $4 trillion for 2020 and eclipsing $6 trillion by 2023 Stripe is well positioned to profit from the year over year growth.  With the continual growth of internet access and mobile payment options the opportunities seem endless in the near future.<sup>8</sup> 

![](images/e-commerce-2020.png)<sup>8</sup>


In 2016 Stripe introduced Radar as their defense against fraudulent online activity.  "Unlike their brick-and-mortar competitors, online stores were financially liable for fraud, which cost them tens of billions of dollars per year"<sup>6</sup>  Fraud protection is a catch twenty-two because rules to protect against fraudulent purchases often block legitimate transactions.  Radar uses machine learning algorithms stacked on top of the hundreds of thousands of transactions that flow through the Stripe network every second.  All of this at no extra cost or setup required, Stripe protects their customers businesses out of the box.<sup>6</sup>

 In 2019 Stripe Capital rolled out as a new product to continue their mission of global GDP growth.  Using AI and Machine Learning - Stripe Capital allows for capital injections into internet businesses with no contact approvals.  Machine Learning and AI programs issue approvals within a day making funds available the next day.

> *“Stripe Capital makes it easy for internet businesses to get the funds they need, when they need them,” said Will Gaybrick, Stripe’s Chief Product Officer. “It’s important to think about financial inclusion not just in terms of consumers, but also in terms of businesses. Businesses, especially small businesses and startups, are the engines for job creation in our economy. It should be trivially simple and lightning fast for them to access the capital they need to smooth their cash flow and invest in their own growth.”* <sup><sup>4</sup></sup>

## Landscape:

As of 2000, e-commerce accounted for less than 1 percent of all U.S. retail sales; twenty years later that figure is now over 16% as of 2020.<sup>8</sup>  Stripe wants to help businesses grow and take advantage of online sales growth by being the premier infrastructure for payment processing and transaction management.

The move away from cash and credit card transactions to digital payment methods is one of the most recent significant changes in the landscape of payments.  440 million users took advantage of digital payment options in 2018, that is expected to grow to 760 million in 2020.<sup>8</sup>
  
Online shopping is one of the most popular online activities worldwide.  According to a 2017 study by Capgemini and BNP Paribas, people worldwide will make 726 billion digital transactions by 2020.<sup>9</sup>  

#### **Competition and Incumbents**
Stripe shares the payment arena with several other well know companies.  Braintree Payment Solutions also provides white-labeled tools for mobile developers to process payments.  Braintree was originally founded in 2007 and later purchased by Paypal for $800 million in 2013.  In 2018 - Braintree processed 6 Billion in transactions as one of Paypal's services.  Top customers for Braintree include Uber, TaskRabbit.  Adyen is another well known competitor in the payments space.  Based out of Amsterdam and founded in 2016 - Adyen opened up payments online, offline and in applications.<sup>6</sup>  Known customers include Netflix, Spotify, Dropbox and ifood.

Braintree and Adyen serve mostly as the role of payment gateways and do not solve some of the more nuanced problems of recurring payments and subscription billing.

Other direct competitors:<sup>10</sup>

- Square
- 2Checkout
- Authorize.net
- 2Checkout
- Payline Data

Stripe  also has inherit competition with the financial incumbents as well.  In many cases Strip has taken on the attitude of "everyone can grow" but there have been concerns of the credit card networks and large banks building their own payment infrastructures.<sup>6</sup> Stripe has maintained that what's good for the banks and credit card networks is good for the internet business and the the online shopper and ultimately good for Stripe.

According to Stripe - they are handlings hundreds of billions of dollars worth in transactions annually <sup>11</sup> and have partnered with household names like Lyft, Target and Shopify.  Even if a card is new to an online business, there’s an 89% chance it’s been seen before on the Stripe network.<sup>4</sup>  With Stripe collecting 2.9% + $.30 on each transaction - they have become the toll booth for e-commerce transactions.  

## Days Ahead

Stripe turned a pain point for developers into a flexible infrastructure for payments that has exploded over the last ten years. There's no indication that internet sales will be reversing over the next five to ten years so it is crucial that Stripe and the Collison brothers stay on the forefront of what payments look like in the future.  Disruptive technologies like digital currencies and smart contracts will grow in adoption and though the threat of fiat currency going away entirely is minimal - the author would argue that we never expected a global pandemic in 2020 either.  

#### **Future of Payments**

Payments in the future will be less tied to plastic in our wallets or phones in our pockets but more our physical persons.  Consider Biometric Payments.  We've already seen this to some degree on mobile payment technology tied to fingerprinting, but imagine in the not too distant future being able to pay for your Instacart groceries via a retinal scan or facial recognition.  Stripe is already moving in this direction with their 2019 acquisition of Touchtech Payments.  <sup>12</sup>  Data shows that there's a 33% chance of a shopper abandoning a transaction when prompted for a 3D Secure Password - a European requirement for online payments called Strong Customer Authentication.  Moving these requirements to biometric validations minimizes lost sales.  Worldwide GDP growth is dependent on facilitating easy and safe online shopping.  Stripe started out building an infrastructure to support businesses to take payments online - their next step needs to focus on changing the behaviors of online shoppers and finding methods to payments that feels as safe as cash.

#### **Battling the Evil Internet**
 As e-commerce continues to explode the reality of fraud and identity theft will grow with it.  As Morpheos said in the Matrix - "Throughout human history, we have been dependent on machines to survive. Fate, it seems, is not without a sense of irony."  Enter the AI and Machine Learning bots to battle fraud and identity theft.  With exponentially growing datasets, companies like Stripe are able to stop fraudulent activity early on with technologies trained to recognize abnormalities in activity.  This technology will only grow more efficient in identifying valid paying customers versus dark web activity.

#### **Mining for Data**
Where I see Stripe's future is in it's ability to monetize their data.  With millions of transactions processed per year and each transaction providing insight on customer behavior - Stripe is sitting on a gold mine of big data.  How they use that data in the near and distant future will influence the field of payments as well as new technologies and advances we have yet to see.    


# Sources
1. https://en.wikipedia.org/wiki/Stripe_(company)

2. https://www.fastcompany.com/1813087/inside-stripe-paypal-competitor-backed-paypal-founders-peter-thiel-elon-musk

3.  https://techcrunch.com/2012/05/20/the-story-behind-payment-disruptor-stripe-com-and-its-founder-patrick-collison/

4. https://www.stripe.com

5. https://www.cbinsights.com/research/report/stripe-teardown/

6. Robert Siegel and Ryan Kissick, “Stripe: Increasing the GDP of the Internet” HBS No. E601 (Stanford Graduate School of Business, 2016), http://hbsp.harvard.edu, accessed October 2020.

7. https://www.braintreepayments.com/blog/reflections-on-our-growth-in-2018-and-beyond

8. https://www.statista.com/statistics/379046/worldwide-retail-e-commerce-sales/

9. https://www.cnbc.com/2017/10/09/digital-payments-expected-to-hit-726-billion-by-2020-study-finds.html

10. https://www.fundera.com/blog/stripe-competitors

11. https://www.techradar.com/best/best-payment-gateways 

12. https://www.biometricupdate.com/201904/stripe-acquires-biometric-software-provider-touchtech-payments-to-support-gdpr-requirements



