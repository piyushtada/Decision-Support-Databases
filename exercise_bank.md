# TestStar DB on JRS 1

```
Schema :
InvoiceLines(FkInvoiceNo*, LineNo, FkProduct*, Qty, Price)
Invoices(PkInvoiceNo, Date, FkCustomer*)
Customers(PkCustomer, CustomerName, CustomerType, FkCountry*)
Countries(PkCountry, Nation, Continent)
Products(PkProduct, ProductID, ProductName, Category, UnitPrice)
```

## EXERCISES: WRITE RELATIONAL EXPRESSIONS / LOGICAL TREES 2

- _Revenue is Qty*Price_
- Find the invoice lines with revenue > 5000
- Find the revenue of every invoice line
- Find the FkProduct sold in at least one invoice line
- Find the total revenue by FkProduct
- Find the total revenue for FkProductin invoice lines with Price > 2000
- Find the total revenue for FkProductwith at least 10 pieces of total quantity
    sold


## EXERCISES: WRITE RELATIONAL EXPRESSIONS / LOGICAL TREES 3

- _Revenue is Qty*Price_
- Find the total revenue by product category
- Find the total revenue by customer nation for sales of product category ‘Cat01’
- Sort the customer names by total revenue descending
- Find the total revenue of sales to customers from Finland of products from
    category ‘Cat01’
- Find customers with no sales


