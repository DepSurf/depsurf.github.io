# Function: <code>swevent_hlist_put_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580395472,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:6791",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:perf_swevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395472,
      "name": "swevent_hlist_put_cpu.isra.84",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459216,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:7385",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459216,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521664,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:7498",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521664,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554256,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:7721",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554256,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635024,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:7718",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635024,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761584,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8100",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761584,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828400,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8109",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828400,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923360,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8413",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923360,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977552,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977552,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144080,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9079",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:swevent_hlist_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144080,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184128,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9345",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:swevent_hlist_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184128,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202496,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9475",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202496,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442144,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442144,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783408,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783408,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209200,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9854",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209200,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409216,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9883",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:swevent_hlist_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409216,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577440,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9953",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:swevent_hlist_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577440,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492326296,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492326296,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226219096,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226219096,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285572624,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285572624,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272451164,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272451164,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946352,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946352,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892416,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892416,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937600,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937600,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void swevent_hlist_put_cpu(int cpu)
```

```json
{
  "name": "swevent_hlist_put_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999184,
      "name": "swevent_hlist_put_cpu",
      "external": false,
      "loc": "kernel/events/core.c:8529",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999184,
      "name": "swevent_hlist_put_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void swevent_hlist_put_cpu(int cpu)
```
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
