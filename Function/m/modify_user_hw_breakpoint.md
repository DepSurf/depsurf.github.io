# Function: <code>modify_user_hw_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444320,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:433",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444320,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519264,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:433",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519264,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580583232,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:433",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580583232,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613872,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:433",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613872,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694640,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:431",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694640,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580828416,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:521",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828416,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895232,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:510",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895232,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992784,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992784,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046800,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046800,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226576,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:513",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226576,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269152,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:513",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269152,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287808,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:513",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287808,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532144,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:514",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532144,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880480,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:514",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880480,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312672,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:825",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312672,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513776,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:825",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513776,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682240,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:797",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682240,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492403080,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:ptrace_hbp_set_addr",
        "arch/arm64/kernel/ptrace.c:ptrace_hbp_set_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492403080,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226287916,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:ptrace_sethbpregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226287916,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285666416,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:ptrace_set_debugreg",
        "arch/powerpc/kernel/ptrace.c:ptrace_triggered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285666416,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015648,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015648,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961776,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961776,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006848,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006848,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
```

```json
{
  "name": "modify_user_hw_breakpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068048,
      "name": "modify_user_hw_breakpoint",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:497",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr",
        "arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068048,
      "name": "modify_user_hw_breakpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int modify_user_hw_breakpoint(struct perf_event * bp, struct perf_event_attr * attr)
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
