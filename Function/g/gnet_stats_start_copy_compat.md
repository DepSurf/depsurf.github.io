# Function: <code>gnet_stats_start_copy_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246416,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:61",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246416,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670432,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670432,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855392,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855392,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978848,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978848,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587477056,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477056,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587782816,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782816,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587915136,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:63",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915136,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588223168,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223168,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588427792,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427792,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589295616,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589295616,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589294192,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294192,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188096,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188096,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589909648,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589909648,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591439984,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591439984,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593206976,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593206976,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593667216,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593667216,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594445264,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594445264,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501949048,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501949048,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234703596,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234703596,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295369232,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295369232,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278252266,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278252266,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588034576,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588034576,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587747664,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747664,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588366352,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366352,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff * skb, int type, int tc_stats_type, int xstats_type, spinlock_t * lock, struct gnet_dump * d, int padattr)
```

```json
{
  "name": "gnet_stats_start_copy_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588501984,
      "name": "gnet_stats_start_copy_compat",
      "external": true,
      "loc": "net/core/gen_stats.c:59",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_start_copy",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tcf_action_copy_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501984,
      "name": "gnet_stats_start_copy_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
<code>int padattr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
