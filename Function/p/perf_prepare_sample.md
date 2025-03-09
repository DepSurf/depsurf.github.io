# Function: <code>perf_prepare_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431520,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:5493",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431520,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505312,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:5820",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505312,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569408,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:5918",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569408,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599680,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6014",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599680,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679984,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:5999",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679984,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1203
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812032,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6373",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812032,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1233
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878672,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6382",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878672,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974864,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6460",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974864,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028992,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028992,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210544,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6979",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210544,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253264,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7150",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253264,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269936,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7261",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269936,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510928,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7385",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510928,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1413
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857648,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7290",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857648,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1287
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284448,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7557",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284448,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1516
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
void perf_prepare_sample(struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485056,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7575",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485056,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1435
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
void perf_prepare_sample(struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653760,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:7656",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653760,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492380888,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492380888,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226267888,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226267888,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285638528,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285638528,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1628
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272493546,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272493546,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997840,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997840,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580944032,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944032,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989040,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989040,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void perf_prepare_sample(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_prepare_sample",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049984,
      "name": "perf_prepare_sample",
      "external": true,
      "loc": "kernel/events/core.c:6576",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer",
        "kernel/events/core.c:perf_event_output",
        "kernel/events/core.c:perf_event_output_backward",
        "kernel/events/core.c:perf_event_output_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049984,
      "name": "perf_prepare_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct perf_event_header * header</code>
</li>
<li>
<b>Param reordered. </b>
<code>header, data, event, regs</code> ➡️ <code>data, event, regs</code>
</li>
</ul>
</details>
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
