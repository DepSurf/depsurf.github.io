# Function: <code>static_key_slow_dec_cpuslocked</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715072,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:232",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715072,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847520,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:233",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847520,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916384,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:256",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916384,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014464,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014464,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069760,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069760,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250688,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250688,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292768,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292768,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310400,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310400,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188972,
      "name": "static_key_slow_dec_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581555520,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964073,
      "name": "static_key_slow_dec_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581907008,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:302",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023698,
      "name": "static_key_slow_dec_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582341456,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:302",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545984,
      "name": "static_key_slow_dec_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582543824,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:302",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449763,
      "name": "static_key_slow_dec_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582713056,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492430864,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430864,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285700512,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285700512,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038608,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038608,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984688,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984688,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029808,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029808,
      "name": "static_key_slow_dec_cpuslocked",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091232,
      "name": "static_key_slow_dec_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:274",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091232,
      "name": "static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key * key)
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
void static_key_slow_dec_cpuslocked(struct static_key * key)
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
