# Function: <code>cgroup_rstat_flush</code>

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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580171888,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:199",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171888,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219776,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:199",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219776,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268688,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268688,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316848,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316848,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580388917,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:192",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388544,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580375885,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:191",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375504,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580378819,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:198",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378432,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580540686,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:198",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540256,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738037,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:204",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737568,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014430,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:234",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013872,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102432,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:233",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102432,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200240,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:272",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200240,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491571536,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491571536,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225535348,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225535348,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284550336,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284550336,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271983368,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271983368,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285648,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285648,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233056,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233056,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276896,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276896,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void cgroup_rstat_flush(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330752,
      "name": "cgroup_rstat_flush",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:202",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330752,
      "name": "cgroup_rstat_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void cgroup_rstat_flush(struct cgroup * cgrp)
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
