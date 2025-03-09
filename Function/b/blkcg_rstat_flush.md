# Function: <code>blkcg_rstat_flush</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523888,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:1149",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523888,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633040,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:764",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633040,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660576,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:762",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660576,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585075312,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:788",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075312,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585802400,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:849",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802400,
      "name": "blkcg_rstat_flush.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071585803664,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586585792,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:861",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586585792,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842496,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:1034",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842496,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```

```json
{
  "name": "blkcg_rstat_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587119792,
      "name": "blkcg_rstat_flush",
      "external": false,
      "loc": "block/blk-cgroup.c:1047",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587119792,
      "name": "blkcg_rstat_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state * css, int cpu)
```
</details>
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
