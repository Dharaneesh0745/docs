# Advanced Configuration

Learn advanced configuration options for power users.

## Configuration File

Create a `.config.json` file in the root directory:

```json
{
  "database": {
    "host": "localhost",
    "port": 27017
  },
  "server": {
    "port": 3000,
    "timeout": 5000
  }
}
```

## Environment Variables

- `DB_URL` - Database connection string
- `API_KEY` - API authentication key
- `NODE_ENV` - Environment (development/production)
