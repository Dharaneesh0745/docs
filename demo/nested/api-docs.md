# API Documentation

This page contains API reference documentation.

## Endpoints

### GET /api/users
Returns a list of all users.

```json
{
  "users": [
    { "id": 1, "name": "John" },
    { "id": 2, "name": "Jane" }
  ]
}
```

## Response Codes

- `200` - Success
- `404` - Not found
- `500` - Server error
