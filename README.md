# sMart-web-server

## API Guide

#### GET /deliveries

#### POST /deliveries

| HTTP METHOD | POST            | GET       | PUT         | DELETE |
| ----------- | --------------- | --------- | ----------- | ------ |
| CRUD OP     | CREATE          | READ      | UPDATE      | DELETE |
| /dogs       | Create new dogs | List dogs | Bulk update | Delete all dogs |
| /dogs/1234  | Error           | Show Bo   | If exists, update Bo; If not, error | Delete Bo |

#### POST /deliveries/quote

#### GET /deliveries/{delivery_id}

#### GET /deliveries/{delivery_id}/receipt

#### GET /deliveries/{delivery_id}/ratings

#### POST /deliveries/{delivery_id}/ratings

#### GET /deliveries/{delivery_id}/rating_tags

#### POST /deliveries/{delivery_id}/cancel

#### GET /deliveries/regions