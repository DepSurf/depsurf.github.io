# Function: <code>get_callchain_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_callchain_buffers()
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442736,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:97",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442736,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517152,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:107",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517152,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581120,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:107",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581120,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611728,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:109",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611728,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692544,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:109",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692544,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824544,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:109",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824544,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891296,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:109",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891296,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989040,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989040,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043024,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043024,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222544,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222544,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264992,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264992,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283696,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283696,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527728,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527728,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875664,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875664,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303456,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303456,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504240,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504240,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672784,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672784,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492397880,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492397880,
      "name": "get_callchain_buffers",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226283464,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226283464,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285660256,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285660256,
      "name": "get_callchain_buffers",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272505916,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272505916,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011872,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011872,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958000,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958000,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003072,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003072,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int get_callchain_buffers(int event_max_stack)
```

```json
{
  "name": "get_callchain_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064272,
      "name": "get_callchain_buffers",
      "external": true,
      "loc": "kernel/events/callchain.c:108",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064272,
      "name": "get_callchain_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int event_max_stack</code>
</li>
</ul>
</details>
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
