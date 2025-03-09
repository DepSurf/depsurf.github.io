# Function: <code>perf_event_header__init_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580388404,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:5199",
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
      "addr": 18446744071580429824,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580456168,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:5516",
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
      "addr": 18446744071580503360,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580518584,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:5614",
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
      "addr": 18446744071580567456,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550804,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:5706",
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
      "addr": 18446744071580597728,
      "name": "perf_event_header__init_id",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580631039,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:5656",
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
      "addr": 18446744071580677984,
      "name": "perf_event_header__init_id",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765174,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6017",
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
      "addr": 18446744071580809760,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832790,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6026",
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
      "addr": 18446744071580876400,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928598,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6104",
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
      "addr": 18446744071580972672,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580982230,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446744071581026800,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581171083,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6603",
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
      "addr": 18446744071581208464,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581211483,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6681",
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
      "addr": 18446744071581250848,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226502,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6792",
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
      "addr": 18446744071581267376,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468086,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6916",
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
      "addr": 18446744071581508304,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581862873,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6821",
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
      "addr": 18446744071581855008,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582290041,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:7078",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
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
      "addr": 18446744071582281520,
      "name": "perf_event_header__init_id",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439321,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:7085",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
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
      "addr": 18446744071582482480,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607465,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:7158",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_report_aux_output_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_bpf_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
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
      "addr": 18446744071582651152,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492329900,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446603336492379304,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226211672,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 3226265244,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285575740,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
        "arch/powerpc/perf/imc-pmu.c:dump_trace_imc_data",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285636272,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272455150,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446743936272491616,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580951030,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446744071580995648,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580897094,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446744071580941840,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580942278,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446744071580986848,
      "name": "perf_event_header__init_id",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "perf_event_header__init_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581003862,
      "name": "perf_event_header__init_id",
      "external": true,
      "loc": "kernel/events/core.c:6220",
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
      "addr": 18446744071581047792,
      "name": "perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
