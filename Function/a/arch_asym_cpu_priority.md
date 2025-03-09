# Function: <code>arch_asym_cpu_priority</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277632,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:180",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277632,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274160,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:178",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274160,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291136,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:178",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291136,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303072,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:177",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303072,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327744,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:177",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327744,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343104,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343104,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347280,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347280,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376992,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:init_sched_groups_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376992,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579375664,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:init_sched_groups_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375664,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379280,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379280,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440784,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440784,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510800,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510800,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579609664,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:170",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609664,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622432,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:161",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622432,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579651488,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:160",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:need_active_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sd_pick_busiest",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/build_utility.c:init_sched_groups_capacity",
        "kernel/sched/build_utility.c:init_sched_groups_capacity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651488,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490976752,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "kernel/sched/fair.c:93",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490976752,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 40
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224989036,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "kernel/sched/fair.c:93",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224989036,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283842944,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "kernel/sched/fair.c:93",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283842944,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 20
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271593436,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "kernel/sched/fair.c:93",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271593436,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 36
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343184,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343184,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275456,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275456,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343104,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343104,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int arch_asym_cpu_priority(int cpu)
```

```json
{
  "name": "arch_asym_cpu_priority",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351552,
      "name": "arch_asym_cpu_priority",
      "external": true,
      "loc": "arch/x86/kernel/itmt.c:171",
      "file": "arch/x86/kernel/itmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351552,
      "name": "arch_asym_cpu_priority",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int arch_asym_cpu_priority(int cpu)
```
</details>
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
