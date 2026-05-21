# RPC API Lab

Build method-oriented APIs with explicit procedure calls and structured errors.

## Core concepts

- Method registry and discovery
- Request envelope and parameter validation
- Error object conventions
- Idempotent vs non-idempotent method semantics
- RPC vs REST boundary tradeoffs

## Suggested Stack

- JSON-RPC or XML-RPC server framework

## Learning Tasks

- Implement method registry
- Validate parameter schemas
- Add structured RPC error responses
- Add auth checks per method
- Compare equivalent REST endpoint behavior

## Validation checklist

- [ ] Unknown methods return proper errors
- [ ] Params are validated per method
- [ ] Auth is enforced at method boundary
- [ ] Error envelope is consistent
