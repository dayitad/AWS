## AWS

#### EC2
Amazon EC2(Elastic Compute Cloud) is a webservice that provides resizable compute capacity in cloud. It reduces the time required to obtain and boot new server instances to minutes, allowing to quicly scale capacity both upwards and downwards based on changing computing requirements.

It has changed the economics of computing by allowing to pay for what is being used. It provides the tools needed to build a failure resistent application.

#### Types of Instances 
+ On Demand - allows to pay by the hour or second(Linux is by second and Windows is by hour)
+ Reserved - Reservation for 1 or 3 years, certain or entire amount upfront, but large discount compared to on demand price.
+ Spot - enables to bid a price for instance capacity, if application has flexible timings, this can lead to significant savings.
+ Dedicated host - These are physical ec2 server dedicated for use. They allow to bring exisitng server-bound software licenses over to aws and thus save costs.

##### On Demand Instances
+ Perfect for users who want low cost and flexibility of AWS EC2 without any long term commitment or contract
+ Applications with Unpredictable workloads that cannot be interrupted
+ Development and testing

##### Reserved Instances
+ Applications with steady state or predictable usage that require reserved capacity
+ Users willing to make upfront payment to reduce computing cost even further
  + Standard RIs(upto 75% off on demand) - if entire payment is made upfront and contract is for 3 years
  + Convertible RIs(upto 54% off on demand) - capability to change attribute of instance from say compute to memory intensive provided the     exchange is of equal or greater value 
  + Scheduled RIs - available to launch within a scheduled time window. It allows to obtain compute capacity within a certain recurring     schedule. For example if a company has large sales during fridays, then it will go for RIs scheduled on every friday.

