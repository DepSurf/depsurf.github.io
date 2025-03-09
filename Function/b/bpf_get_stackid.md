# Function: <code>bpf_get_stackid</code>

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
u64 bpf_get_stackid(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451744,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:119",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451744,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512848,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:115",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512848,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580544672,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:116",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544672,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622400,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:121",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622400,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749984,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:338",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749984,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1086
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814288,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:350",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814288,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1163
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903376,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:345",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903376,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956560,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956560,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119984,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:351",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119984,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1154
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154032,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:465",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154032,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169840,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:330",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169840,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408896,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:337",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408896,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732800,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:283",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732800,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140528,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:283",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140528,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337744,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:280",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337744,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504000,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:280",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp",
        "kernel/bpf/stackmap.c:bpf_get_stackid_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504000,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492302088,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492302088,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226187188,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226187188,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1128
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285538816,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285538816,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1444
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272431562,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272431562,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925360,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925360,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871424,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871424,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916608,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916608,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_get_stackid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976704,
      "name": "bpf_get_stackid",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:346",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976704,
      "name": "bpf_get_stackid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
u64 bpf_get_stackid(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 regs</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
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
