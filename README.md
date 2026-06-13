# Cornerstone OnDemand

Cornerstone OnDemand is an enterprise talent management platform offering REST APIs for learning management, performance reviews, succession planning, recruiting, and workforce analytics across enterprise organizations.

## Developer Portal

https://csod.dev/

## APIs

- **Employee and OU API** - Synchronize employee records and organizational unit structures
- **Learning Assignment API** - Assign training courses to user transcripts programmatically
- **Recruiting API** - Manage job requisitions, candidates, and applications
- **Reporting API** - Access workforce analytics via OData-compatible interface
- **Bulk API** - Import large data volumes asynchronously
- **Performance API** - Manage performance reviews, goals, and succession planning
- **Webhooks** - Real-time HTTP event notifications for business events

## Authentication

OAuth 2.0 Client Credentials grant type. Register applications via Admin > Tools > Edge > API Management to obtain a client ID and secret. Token endpoint: `POST https://[corpname].csod.com/services/api/oauth2/token`

## Status

https://status.csod.com/

## Resources

- [APIs.json](apis.yml)
- [Plans and Pricing](plans/cornerstone-plans-pricing.yml)
- [Rate Limits](rate-limits/cornerstone-rate-limits.yml)
- [FinOps](finops/cornerstone-finops.yml)
