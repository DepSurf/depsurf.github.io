# Function: <code>perf_event_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435648,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:6473",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435648,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508720,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7067",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508720,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572848,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7180",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572848,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603456,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7403",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603456,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684192,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7400",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684192,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816192,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7782",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816192,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882848,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:7791",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882848,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980064,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8095",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980064,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034192,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034192,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214176,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8761",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214176,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257168,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9027",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257168,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275184,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275184,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516336,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9276",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516336,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863264,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863264,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290480,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9536",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290480,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491184,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9565",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491184,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659632,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:9635",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659632,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492386128,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492386128,
      "name": "perf_event_overflow",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226273420,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226273420,
      "name": "perf_event_overflow",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285645536,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/core-book3s.c:record_and_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285645536,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272497764,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272497764,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003040,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003040,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949200,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949200,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994240,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994240,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int perf_event_overflow(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055296,
      "name": "perf_event_overflow",
      "external": true,
      "loc": "kernel/events/core.c:8211",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055296,
      "name": "perf_event_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
