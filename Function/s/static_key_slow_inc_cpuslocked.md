# Function: <code>static_key_slow_inc_cpuslocked</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580714864,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:82",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/jump_label.c:static_key_slow_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714864,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847312,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:83",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/jump_label.c:static_key_slow_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847312,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916176,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:101",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916176,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014272,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014272,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069568,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069568,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250496,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250496,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292576,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292576,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310208,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310208,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188951,
      "name": "static_key_slow_inc_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581555312,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964052,
      "name": "static_key_slow_inc_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581906784,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341232,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:148",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341232,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543600,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:148",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543600,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712832,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:148",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712832,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492430560,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430560,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285700112,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285700112,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038416,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038416,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984496,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984496,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029616,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029616,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void static_key_slow_inc_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091040,
      "name": "static_key_slow_inc_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:116",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/jump_label.c:static_key_slow_inc",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091040,
      "name": "static_key_slow_inc_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key * key)
```
</details>
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
