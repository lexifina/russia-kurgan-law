<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Kurgan Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:42 UTC, Kurgan Oblast: Official Internet Portal of Legal Information (region45): 10 addresses read; 3 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Kurgan Oblast: Official Internet Portal of Legal Information (region45)](http://publication.pravo.gov.ru/documents/block/region45) | `zakony-<year>/` | daily | 2026-11-28 05:42 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:41](checks/2026-11.md#ru-pravo-kurgan-20261128t054128z) | pravo-kurgan | 10 | 3 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-kurgan-law/compare/1b05caa07f8b...eab1f737f00a) |
| [2026-11-27 05:32](checks/2026-11.md#ru-pravo-kurgan-20261127t053255z) | pravo-kurgan | 10 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-kurgan-law/compare/8b4fd95421d4...2382ceeb02fc) |
| [2026-11-26 05:38](checks/2026-11.md#ru-pravo-kurgan-20261126t053806z) | pravo-kurgan | 10 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-kurgan-law/compare/118c819a212e...04df8fde6c11) |
| [2026-11-25 06:11](checks/2026-11.md#ru-pravo-kurgan-20261125t061100z) | pravo-kurgan | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:07](checks/2026-11.md#ru-pravo-kurgan-20261124t140736z) | pravo-kurgan | 10 | 0 | 0 | 0 | 0 (0) | no change | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
