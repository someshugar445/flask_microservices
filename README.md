# flask_microservices

This is a basic approach of building a Microservice on top of Flask, with some useful packages like:

Flask

**Endpoints**:

|Method|URI|Description| Status |
|------|---|-----------|--------|
| GET | /api/v1/products | This endpoint returns the list of products | 200 |
| POST | /api/v1/products | it will receive the product payload, and it will proceed to index it | 201 |
| PUT | /api/v1/products/<product_id> | this PUT method will allow us to make changes on the indexed item | 200 |
| PATCH | /api/v1/products/<product_id> | this PATCH method will allow us to make changes on the indexed item | 200 |
