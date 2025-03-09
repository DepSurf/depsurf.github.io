# Function: <code>perf_trace_event_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580296830,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:185",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580339788,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:188",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580385548,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:188",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580397084,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:188",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580452476,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:188",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580514240,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:189",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514240,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571952,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571952,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580629056,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629056,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580675632,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675632,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780864,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:195",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780864,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768864,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:195",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768864,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580773968,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:195",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773968,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580958032,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:195",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958032,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581200672,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:193",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200672,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519280,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:193",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519280,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581637936,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:193",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637936,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581751872,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:193",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751872,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491983520,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491983520,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225918152,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225918152,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285104720,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285104720,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272252386,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580644432,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644432,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580590640,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590640,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580635680,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635680,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```

```json
{
  "name": "perf_trace_event_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580693184,
      "name": "perf_trace_event_init",
      "external": false,
      "loc": "kernel/trace/trace_event_perf.c:190",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693184,
      "name": "perf_trace_event_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int perf_trace_event_init(struct trace_event_call * tp_event, struct perf_event * p_event)
```
</details>
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
