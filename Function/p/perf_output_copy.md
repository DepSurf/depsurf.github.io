# Function: <code>perf_output_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580439791,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:206",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_begin"
      ],
      "caller_func": [
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_log_lost_samples"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439968,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512720,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:253",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512720,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576704,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:253",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576704,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607328,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:253",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607328,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688336,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:253",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688336,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820368,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:254",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820368,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887040,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:254",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887040,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984528,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984528,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038512,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038512,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219214,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217136,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581261854,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:287",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259792,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581280608,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:287",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278544,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524512,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:287",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522416,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581872256,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:287",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870064,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582299973,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:290",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299600,
      "name": "perf_output_copy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582500757,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:290",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500384,
      "name": "perf_output_copy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582669269,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:291",
      "file": "kernel/events/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668896,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492392624,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492392624,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226278876,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
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
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226278876,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285653376,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285653376,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272502520,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272502520,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007360,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007360,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953488,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953488,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580998560,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998560,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int perf_output_copy(struct perf_output_handle * handle, const void * buf, unsigned int len)
```

```json
{
  "name": "perf_output_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059664,
      "name": "perf_output_copy",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:285",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:__perf_event__output_id_sample",
        "kernel/events/core.c:perf_output_sample_regs",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059664,
      "name": "perf_output_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
