# Data Dictionary - Retail Sales Portfolio

### Annex 1: Item Master
- Item Code: Unique identifier for each product (Categorical/Key)
- Item Name: Name of the item (Text)
- Category Code: Unique code for the item's broad category (Categorical)
- Category Name: Name of the department/category (Text)

### Annex 2: Daily Sales Transactions
- Date: Date of transaction (Datetime)
- Time: Time of transaction (Time)
- Item Code: Unique identifier matching the product (Key)
- Quantity Sold (Kilo): Total weight sold in kilograms (Numerical)
- Unit Selling Price (RMB/kg): Price charged per kilogram (Numerical)
- Sale or Return: Whether the item was bought or returned (Text)
- Discount (Yes/No): Indicator if a markdown was applied (Text)

### Annex 3: Wholesale Pricing
- Date: Date pricing applies to (Datetime)
- Item Code: Unique identifier matching the product (Key)
- Wholesale Price (RMB/kg): Cost price paid by the retailer per kilogram (Numerical)

### Annex 4: Inventory Loss
- Item Code: Unique identifier matching the product (Key)
- Item Name: Name of the item (Text)
- Loss Rate (%): Percentage of stock lost to spoilage/waste (Numerical)
