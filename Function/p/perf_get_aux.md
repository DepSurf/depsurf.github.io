# Function: <code>perf_get_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440432,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:416",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_event_del",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/pt.c:pt_update_head",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_del",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440432,
      "name": "perf_get_aux",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514832,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:490",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514832,
      "name": "perf_get_aux",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580578816,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:490",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578816,
      "name": "perf_get_aux",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609472,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:502",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609472,
      "name": "perf_get_aux",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687472,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:512",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687472,
      "name": "perf_get_aux",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819552,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:513",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819552,
      "name": "perf_get_aux",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886224,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886224,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983696,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983696,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037680,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037680,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216320,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head",
        "arch/x86/events/intel/pt.c:pt_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216320,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259040,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:557",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head",
        "arch/x86/events/intel/pt.c:pt_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259040,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277792,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:557",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277792,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581521632,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:557",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521632,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869152,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:557",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869152,
      "name": "perf_get_aux",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296576,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:560",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296576,
      "name": "perf_get_aux",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497344,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:560",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497344,
      "name": "perf_get_aux",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665856,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:561",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665856,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492391680,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492391680,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226277944,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226277944,
      "name": "perf_get_aux",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285652304,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285652304,
      "name": "perf_get_aux",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272501156,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272501156,
      "name": "perf_get_aux",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006528,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006528,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952656,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952656,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997728,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997728,
      "name": "perf_get_aux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * perf_get_aux(struct perf_output_handle * handle)
```

```json
{
  "name": "perf_get_aux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058816,
      "name": "perf_get_aux",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:555",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:__bts_event_start",
        "arch/x86/events/intel/bts.c:bts_update",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_update_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058816,
      "name": "perf_get_aux",
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
