# Baltasar Blanco

Hi! I'm a backend developer and student from Buenos Aires, Argentina. Before
software I spent seven years in high-end audio engineering — I learned mastering
working alongside people with Latin Grammys on their shelves. These days I'm
studying computer science, headed toward research and eventually a PhD. In
parallel, I contribute PRs to three open source projects I care about: it's how
I get real-world experience at a pace I can sustain. That work is below, along
with some personal projects you might find interesting.

Rust · Python · Go

---

## Where my patches go

Three codebases, on purpose. The fifth patch to a project you understand is worth
more than the first patch to five you don't, so I'd rather keep going back to the
same three than collect logos.

The pattern is consistent enough to describe: I look for the case where an
optimization or a rule is correct in general and wrong in one corner — usually
something about scope, aliasing, or an assumption that stops holding at a
boundary. Small diffs, a test that fails without the change, and a maintainer
willing to argue with me about it.

### [astral-sh/ruff](https://github.com/astral-sh/ruff) — Python linter and formatter, in Rust
Rule semantics, mostly: the unglamorous question of when a fix is safe enough to
apply without asking first. One example — [skipping `FURB101`/`FURB103` when the
argument to `open` is a file descriptor](https://github.com/astral-sh/ruff/pull/27643).

→ [everything I've had merged here](https://github.com/search?q=repo%3Aastral-sh%2Fruff+is%3Apr+author%3Abaltasarblanco+is%3Amerged&type=pullrequests)

### [swc-project/swc](https://github.com/swc-project/swc) — JavaScript/TypeScript compiler, in Rust
Minifier and renamer. One example — [preserving top-level declarations that are
only referenced from inside a direct `eval`](https://github.com/swc-project/swc/pull/12029),
which the dead-code pass was happy to delete.

→ [everything I've had merged here](https://github.com/search?q=repo%3Aswc-project%2Fswc+is%3Apr+author%3Abaltasarblanco+is%3Amerged&type=pullrequests)

### [coredns/coredns](https://github.com/coredns/coredns) — DNS server, in Go
The cache and file plugins, and the reason I write Go at all. One example —
[resolving each additional-section target only once](https://github.com/coredns/coredns/pull/8286).

→ [everything I've had merged here](https://github.com/search?q=repo%3Acoredns%2Fcoredns+is%3Apr+author%3Abaltasarblanco+is%3Amerged&type=pullrequests)

Anything currently in flight is [here](https://github.com/search?q=is%3Apr+author%3Abaltasarblanco+is%3Aopen&type=pullrequests).

---

## Things I built to learn

**Vanguard** — a Rust workspace where the pieces share one ABI (`shared-ipc`) and
one OpenTelemetry trace across process boundaries.

- [aegis-proxy](https://github.com/baltasarblanco/aegis-proxy) — L4 TCP proxy, `io_uring`, thread-per-core, zero-alloc hot path
- [chronos_lsm](https://github.com/baltasarblanco/chronos_lsm) — LSM-tree key-value store with WAL, bloom filters and compaction
- [celer_mock](https://github.com/baltasarblanco/celer_mock) — cross-process event consumer over `memfd` + `SCM_RIGHTS`
- [vanguard-infrastructure](https://github.com/baltasarblanco/vanguard-infrastructure) — workspace root and the RYŪ demo frontend

Benchmarks in those repos are single-machine and loopback — there to show the
shape of the thing, not to be compared against anything shipping.

**[bifrost-api](https://github.com/baltasarblanco/bifrost-api)** — B2B booking API
in FastAPI and PostgreSQL, with pessimistic locking and LLM intent extraction.

---

Buenos Aires, Argentina · [LinkedIn](https://www.linkedin.com/in/baltasarblanco/) · baltasarblanco.dev@gmail.com
