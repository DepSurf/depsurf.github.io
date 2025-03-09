# Function: <code>alloc_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580323646,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:263",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
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
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580378629,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:263",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
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
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580426388,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:278",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
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
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580438174,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:281",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
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
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494718,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:281",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581536,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:305",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581536,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635248,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:189",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635248,
      "name": "alloc_trace_kprobe",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696384,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:219",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696384,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745312,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745312,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865760,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:255",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865760,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857904,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:257",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857904,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862976,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:257",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862976,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063792,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:253",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063792,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323328,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:254",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323328,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647584,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647584,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794080,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794080,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915424,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915424,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492058464,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492058464,
      "name": "alloc_trace_kprobe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225957580,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225957580,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285239456,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285239456,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714112,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714112,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660320,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660320,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705360,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705360,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
```

```json
{
  "name": "alloc_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763312,
      "name": "alloc_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:256",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763312,
      "name": "alloc_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
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
struct trace_kprobe * alloc_trace_kprobe(const char * group, const char * event, void * addr, const char * symbol, long unsigned int offs, int maxactive, int nargs, bool is_return)
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
