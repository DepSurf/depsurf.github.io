# Function: <code>cgroup_rstat_updated</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170992,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:24",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170992,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218880,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:24",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218880,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267840,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267840,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316000,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316000,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387472,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "block/blk-core.c:blkcg_bio_issue_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387472,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375312,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375312,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378224,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378224,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539792,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539792,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737088,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737088,
      "name": "cgroup_rstat_updated",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012208,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:29",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012208,
      "name": "cgroup_rstat_updated",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100784,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:29",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100784,
      "name": "cgroup_rstat_updated",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198176,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:29",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "block/blk-cgroup.c:blk_cgroup_bio_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198176,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491570376,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491570376,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225534056,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225534056,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284549072,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284549072,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271982512,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271982512,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284800,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284800,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232208,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232208,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276048,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276048,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_rstat_updated",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329872,
      "name": "cgroup_rstat_updated",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:25",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329872,
      "name": "cgroup_rstat_updated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void cgroup_rstat_updated(struct cgroup * cgrp, int cpu)
```
</details>
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
