# Function: <code>alloc_trace_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580353781,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:239",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
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
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580408855,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:239",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
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
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580456976,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:243",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
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
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580468130,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:245",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
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
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580524130,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:245",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580611920,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:248",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611920,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670784,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:272",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670784,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732288,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:300",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732288,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782896,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782896,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580896832,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896832,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891088,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891088,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895056,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895056,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096656,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:335",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096656,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358864,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:336",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358864,
      "name": "alloc_trace_uprobe",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693008,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693008,
      "name": "alloc_trace_uprobe",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838000,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:336",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838000,
      "name": "alloc_trace_uprobe",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961472,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:331",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961472,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492092304,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492092304,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225993824,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225993824,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285293984,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285293984,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751696,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751696,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697888,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697888,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742944,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742944,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
```

```json
{
  "name": "alloc_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800960,
      "name": "alloc_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:338",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800960,
      "name": "alloc_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
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
struct trace_uprobe * alloc_trace_uprobe(const char * group, const char * event, int nargs, bool is_ret)
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
