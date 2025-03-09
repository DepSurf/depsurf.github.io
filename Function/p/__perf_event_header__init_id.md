# Function: <code>__perf_event_header__init_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388032,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5169",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_prepare_sample",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_log_lost_samples"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388032,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580455424,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5486",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455424,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517840,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5584",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_throttle",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_log_lost_samples",
        "kernel/events/core.c:perf_event_aux_event",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517840,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549840,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5676",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549840,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630080,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5626",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630080,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764496,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5987",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764496,
      "name": "__perf_event_header__init_id.isra.83",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832112,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:5996",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832112,
      "name": "__perf_event_header__init_id.isra.86",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927920,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6074",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927920,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580981552,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981552,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166304,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6573",
      "file": "kernel/events/core.c",
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
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166304,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206496,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6651",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206496,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222288,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6762",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222288,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463856,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6886",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463856,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811936,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6791",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811936,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event, u64 sample_type)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238112,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:7049",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238112,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void __perf_event_header__init_id(struct perf_sample_data * data, struct perf_event * event, u64 sample_type)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438864,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:7057",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438864,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void __perf_event_header__init_id(struct perf_sample_data * data, struct perf_event * event, u64 sample_type)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607008,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:7130",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607008,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492329272,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492329272,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226210640,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226210640,
      "name": "__perf_event_header__init_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285574896,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285574896,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272453802,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272453802,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950352,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950352,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580896416,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896416,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941600,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941600,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_event_header__init_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581003184,
      "name": "__perf_event_header__init_id",
      "external": false,
      "loc": "kernel/events/core.c:6190",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
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
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003184,
      "name": "__perf_event_header__init_id.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 sample_type</code>
</li>
</ul>
</details>
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
<code>header, data, event, sample_type</code> ➡️ <code>data, event, sample_type</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __perf_event_header__init_id(struct perf_event_header * header, struct perf_sample_data * data, struct perf_event * event)
```
</details>
</li>
</ul>
