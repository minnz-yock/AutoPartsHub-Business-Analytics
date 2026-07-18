# Data Dictionary

This document describes the datasets used in the AutoPartsHub Business Analytics Dashboard.

---

## Supplier Table

| Column | Description |
|--------|-------------|
| Supplier ID | Unique identifier for each supplier |
| Supplier Name | Supplier company name |
| Contact Person | Supplier contact person |
| Contact Number | Supplier contact number |
| Products Supplied | Products provided by the supplier |

---

## Supplier Orders Table

| Column | Description |
|--------|-------------|
| Supplier Order ID | Unique supplier order identifier |
| Supplier ID | Supplier reference |
| Product ID | Ordered product |
| Order Quantity | Quantity ordered |
| Order Date | Date of supplier order |
| Total Cost (MMK) | Total purchasing cost |
| Status | Supplier order status |

---

## Inventory Table

| Column | Description |
|--------|-------------|
| Product ID | Unique product identifier |
| Product Name | Product name |
| Product Type | Product category |
| Warehouse Location | Warehouse storing the product |
| Available Stock | Current inventory quantity |
| Expiration Date | Product expiration date |
| Unit Cost (MMK) | Purchasing cost per unit |
| Unit Price (MMK) | Selling price per unit |

---

## Order Table

| Column | Description |
|--------|-------------|
| Order ID | Unique customer order identifier |
| Customer ID | Customer reference |
| Total Order Quantity | Total quantity ordered |
| Order Date | Date of the order |
| Total Amount (MMK) | Total order value |

---

## Order Detail Table

| Column | Description |
|--------|-------------|
| Order Detail ID | Unique order detail identifier |
| Order ID | Parent order reference |
| Product ID | Product ordered |
| Quantity | Quantity purchased |
| Subtotal (MMK) | Subtotal amount for the item |

---

## Customer Table

| Column | Description |
|--------|-------------|
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Email | Customer email address |
| Purchase History | Previous purchasing information |
| Region | Customer region |

---

## Payment Table

| Column | Description |
|--------|-------------|
| Payment ID | Unique payment identifier |
| Order ID | Related customer order |
| Payment Date | Date of payment |
| Payment Method | Payment method used |
| Payment Status | Payment status |

---

## Delivery Table

| Column | Description |
|--------|-------------|
| Delivery ID | Unique delivery identifier |
| Order ID | Related customer order |
| Quantity Shipped | Quantity delivered |
| Delivery Date | Delivery date |
| Delivery Status | Delivery status |
| Shipping Method | Shipping method |
| Tracking Number | Shipment tracking number |
| Customer ID | Customer reference |