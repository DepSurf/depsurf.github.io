# Function: <code>partition_sched_domains_locked</code>

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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864128,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864128,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2206",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907348,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579904784,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2264",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284367,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579899696,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2291",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591227387,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579908784,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2421",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592113960,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071580027600,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2528",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593891039,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071580200656,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1477
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2535",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983242,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071580391664,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1534
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2635",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501612,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071580460016,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1623
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2683",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399298,
      "name": "partition_sched_domains_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071580519664,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1645
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491061952,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491061952,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225064336,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225064336,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283940976,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283940976,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1192
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271653710,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271653710,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836480,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836480,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771056,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771056,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824496,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824496,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869616,
      "name": "partition_sched_domains_locked",
      "external": true,
      "loc": "kernel/sched/topology.c:2221",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869616,
      "name": "partition_sched_domains_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
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
