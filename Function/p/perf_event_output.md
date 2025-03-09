# Function: <code>perf_event_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432368,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:5599",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/events/core.c:__perf_event_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432368,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506464,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:5984",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506464,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570528,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6082",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570528,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600736,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6178",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600736,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681456,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6166",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681456,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813536,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6540",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813536,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880192,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6549",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880192,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976400,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976400,
      "name": "perf_event_output",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030528,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030528,
      "name": "perf_event_output",
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211888,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211888,
      "name": "perf_event_output",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254704,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7373",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254704,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271664,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7484",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271664,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512640,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7608",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512640,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859328,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7513",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859328,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286400,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7802",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286400,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487504,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7830",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487504,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656224,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:7911",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656224,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492382360,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492382360,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226269524,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226269524,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285640512,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285640512,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272494904,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272494904,
      "name": "perf_event_output",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999376,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999376,
      "name": "perf_event_output",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945568,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945568,
      "name": "perf_event_output",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990576,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990576,
      "name": "perf_event_output",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int perf_event_output(struct perf_event * event, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "perf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051584,
      "name": "perf_event_output",
      "external": true,
      "loc": "kernel/events/core.c:6746",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051584,
      "name": "perf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
