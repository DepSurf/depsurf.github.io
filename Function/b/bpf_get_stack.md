# Function: <code>bpf_get_stack</code>

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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751072,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:438",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751072,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815456,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:450",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815456,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904512,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:445",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904512,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957696,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957696,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121152,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:451",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121152,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154944,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:636",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154944,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170752,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:501",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170752,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409808,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:508",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409808,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733840,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:455",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733840,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141616,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:455",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141616,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338832,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:452",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338832,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505184,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:461",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505184,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492303160,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492303160,
      "name": "bpf_get_stack",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226188316,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226188316,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285540272,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285540272,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272432506,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272432506,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926496,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926496,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580872560,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872560,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917744,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917744,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_get_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977840,
      "name": "bpf_get_stack",
      "external": true,
      "loc": "kernel/bpf/stackmap.c:446",
      "file": "kernel/bpf/stackmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stack_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977840,
      "name": "bpf_get_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1)
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
