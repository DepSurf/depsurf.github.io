# Function: <code>partition_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565216,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7159",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cpuset.c:cpuset_update_active_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565216,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575456,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7094",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cpuset.c:cpuset_update_active_cpus",
        "kernel/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575456,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 895
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601536,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7215",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cpuset.c:cpuset_update_active_cpus",
        "kernel/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601536,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686032,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1843",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cgroup/cpuset.c:cpuset_update_active_cpus",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686032,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716768,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1858",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716768,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748480,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748480,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788512,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2130",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788512,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816208,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2154",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816208,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864976,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864976,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905984,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2312",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905984,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900912,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2370",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900912,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909984,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2394",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909984,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028960,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2527",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028960,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202144,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2634",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202144,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580393216,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2641",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393216,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461664,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2741",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461664,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521328,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2789",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521328,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491062928,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491062928,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225065468,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225065468,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283942176,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283942176,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271654626,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271654626,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837328,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837328,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771904,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771904,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825344,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825344,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void partition_sched_domains(int ndoms_new, cpumask_var_t * doms_new, struct sched_domain_attr * dattr_new)
```

```json
{
  "name": "partition_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870480,
      "name": "partition_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870480,
      "name": "partition_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
