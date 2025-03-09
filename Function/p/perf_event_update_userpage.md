# Function: <code>perf_event_update_userpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417328,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:4445",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417328,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490400,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:4735",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490400,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553808,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:4832",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553808,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584736,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:4924",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584736,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664704,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:4874",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664704,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580796208,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5230",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796208,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862768,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5239",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862768,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959504,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5285",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959504,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011712,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011712,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191968,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5649",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191968,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233488,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5728",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233488,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249536,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5812",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249536,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581484528,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5920",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484528,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829792,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5818",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829792,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257248,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:6036",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257248,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457840,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:6036",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_del",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457840,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626656,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:6109",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_context_sched_out",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_del",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626656,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492364768,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "drivers/perf/arm-cci.c:cci_pmu_del",
        "drivers/perf/arm-cci.c:cci_pmu_del",
        "drivers/perf/arm-cci.c:cci_pmu_add",
        "drivers/perf/arm_pmu.c:armpmu_add",
        "drivers/perf/arm_pmu.c:armpmu_del",
        "drivers/perf/arm_pmu.c:armpmu_event_set_period",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_del",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_start",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_del",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_del",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_del",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_add",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_del",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_add",
        "drivers/perf/xgene_pmu.c:xgene_perf_del",
        "drivers/perf/xgene_pmu.c:xgene_perf_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492364768,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226249344,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "drivers/perf/arm-cci.c:cci_pmu_del",
        "drivers/perf/arm-cci.c:cci_pmu_add",
        "drivers/perf/arm_pmu.c:armpmu_add",
        "drivers/perf/arm_pmu.c:armpmu_del",
        "drivers/perf/arm_pmu.c:armpmu_event_set_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226249344,
      "name": "perf_event_update_userpage",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285617056,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/core-book3s.c:record_and_restart",
        "arch/powerpc/perf/core-book3s.c:record_and_restart",
        "arch/powerpc/perf/core-book3s.c:record_and_restart",
        "arch/powerpc/perf/core-book3s.c:record_and_restart",
        "arch/powerpc/perf/core-book3s.c:power_pmu_del",
        "arch/powerpc/perf/core-book3s.c:power_pmu_enable",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285617056,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272488884,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:riscv_pmu_del",
        "arch/riscv/kernel/perf_event.c:riscv_pmu_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272488884,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980560,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980560,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926720,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926720,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971760,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971760,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void perf_event_update_userpage(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_userpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032560,
      "name": "perf_event_update_userpage",
      "external": true,
      "loc": "kernel/events/core.c:5380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_start",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_del",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_del",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032560,
      "name": "perf_event_update_userpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
