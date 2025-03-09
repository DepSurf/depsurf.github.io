# Function: <code>dl_clear_root_domain</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846384,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846384,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885280,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2314",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885280,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878576,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2427",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878576,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887600,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2409",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887600,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000576,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2421",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000576,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130944,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2574",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130944,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305152,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2574",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305152,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580372640,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2566",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372640,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580430752,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2663",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430752,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491035664,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491035664,
      "name": "dl_clear_root_domain",
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225045180,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225045180,
      "name": "dl_clear_root_domain",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283914416,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283914416,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271637494,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271637494,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818736,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818736,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753344,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753344,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806752,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806752,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void dl_clear_root_domain(struct root_domain * rd)
```

```json
{
  "name": "dl_clear_root_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851728,
      "name": "dl_clear_root_domain",
      "external": true,
      "loc": "kernel/sched/deadline.c:2315",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851728,
      "name": "dl_clear_root_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void dl_clear_root_domain(struct root_domain * rd)
```
</details>
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
