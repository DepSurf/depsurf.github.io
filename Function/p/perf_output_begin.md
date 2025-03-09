# Function: <code>perf_output_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580439376,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:105",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_log_lost_samples"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439376,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513920,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:245",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513920,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577904,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:245",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577904,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608528,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:245",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608528,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689536,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:245",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689536,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821520,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:246",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821520,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888192,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:246",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888192,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985696,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985696,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039680,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039680,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218272,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218272,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260912,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:278",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260912,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279664,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:278",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279664,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581523552,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:278",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523552,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871328,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:278",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871328,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298928,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:281",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298928,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499712,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:281",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499712,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_sample_data * data, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668240,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:282",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668240,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492394072,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492394072,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226280400,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226280400,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285655392,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/imc-pmu.c:dump_trace_imc_data",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285655392,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272503542,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272503542,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008528,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008528,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954656,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954656,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999728,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999728,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int perf_output_begin(struct perf_output_handle * handle, struct perf_event * event, unsigned int size)
```

```json
{
  "name": "perf_output_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060880,
      "name": "perf_output_begin",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:277",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060880,
      "name": "perf_output_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_sample_data * data</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, event, size</code> ➡️ <code>handle, data, event, size</code>
</li>
</ul>
</details>
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
