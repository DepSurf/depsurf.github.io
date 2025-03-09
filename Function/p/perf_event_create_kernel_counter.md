# Function: <code>perf_event_create_kernel_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420992,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:8606",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420992,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580493648,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:9786",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493648,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557104,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_enable",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557104,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587760,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:10278",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_enable",
        "kernel/watchdog_hld.c:watchdog_nmi_enable",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587760,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667712,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:10310",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667712,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799296,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:10840",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799296,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865856,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:10883",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865856,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962688,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11234",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962688,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014896,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014896,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581194912,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11944",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194912,
      "name": "perf_event_create_kernel_counter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071581195264,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581236832,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12228",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236832,
      "name": "perf_event_create_kernel_counter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581237184,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581252896,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12418",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252896,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581496800,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12539",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496800,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581842832,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12509",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842832,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582269584,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12708",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269584,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470432,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12748",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470432,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582639184,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:12832",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639184,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492367896,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/pmu.c:kvm_pmu_create_perf_event",
        "virt/kvm/arm/pmu.c:kvm_pmu_create_perf_event",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492367896,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226252752,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226252752,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285621360,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285621360,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272475818,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272475818,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983744,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983744,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580929968,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929968,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580974944,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974944,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct perf_event * perf_event_create_kernel_counter(struct perf_event_attr * attr, int cpu, struct task_struct * task, perf_overflow_handler_t overflow_handler, void * context)
```

```json
{
  "name": "perf_event_create_kernel_counter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035776,
      "name": "perf_event_create_kernel_counter",
      "external": true,
      "loc": "kernel/events/core.c:11341",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_event_create",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035776,
      "name": "perf_event_create_kernel_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
