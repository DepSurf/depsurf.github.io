# Function: <code>perf_event__output_id_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580388506,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:5231",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_log_lost_samples"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429856,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580456225,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:5548",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503392,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580518641,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:5646",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567488,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550873,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:5738",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597760,
      "name": "perf_event__output_id_sample",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580631108,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:5688",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678016,
      "name": "perf_event__output_id_sample",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765225,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6049",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809792,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832841,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6058",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876432,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928649,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6136",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972704,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580982281,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026832,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581171138,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6635",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208496,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581211546,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6713",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250880,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226565,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6824",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267408,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468149,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6948",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508336,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581862962,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6853",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855056,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582290130,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:7110",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281600,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439410,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:7119",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482576,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607554,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:7192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651248,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492329952,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492379344,
      "name": "perf_event__output_id_sample",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226211716,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226265276,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285575828,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285636304,
      "name": "perf_event__output_id_sample",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272455204,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272491656,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580951081,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995680,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580897145,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941872,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580942329,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986880,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void perf_event__output_id_sample(struct perf_event * event, struct perf_output_handle * handle, struct perf_sample_data * sample)
```

```json
{
  "name": "perf_event__output_id_sample",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581003913,
      "name": "perf_event__output_id_sample",
      "external": true,
      "loc": "kernel/events/core.c:6252",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "kernel/events/core.c:perf_event_read_event"
      ],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047824,
      "name": "perf_event__output_id_sample",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
