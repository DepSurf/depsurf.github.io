# Function: <code>__bpf_trace_napi_poll</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588034688,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588034688,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202368,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202368,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530432,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530432,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738960,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738960,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589607072,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589607072,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589622432,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589622432,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589510992,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589510992,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590252496,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590252496,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591838160,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591838160,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593636400,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593636400,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594112496,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594112496,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594907136,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594907136,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502300368,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502300368,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235044548,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235044548,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295813648,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295813648,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588345696,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588345696,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588058400,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588058400,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588677520,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588677520,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
```

```json
{
  "name": "__bpf_trace_napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817408,
      "name": "__bpf_trace_napi_poll",
      "external": false,
      "loc": "include/trace/events/napi.h:14",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817408,
      "name": "__bpf_trace_napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
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
void __bpf_trace_napi_poll(void * __data, struct napi_struct * napi, int work, int budget)
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
