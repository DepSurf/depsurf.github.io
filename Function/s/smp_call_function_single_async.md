# Function: <code>smp_call_function_single_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908704,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:327",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908704,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int smp_call_function_single_async(int cpu, struct call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938448,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:311",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938448,
      "name": "smp_call_function_single_async",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969200,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:315",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969200,
      "name": "smp_call_function_single_async",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, struct call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974608,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:324",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:__blk_mq_complete_request",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974608,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021120,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:326",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:__blk_mq_complete_request",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021120,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075184,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:326",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075184,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122496,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:326",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122496,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167936,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167936,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215872,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215872,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285680,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:411",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_force_complete_rq",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285680,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269200,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:545",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269200,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int smp_call_function_single_async(int cpu, struct __call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273840,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:787",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273840,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int smp_call_function_single_async(int cpu, struct __call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425952,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:789",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425952,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int smp_call_function_single_async(int cpu, struct __call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649056,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:808",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649056,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int smp_call_function_single_async(int cpu, struct __call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916176,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:807",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916176,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int smp_call_function_single_async(int cpu, struct __call_single_data * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003888,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:661",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003888,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100048,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:681",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100048,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491454072,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491454072,
      "name": "smp_call_function_single_async",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225440220,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_poke_others",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225440220,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284404192,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284404192,
      "name": "smp_call_function_single_async",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271910628,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271910628,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184672,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184672,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132160,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132160,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176144,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176144,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smp_call_function_single_async(int cpu, call_single_data_t * csd)
```

```json
{
  "name": "smp_call_function_single_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228272,
      "name": "smp_call_function_single_async",
      "external": true,
      "loc": "kernel/smp.c:335",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hrtick_start",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "net/core/dev.c:net_rps_send_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228272,
      "name": "smp_call_function_single_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct call_single_data * csd</code> ➡️ <code>call_single_data_t * csd</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>call_single_data_t * csd</code> ➡️ <code>struct __call_single_data * csd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __call_single_data * csd</code> ➡️ <code>call_single_data_t * csd</code>
</li>
</ul>
</details>
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
