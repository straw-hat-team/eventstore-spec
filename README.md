# eventstore-spec

## AppendStream

- `Event Id` must be able to be set, Why: in some cases, the `Event Id` must be a deterministic ID used for idempotency sake
- Idempotency based on the `Event Id`

## ReadStream
