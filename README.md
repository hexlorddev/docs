---
title: 'Introduction'
description: 'Authenticate and start making requests to the Playpulse Panel API.'
icon: 'puzzle'
---
Playpulse Panel provides a powerful API for programmatic interaction. All API requests require Bearer token authentication.

### Authentication
To authenticate your API requests, include a Bearer token in the `Authorization` header. Replace `YOUR_TOKEN` with your actual API token.

```bash
curl -H "Authorization: Bearer YOUR_TOKEN" \
     -H "Content-Type: application/json" \
     https://your-panel.com/api/v1/servers
