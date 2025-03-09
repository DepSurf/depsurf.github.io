# Function: <code>gen_new_estimator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct gnet_stats_rate_est64 * rate_est, spinlock_t * stats_lock, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586248592,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:207",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248592,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct gnet_stats_rate_est64 * rate_est, spinlock_t * stats_lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672752,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:212",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672752,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * stats_lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586857360,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:127",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857360,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * stats_lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980576,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:127",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980576,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * stats_lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587478784,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:128",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587478784,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * stats_lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587783808,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:128",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783808,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587916800,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:128",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916800,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225168,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225168,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429792,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429792,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589297040,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297040,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589295600,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589295600,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589189488,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189488,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695268,
      "name": "gen_new_estimator.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589911120,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync * bstats, struct gnet_stats_basic_sync * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, bool running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:130",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580815,
      "name": "gen_new_estimator.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591441744,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync * bstats, struct gnet_stats_basic_sync * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, bool running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:130",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596322703,
      "name": "gen_new_estimator.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593208640,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync * bstats, struct gnet_stats_basic_sync * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, bool running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:130",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596852711,
      "name": "gen_new_estimator.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593668880,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync * bstats, struct gnet_stats_basic_sync * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, bool running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:130",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597777676,
      "name": "gen_new_estimator.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594446928,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501950504,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501950504,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234706144,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234706144,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295372240,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295372240,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278254082,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278254082,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588036576,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588036576,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749664,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749664,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368352,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368352,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu_bstats, struct net_rate_estimator * * rate_est, spinlock_t * lock, seqcount_t * running, struct nlattr * opt)
```

```json
{
  "name": "gen_new_estimator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503904,
      "name": "gen_new_estimator",
      "external": true,
      "loc": "net/core/gen_estimator.c:124",
      "file": "net/core/gen_estimator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_estimator.c:gen_replace_estimator",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503904,
      "name": "gen_new_estimator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>seqcount_t * running</code>
</li>
<li>
<b>Param reordered. </b>
<code>bstats, cpu_bstats, rate_est, stats_lock, opt</code> ➡️ <code>bstats, cpu_bstats, rate_est, stats_lock, running, opt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_rate_est64 * rate_est</code> ➡️ <code>struct net_rate_estimator * * rate_est</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>spinlock_t * lock</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t * stats_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_packed * bstats</code> ➡️ <code>struct gnet_stats_basic_sync * bstats</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_cpu * cpu_bstats</code> ➡️ <code>struct gnet_stats_basic_sync * cpu_bstats</code>
</li>
<li>
<b>Param type changed. </b>
<code>seqcount_t * running</code> ➡️ <code>bool running</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
