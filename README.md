# flask_microservices

**Endpoints**:

|Method|URI|Description| Status |
|------|---|-----------|--------|
| GET | /api/v1/products | This endpoint retuns the state of the service | 200 |
| POST | /api/v1/products | it will receive the room payload, and it will proceed to index it | 201 |
| PUT | /api/v1/products/<product_id> | this PUT method will allow us to make changes on the indexed item | 200 |
| PATCH | /api/v1/products/<product_id> | this PATCH method will allow us to make changes on the indexed item | 200 |
