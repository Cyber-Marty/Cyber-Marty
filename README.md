# PipesVisuals

Python tooling, quantitative research, and AI evaluation.

I contribute bug fixes to Python tools and quantitative-finance libraries, with a focus on numerical correctness, reproducibility, and regression tests.

[Projects](#projects) | [Merged contributions](#merged-contributions) | [Open contributions](#open-contributions) | [All pull requests](https://github.com/search?q=is%3Apr+author%3ACyber-Marty&type=pullrequests)

## Merged contributions

Bug fixes accepted upstream, most recent first.

| Project                                                                   | My contribution                                                      | Merged PR                                                          |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [skfolio](https://github.com/skfolio/skfolio)                             | Preserve failed-period observation weights                           | [#477](https://github.com/skfolio/skfolio/pull/477)                |
| [skfolio](https://github.com/skfolio/skfolio)                             | Preserve zero exposure for all-cash periods                          | [#473](https://github.com/skfolio/skfolio/pull/473)                |
| [pydash](https://github.com/dgilland/pydash)                              | Keep partial iteratee args out of keyword-bound slots                | [#448](https://github.com/dgilland/pydash/pull/448)                |
| [jc](https://github.com/kellyjonbrazil/jc)                                | Handle Windows CRLF input while preserving POSIX filename characters | [#898](https://github.com/kellyjonbrazil/jc/pull/898)              |
| [nox](https://github.com/wntrblm/nox)                                     | Honor usage requests before session filtering                        | [#1223](https://github.com/wntrblm/nox/pull/1223)                  |
| [parse](https://github.com/r1chardj0n3s/parse)                            | Fix pickle round-trips for timezone-aware results                    | [#275](https://github.com/r1chardj0n3s/parse/pull/275)             |
| [nox](https://github.com/wntrblm/nox)                                     | Keep reused parameter specs independent                              | [#1214](https://github.com/wntrblm/nox/pull/1214)                  |
| [pipx](https://github.com/pypa/pipx)                                      | Preserve extras on local archive installs                            | [#2174](https://github.com/pypa/pipx/pull/2174)                    |
| [skfolio](https://github.com/skfolio/skfolio)                             | Stabilize entropic risk calculations                                 | [#440](https://github.com/skfolio/skfolio/pull/440)                |
| [bt](https://github.com/pmorissette/bt)                                   | Fix cash-reserve position limits                                     | [#638](https://github.com/pmorissette/bt/pull/638)                 |
| [empyrical-reloaded](https://github.com/stefan-jansen/empyrical-reloaded) | Handle missing return pairs in batting averages                      | [#92](https://github.com/stefan-jansen/empyrical-reloaded/pull/92) |
| [ffn](https://github.com/pmorissette/ffn)                                 | Prevent recursion in low-precision weight limits                     | [#425](https://github.com/pmorissette/ffn/pull/425)                |

[All merged pull requests](https://github.com/search?q=is%3Apr+is%3Amerged+author%3ACyber-Marty&type=pullrequests)

## Projects

**[SkillArena](https://github.com/Cyber-Marty/SkillArena)**  
A local evaluation harness for comparing agent skills on frozen tasks, with auditable run evidence. [View the report](https://cyber-marty.github.io/SkillArena/).

**[engineering-skills](https://github.com/Cyber-Marty/engineering-skills)**  
Reusable agent skills and engineering notes from open-source work.

## Open contributions

Selected pull requests; these changes have not been merged.

**Quantitative research**  
[arch #1025](https://github.com/bashtage/arch/pull/1025) — Return SkewStudent partial moments when lambda is 1.  
[Qlib](https://github.com/microsoft/qlib/pulls?q=is%3Apr+is%3Aopen+author%3ACyber-Marty) / [QuantStats](https://github.com/ranaroussi/quantstats/pull/576) / [VeighNa](https://github.com/vnpy/vnpy/pull/3813)

[All open pull requests](https://github.com/search?q=is%3Apr+is%3Aopen+author%3ACyber-Marty&type=pullrequests)

## How I work

- Reproduce the issue before proposing a fix.
- Explain the cause and keep the patch focused.
- Add regression tests and respond to review.
