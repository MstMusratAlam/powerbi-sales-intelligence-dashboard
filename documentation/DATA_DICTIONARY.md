# Data Dictionary for Power BI Sales Intelligence Dashboard

## Tables and Field Definitions

### 1. Sales
| Field Name       | Description                     | Data Type | Example           |
|------------------|---------------------------------|-----------|-------------------|
| Sale ID          | Unique identifier for the sale | Integer   | 1001              |
| Product ID       | Unique identifier for product   | Integer   | 501               |
| Quantity Sold    | Number of items sold            | Integer   | 5                 |
| Sale Date        | Date of the sale                | Date      | 2025-12-01        |
| Total Revenue    | Total revenue generated         | Decimal   | 150.75            |

### 2. Products
| Field Name       | Description                     | Data Type | Example           |
|------------------|---------------------------------|-----------|-------------------|
| Product ID       | Unique identifier for product    | Integer   | 501               |
| Product Name     | Name of the product              | String    | Widget A          |
| Category         | Category of the product          | String    | Gadgets           |
| Price            | Price of the product             | Decimal   | 30.15             |

### 3. Customers
| Field Name       | Description                     | Data Type | Example           |
|------------------|---------------------------------|-----------|-------------------|
| Customer ID      | Unique identifier for customer   | Integer   | 201               |
| Customer Name    | Name of the customer             | String    | John Doe          |
| Email            | Email address of customer        | String    | john@example.com  |
| Join Date        | Date the customer joined         | Date      | 2025-01-15        |

### 4. Regions
| Field Name       | Description                     | Data Type | Example           |
|------------------|---------------------------------|-----------|-------------------|
| Region ID        | Unique identifier for region     | Integer   | 301               |
| Region Name      | Name of the region               | String    | North America     |  
| Country          | Country in the region            | String    | USA               |  
