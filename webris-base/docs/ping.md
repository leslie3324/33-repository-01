# /api/ping

Returns the service name and server time. Used by the load balancer health check.

```http
GET /api/ping
{"status":"ok","service":"webris-base","time":"2026-11-26T15:30:00Z"}
```

No authentication required.
