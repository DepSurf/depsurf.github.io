# Function: <code>cgroup_taskset_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_taskset_migrate(struct cgroup_taskset * tset, struct cgroup * dst_cgrp)
```

```json
{
  "name": "cgroup_taskset_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986400,
      "name": "cgroup_taskset_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2486",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_migrate",
        "kernel/cgroup.c:cgroup_update_dfl_csses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986400,
      "name": "cgroup_taskset_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int cgroup_taskset_migrate(struct cgroup_taskset * tset, struct cgroup_root * root)
```

```json
{
  "name": "cgroup_taskset_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015760,
      "name": "cgroup_taskset_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2527",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015760,
      "name": "cgroup_taskset_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
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
int cgroup_taskset_migrate(struct cgroup_taskset * tset, struct cgroup_root * root)
```

```json
{
  "name": "cgroup_taskset_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049344,
      "name": "cgroup_taskset_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2532",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049344,
      "name": "cgroup_taskset_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_root * root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup * dst_cgrp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int cgroup_taskset_migrate(struct cgroup_taskset * tset, struct cgroup_root * root)
```
</details>
</li>
</ul>
