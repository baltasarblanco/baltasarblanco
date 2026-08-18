# Baltasar Blanco

Backend developer in Buenos Aires. I spent seven years in audio engineering before
switching to software, and most of what I know about systems I learned by reading
code I didn't write — which is also how I spend a good part of every month.

Rust · Python · Go

---

## What I do every month

Three codebases, roughly one merged patch each per month since May 2026. Same three
on purpose: the fifth patch to a project you understand is worth more than the first
patch to five you don't. **13 PRs opened, 11 merged.**

### [astral-sh/ruff](https://github.com/astral-sh/ruff) — Python linter and formatter, in Rust
**4 opened · 4 merged.** Mostly rule semantics — the unglamorous question of when a
fix is safe enough to apply without asking.

- [#27643](https://github.com/astral-sh/ruff/pull/27643) — skip `FURB101`/`FURB103` when the argument to `open` is a file descriptor
- [#26813](https://github.com/astral-sh/ruff/pull/26813) — NFKC-normalize keyword names in the `C408` fix
- [#26033](https://github.com/astral-sh/ruff/pull/26033) — mark the `EXE004` fix as unsafe
- [#25086](https://github.com/astral-sh/ruff/pull/25086) — mark the `PTH101` fix unsafe when the first argument is an `int`-annotated class attribute

### [swc-project/swc](https://github.com/swc-project/swc) — JavaScript/TypeScript compiler, in Rust
**6 opened · 5 merged · 1 in review.** Minifier and renamer: optimizations that are
correct in general and wrong in one corner, usually involving scope.

- [#12101](https://github.com/swc-project/swc/pull/12101) *(in review)* — treat const variable references as enum constants
- [#12029](https://github.com/swc-project/swc/pull/12029) — preserve top-level declarations referenced only by direct `eval`
- [#11963](https://github.com/swc-project/swc/pull/11963) — eliminate unused classes with cyclic references
- [#11913](https://github.com/swc-project/swc/pull/11913) — avoid duplicate mangled names across `eval` scope boundaries
- [#11839](https://github.com/swc-project/swc/pull/11839) — avoid mangled property names that collide with existing ones

### [coredns/coredns](https://github.com/coredns/coredns) — DNS server, in Go
**3 opened · 2 merged · 1 in review.** The cache and file plugins, and the reason I
write Go at all.

- [#8419](https://github.com/coredns/coredns/pull/8419) *(in review)* — stop setting `AA` on answers served from cache
- [#8286](https://github.com/coredns/coredns/pull/8286) — resolve each additional-section target only once
- [#8214](https://github.com/coredns/coredns/pull/8214) — regression test for the `AD` bit not partitioning the cache

---

## Things I built to learn

**Vanguard** — a Rust workspace where the pieces share one ABI (`shared-ipc`) and one
OpenTelemetry trace across process boundaries.

- [aegis-proxy](https://github.com/baltasarblanco/aegis-proxy) — L4 TCP proxy, `io_uring`, thread-per-core, zero-alloc hot path
- [chronos_lsm](https://github.com/baltasarblanco/chronos_lsm) — LSM-tree key-value store with WAL, bloom filters and compaction
- [celer_mock](https://github.com/baltasarblanco/celer_mock) — cross-process event consumer over `memfd` + `SCM_RIGHTS`
- [vanguard-infrastructure](https://github.com/baltasarblanco/vanguard-infrastructure) — workspace root and the RYŪ demo frontend

Benchmarks in those repos are single-machine and loopback. They're there to show the
shape of the thing, not to be compared against anything shipping.

**[bifrost-api](https://github.com/baltasarblanco/bifrost-api)** — B2B booking API in
FastAPI and PostgreSQL, with pessimistic locking and LLM intent extraction.

---

Buenos Aires, Argentina · [LinkedIn](https://www.linkedin.com/in/baltasarblanco/) · baltasarblanco.dev@gmail.com
