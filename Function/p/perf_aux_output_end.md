# Function: <code>perf_aux_output_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size, bool truncated)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440928,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:346",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_del",
        "arch/x86/events/intel/bts.c:bts_event_add",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/pt.c:pt_event_add",
        "arch/x86/events/intel/pt.c:pt_event_del",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440928,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size, bool truncated)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580516128,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:411",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516128,
      "name": "perf_aux_output_end",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size, bool truncated)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580096,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:411",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580096,
      "name": "perf_aux_output_end",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580610688,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:425",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580610688,
      "name": "perf_aux_output_end",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691472,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:439",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691472,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823488,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:440",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823488,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890160,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:440",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890160,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987680,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987680,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041664,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041664,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220720,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220720,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263360,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263360,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282048,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282048,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526000,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526000,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873872,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873872,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301552,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:480",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301552,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502336,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:480",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502336,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582670880,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:481",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582670880,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492396184,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492396184,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226282480,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226282480,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285658128,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285658128,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272502232,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272502232,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010512,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010512,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956640,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956640,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581001712,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001712,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void perf_aux_output_end(struct perf_output_handle * handle, long unsigned int size)
```

```json
{
  "name": "perf_aux_output_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062912,
      "name": "perf_aux_output_end",
      "external": true,
      "loc": "kernel/events/ring_buffer.c:475",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:intel_bts_interrupt",
        "arch/x86/events/intel/bts.c:bts_event_stop",
        "arch/x86/events/intel/bts.c:bts_event_start",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062912,
      "name": "perf_aux_output_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool truncated</code>
</li>
</ul>
</details>
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
