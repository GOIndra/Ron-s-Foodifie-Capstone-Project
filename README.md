# Ron-s-Foodifie-Capstone-Project


INTRODUCTION :        
               Ron and his buddies founded Foodie-Fi and began selling monthly and annual
subscriptions, providing clients with unrestricted on-demand access to exclusive cuisine
videos from around the world.

               This case study focuses on the use of subscription-style digital data to answer critical
business questions about the customer journey, payments, and business performance.


DATA SOURCE : https://www.db-fiddle.com/f/jbahqhW5AQwqV1RZ2xExEz/0


TOOLS USED  : Mysql, Microsoft Excel
              
              Mysql is used for executing queries and get result and Excel is used to make charts and trends to visualize the 
              performance of the business
I

DATA DESCRIPTION:

Table ‘plans’ Description

  There are 5 customer plans:

Trial —   Customers sign up for a 7-day free trial and will be automatically enrolled in the pro monthly subscription plan
unless they unsubscribe, downgrade to basic, or upgrade to an annual pro plan during the trial.

Basic plan — 
          Customers have limited access and can only stream their videos with the basic package, which is only
available monthly for $9.90.

Pro plan — 
         Customers on the Pro plan have no watch time limits and can download videos for offline viewing. Pro
plans begin at $19.90 per month or $199 for a yearly subscription.

         When clients cancel their Foodie-Fi service, a Churn plan record with a null pricing is created, but their plan continues
until the end of the billing cycle.


Table ‘subscriptions’ Description

Customer subscriptions display the precise date on which their specific plan id begins.

        If a customer downgrades from a pro plan or cancels their subscription — the higher program will remain in place until
the period expires — the start date in the subscriptions table will reflect the date the actual plan changes.

        When clients upgrade their account from a basic plan to a pro or annual pro plan, the higher plan becomes active
immediately.

        When customers cancel their subscription, they will retain access until the end of their current billing cycle, but the
start date will be the day they opted to quit their service.



OUTCOMES :
            1)  The drawbacks or reason for downfall of the business are throughly discussed 
            2)  The overall health has been analyzed in detail
            3)  The key factors have been potrayed with proper charts for better visualization
            4)  All the points have been mentioned in 'Keypoints' section. 



 


