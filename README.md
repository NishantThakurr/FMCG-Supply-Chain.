
# FMCG Supply Chain Analysis

Trying to understand why key customers are not renewing their contracts.

# Business Knowledge

Orders and Lines
-> Orders are nothing but a unique request placed by a customer on a given date
-> Within an order, a customer could request multiple items. Each of these items
requested within the order is called an order line
Example: Let's say you order 4 notebooks and 2 pens at Amazon. A unique order ID is
generated for all these items. Notebook and Pen is an order line.
Measuring Line Fill Rate & Volume Fill Rate
-> Line Fill Rate is an important metric for the supply planning team to understand how
many lines they shipped out of the total lines ordered. This metric does not consider the
delivery time of the order.
-> Volume fill rate or case fill rate is a similar metric useful for the supply planning team to
understand the total quantity they are able to ship for a customer per order or for a given
period of time
Example: In above example let's say Amazon is able to ship you 4 notebooks and 1 pen.
The line item pen is failed because you requested 2 nos. So Line Fill Rate for Amazon for
your order is order lines fulfilled / lines ordered => 1/2 => 50 %.
Volume Fill rate will be total quantity shipped / total quantity ordered => 5/6 => 83 %

## Tech Used

Power BI
M Language
DAX

## Data Model

![Screenshot 2022-11-22 152114](https://user-images.githubusercontent.com/102639991/203282922-59fa002a-a90d-412f-b2c4-66567f960680.png)
## Live Dashboard

![Screenshot 2022-11-22 152502](https://user-images.githubusercontent.com/102639991/203305970-120a7f61-bc5c-4f20-924e-605e1a7639c3.png)
![Screenshot 2022-11-22 152533](https://user-images.githubusercontent.com/102639991/203283903-9ac8a21a-db73-43cf-badf-8f10d255bcc0.png)

## Insights
1)The KPI's such as OT%, IF%, OTIF% are far behind the target.
2)The Customers with highest number of orders have most delay in their orders.
This may be because the expected number of orders are less than the actual orders for these Customers.
