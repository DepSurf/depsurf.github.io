# Function: <code>cgroup_rstat_flush_hold</code>

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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172032,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:232",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172032,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219920,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:232",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219920,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268832,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268832,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316992,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316992,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580389262,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:225",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388688,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580376222,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:224",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375648,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580379166,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:231",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378576,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541086,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:231",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540400,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738614,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:237",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737728,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015088,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:267",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014064,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103504,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:251",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102512,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581201312,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:290",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200320,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491571888,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491571888,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225535508,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225535508,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284550640,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284550640,
      "name": "cgroup_rstat_flush_hold",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271983592,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271983592,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285792,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285792,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233184,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233184,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277040,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277040,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331390,
      "name": "cgroup_rstat_flush_hold",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:235",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330880,
      "name": "cgroup_rstat_flush_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void cgroup_rstat_flush_hold(struct cgroup * cgrp)
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
