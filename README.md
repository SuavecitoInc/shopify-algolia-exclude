# Get Excluded Online SKUs

> A simple tool that fetches all Shopify products and product variants. It then generates a list of all variants marked with metafield excluded_online. This list is used to exclude them from Algolia search.

### Setup

```bash
SHOPIFY_ADMIN_API_VERSION=2024-07
SHOPIFY_STORE=suavecito
SHOPIFY_ACCESS_TOKEN=
```

### Generate Types

```bash
npm run generate
```

### Run

```bash
npm run excluded-online
```

```bash
npm run exclude-online

> shopify-algolia-exclude@0.0.1 exclude-online
> tsx src/index.ts

-----------------------------------------------
Fetching all products
Searching for excluded variants
Excluded Variants: 21
Fetching next page eyJsYXN0X2lkIjo0OTAyMTQwMjI4LCJsYXN0X3ZhbHVlIjoiNDkwMjE0MDIyOCJ9
Excluded Variants: 35
Fetching next page eyJsYXN0X2lkIjoxMTczMzk1OTExOSwibGFzdF92YWx1ZSI6IjExNzMzOTU5MTE5In0=
Excluded Variants: 42
Fetching next page eyJsYXN0X2lkIjoxMzQ2MDY4ODczMjk5LCJsYXN0X3ZhbHVlIjoiMTM0NjA2ODg3MzI5OSJ9
Excluded Variants: 50
Fetching next page eyJsYXN0X2lkIjozOTQ1MzI2NjQxMjM1LCJsYXN0X3ZhbHVlIjoiMzk0NTMyNjY0MTIzNSJ9
Excluded Variants: 55
Fetching next page eyJsYXN0X2lkIjo0NDA4ODA1MjYxMzk1LCJsYXN0X3ZhbHVlIjoiNDQwODgwNTI2MTM5NSJ9
Excluded Variants: 58
Fetching next page eyJsYXN0X2lkIjo2NTUzNDgzOTAzMDU5LCJsYXN0X3ZhbHVlIjoiNjU1MzQ4MzkwMzA1OSJ9
Excluded Variants: 60
Fetching next page eyJsYXN0X2lkIjo2ODE4NjI3OTQ0NTMxLCJsYXN0X3ZhbHVlIjoiNjgxODYyNzk0NDUzMSJ9
Excluded Variants: 60
Fetching next page eyJsYXN0X2lkIjo3MTIyNDEzODEzODQzLCJsYXN0X3ZhbHVlIjoiNzEyMjQxMzgxMzg0MyJ9
Excluded Variants: 60
-----------------------------------------------
Excluded Variants Found: 60
-----------------------------------------------
Copy and paste the above list of SKUs to the exclude list in the Shopify Theme Settings
-----------------------------------------------
P278NN, P031NN, P543NN, P551NN, P279NN, P414NN, P032NN, P552NN, P060NN, S323B1, S323B2, S323B3, S323B4, P397NN, P399NN, P059NN, P068NN, S326B1, S326B2, S326B3, S326B4, P400NN, P394NN, P344NN, P462NN, P442NN, P467NN, P459NN, P357NN, P322NN, P479NN, P332NN, P501NN, P553NN, C146BN, P245NN, P191NN, P222NN, P232NN, P398NN, P402NN, P401NN, K-P254-3, K-P254-5, P395NN, P396NN, C129NN, K-P293-3, K-P293-5, S603BS, TN-SX-TT-001, S325B1, S325B2, S325B3, S325B4, P383NN, K-P383-3, K-P383-5, TN-BS-WEES, TN-CL-003
-----------------------------------------------
```
