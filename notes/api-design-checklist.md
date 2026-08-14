# API Design Checklist

- [ ] Use consistent naming (kebab-case for URLs, snake_case for JSON keys)
- [ ] Version from day one (e.g., `/v1/`)
- [ ] Return proper HTTP status codes (200, 201, 204, 400, 401, 404, 409, 422, 500)
- [ ] Include error payloads with `code`, `message`, and `details`
- [ ] Paginate list endpoints with `limit` and `cursor`
- [ ] Use RFC 3339 timestamps in UTC
- [ ] Document rate limits and auth headers
- [ ] Add `Idempotency-Key` for POST/PATCH
- [ ] Validate input before processing
- [ ] Keep responses flat, avoid deep nesting

Quick reference for my next Ruby API project.