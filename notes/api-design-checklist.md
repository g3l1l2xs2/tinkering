# API Design Checklist

Quick notes for tinkering with new endpoints.

- Use consistent resource names and plural nouns.
- Prefer nested routes only for obvious ownership.
- Return stable error codes with a short message and a reference id.
- Keep JSON keys snake_case unless the client contract says otherwise.
- Document pagination limits and default sort order.
- Version via the URL path or media type, not a query param.
- Make idempotency explicit for POSTs that create resources.
- Avoid breaking changes; add fields instead of renaming them.

Still a draft. Will refine as I keep tinkering.