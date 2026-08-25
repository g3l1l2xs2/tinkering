# API Design Tinkering

Quick notes from today's experiments with RESTful API patterns.

- Prefer JSON:API (`application/vnd.api+json`) for structured responses.
- Version via Accept header instead of URL path to keep URIs stable.
- Use `ETag`/`If-None-Match` for conditional requests and caching.
- Paginate with `Link` header (RFC 8288) rather than envelope metadata.
- Consider `409 Conflict` for state-changing requests on stale resources.

Next: try out these patterns in a small Sinatra app.
