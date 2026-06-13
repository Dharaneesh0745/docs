# Troubleshooting Guide

Common issues and solutions.

## Connection Errors

**Problem**: Cannot connect to database

**Solution**: 
- Check if MongoDB is running
- Verify connection string in config
- Check firewall settings

## Performance Issues

**Problem**: Slow API responses

**Solution**:
- Add database indexes
- Enable caching
- Check server logs for errors

## Common Error Codes

| Code | Message | Solution |
|------|---------|----------|
| E001 | DB Connection Failed | Restart MongoDB |
| E002 | Timeout | Increase timeout value |
| E003 | Invalid Token | Check API key |
