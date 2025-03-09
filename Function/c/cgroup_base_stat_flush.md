# Function: <code>cgroup_base_stat_flush</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580171512,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:312",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580219400,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:312",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580268316,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580316476,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cgroup_base_stat_flush(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387664,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:313",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387664,
      "name": "cgroup_base_stat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void cgroup_base_stat_flush(struct cgroup * cgrp, int cpu)
```

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374432,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:312",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374432,
      "name": "cgroup_base_stat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580377824,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:317",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580539118,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:317",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736403,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:323",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581013146,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:359",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581101718,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:343",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581199300,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:382",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491571064,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225534560,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284549752,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271983118,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580285276,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580232684,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580276524,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_base_stat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580330343,
      "name": "cgroup_base_stat_flush",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:315",
      "file": "kernel/cgroup/rstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cgroup_base_stat_flush(struct cgroup * cgrp, int cpu)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void cgroup_base_stat_flush(struct cgroup * cgrp, int cpu)
```
</details>
</li>
</ul>
