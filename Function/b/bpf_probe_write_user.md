# Function: <code>bpf_probe_write_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369824,
      "name": "bpf_probe_write_user",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:84",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369824,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415776,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:84",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415776,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427328,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:89",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427328,
      "name": "bpf_probe_write_user",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483040,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:99",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483040,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580568816,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:122",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568816,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626368,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:156",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626368,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687072,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:161",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687072,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734112,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734112,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847440,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:305",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847440,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836144,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:328",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836144,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841968,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:316",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841968,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041776,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:316",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041776,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296432,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:324",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296432,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620992,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:327",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620992,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761456,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:327",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761456,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878848,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:327",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878848,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492042080,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492042080,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225942776,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225942776,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285213312,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285213312,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702912,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702912,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649120,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649120,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694160,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694160,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_probe_write_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749680,
      "name": "bpf_probe_write_user",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:166",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749680,
      "name": "bpf_probe_write_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
u64 bpf_probe_write_user(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 unsafe_ptr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 src</code>
</li>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2)
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
