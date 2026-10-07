# mini-lineman-order

order-service (Go). Client-facing, changes often — kept in its own repo for that reason.

Status: **skeleton only.** No service code yet.

Part of the mini-lineman system. Architecture, phases and conventions live in the
`mini-lineman` repo (`CLAUDE.md`); decisions are recorded as ADRs in
`mini-lineman/docs/decisions/`.

## Toolchain

Pinned by ADR 0001: Go 1.27.1 with `GOTOOLCHAIN=local`, `golangci-lint` v2.14.0.
CI runs inside `ghcr.io/surakietart/mini-lineman-go-tools`, so the image — not this repo's
`go.mod` — decides the Go version.
