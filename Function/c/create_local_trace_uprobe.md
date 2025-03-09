# Function: <code>create_local_trace_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1355",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614741,
      "name": "create_local_trace_uprobe.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580614064,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1357",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673651,
      "name": "create_local_trace_uprobe.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580673056,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1350",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738077,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580737568,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788795,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580788352,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1568",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906276,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580905760,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1580",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322907,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580900560,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1585",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591264771,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580904384,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1586",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592179885,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581106576,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1576",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593953714,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581368976,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705312,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1582",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705312,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850224,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1583",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850224,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973344,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1579",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973344,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492100992,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492100992,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226001012,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226001012,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285303536,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285303536,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757595,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580757152,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703787,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580703344,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748843,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580748400,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
```

```json
{
  "name": "create_local_trace_uprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_uprobe",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1556",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_uprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806891,
      "name": "create_local_trace_uprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580806448,
      "name": "create_local_trace_uprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, bool is_return)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int ref_ctr_offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, offs, is_return</code> ➡️ <code>name, offs, ref_ctr_offset, is_return</code>
</li>
</ul>
</details>
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
struct trace_event_call * create_local_trace_uprobe(char * name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return)
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
