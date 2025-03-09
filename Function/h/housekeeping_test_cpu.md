# Function: <code>housekeeping_test_cpu</code>

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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746272,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:47",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746272,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780640,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:42",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780640,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823520,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:42",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823520,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851728,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851728,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900224,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900224,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943376,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943376,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931632,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931632,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939472,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939472,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064496,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064496,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool housekeeping_test_cpu(int cpu, enum hk_type type)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:73",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879872,
      "name": "housekeeping_test_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580140784,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool housekeeping_test_cpu(int cpu, enum hk_type type)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:73",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595981664,
      "name": "housekeeping_test_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580315920,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580390410,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:73",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596500035,
      "name": "housekeeping_test_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580390336,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580446538,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:73",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "fs/buffer.c:lookup_bh_lru",
        "fs/buffer.c:lookup_bh_lru",
        "fs/buffer.c:bh_lru_install",
        "fs/buffer.c:bh_lru_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597397397,
      "name": "housekeeping_test_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580446464,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491099432,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099432,
      "name": "housekeeping_test_cpu",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225102708,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225102708,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283989584,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989584,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271681532,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271681532,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872336,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872336,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807344,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807344,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860496,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860496,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_test_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905872,
      "name": "housekeeping_test_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:57",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905872,
      "name": "housekeeping_test_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
