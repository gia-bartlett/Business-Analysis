





**Scenarios:**  

Consider an example scenario where a customer wishes to place an order via the telephone.
```
The precondition might be that for the process to happen the sales clerk is already logged in to the sales system.
The default steps for the telesales clerk could then be:

1. enter customer reference number;
2. confirm customer details;
3. record order items;
4. accept payment;
5. advise customer of delivery date.

In order for this scenario to flow in the sequence shown, the control conditions to go from step (i) to 
step (ii), step (ii) to step (iii), and so on must be true. For example, the order items recorded in step (iii) 
must be in available for step (iv) to take place. However, if there were insufficient stock then the next 
step to be followed would not be step (iv) but an alternative step. There may be several possible 
actions to be taken following this alternative step, such as:

delay an order fulfilment until stock arrives;
allocate a substitute item;
send an order and the customer’s delivery details directly to the supplier.

At the (successful) conclusion of the process the postcondition might be: The customer order has been 
recorded, stock levels have been adjusted and payment has been received.

All of the possibilities should be explored, and documented as alternative paths; these are termed 
‘extensions’ to the default scenario. This process helps to ensure that all possible situations and 
exceptions are anticipated, and so help satisfy the law of requisite variety.
```

The example scenario above is described in a generic, abstract manner and some users may find this 
approach difficult to apply to the reality of their work. Another possible approach is known as a 
‘concrete’ scenario where a specific narrative or story is developed and then tested against the 
requirements already identified to find the gaps.  

Here is an example of a concrete scenario for a vehicle parts system:
```
Turpin Coaches calls with an urgent request for 500 Type 2 gaskets. They are a highly valued – 
and valuable – customer. They tell the clerk that if we cannot satisfy them, they must go 
elsewhere. The stock records show that there are 150 Type 2 gaskets available. Four hundred 
were allocated to ZED just 30 minutes previously. Their order will not be processed for another 2 
hours. The clerk wishes to amend the ZED order.
```
Using this concrete scenario, we can see that there is a possible extension in that an order may be 
prioritised and amended, giving rise to alternative paths through the ‘take order’ scenario. This will 
require the analyst to record additional requirements to those reflected in the ‘happy day’ such as the 
ability to prioritise orders and to amend orders already accepted. Concrete scenarios such as this 
example are extremely useful in helping to uncover where all the possible extensions lie and can be 
used during one-to-one discussions or workshops.
