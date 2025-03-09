# Function: <code>create_local_trace_kprobe</code>

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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1462",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585444,
      "name": "create_local_trace_kprobe.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580584624,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1378",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643718,
      "name": "create_local_trace_kprobe.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580642928,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1390",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705127,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580704528,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753510,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580753008,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1782",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870725,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580870144,
      "name": "create_local_trace_kprobe",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1803",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322727,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580862544,
      "name": "create_local_trace_kprobe",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1806",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591264591,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580866016,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1801",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592179168,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581066832,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1795",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593952954,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581326464,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656832,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1747",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656832,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797392,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1704",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797392,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918896,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1769",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918896,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492064272,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492064272,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225963800,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225963800,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285244576,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285244576,
      "name": "create_local_trace_kprobe",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722310,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580721808,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668502,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580668000,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713558,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580713056,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
```

```json
{
  "name": "create_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771510,
      "name": "create_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580771008,
      "name": "create_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
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
struct trace_event_call * create_local_trace_kprobe(char * func, void * addr, long unsigned int offs, bool is_return)
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
