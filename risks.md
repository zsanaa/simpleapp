### Risks

```code

npm audit

                       === npm audit security report ===

┌──────────────────────────────────────────────────────────────────────────────┐
│                                Manual Review                                 │
│            Some vulnerabilities require your attention to resolve            │
│                                                                              │
│         Visit https://go.npm.me/audit-guide for additional guidance          │
└──────────────────────────────────────────────────────────────────────────────┘
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │ Prototype Pollution                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ lodash                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Patched in    │ >=4.17.11                                                    │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ last-commit                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ last-commit > ggit > lodash                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/782                             │
└───────────────┴──────────────────────────────────────────────────────────────┘
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Prototype Pollution                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ lodash                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Patched in    │ >=4.17.5                                                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ last-commit                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ last-commit > ggit > lodash                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/577                             │
└───────────────┴──────────────────────────────────────────────────────────────┘
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ debug                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Patched in    │ >= 2.6.9 < 3.0.0 || >= 3.1.0                                 │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ last-commit                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ last-commit > ggit > debug                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/534                             │
└───────────────┴──────────────────────────────────────────────────────────────┘
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Regular Expression Denial of Service                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ moment                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Patched in    │ >=2.19.3                                                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ last-commit                                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ last-commit > ggit > moment                                  │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/532                             │
└───────────────┴──────────────────────────────────────────────────────────────┘
found 4 vulnerabilities (3 low, 1 moderate) in 562 scanned packages
  4 vulnerabilities require manual review. See the full report for details.
  
 ```
