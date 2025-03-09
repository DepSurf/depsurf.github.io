# Function: <code>bpf_get_stackid_tp</code>

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
u64 bpf_get_stackid_tp(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369248,
      "name": "bpf_get_stackid_tp",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:473",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369248,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417232,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:499",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417232,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429520,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:567",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429520,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485472,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:616",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485472,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571152,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:650",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571152,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628784,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:686",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628784,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689520,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:791",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689520,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736480,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736480,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850272,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1214",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850272,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839168,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1443",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839168,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843936,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1137",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843936,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043744,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1214",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043744,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298992,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1392",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298992,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623328,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1606",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623328,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763104,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1615",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763104,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880496,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1720",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880496,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492043368,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492043368,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225945900,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225945900,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285216784,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285216784,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705280,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705280,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651488,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651488,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696528,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696528,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid_tp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752048,
      "name": "bpf_get_stackid_tp",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:815",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752048,
      "name": "bpf_get_stackid_tp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 bpf_get_stackid_tp(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 tp_buff</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 flags</code>
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
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
