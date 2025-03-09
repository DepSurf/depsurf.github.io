# Function: <code>hw_breakpoint_arch_parse</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580826357,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:404",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827696,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076896,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:329",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076896,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579086528,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086528,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088528,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088528,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100480,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:400",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100480,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100656,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100656,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107056,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107056,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131568,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131568,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167360,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167360,
      "name": "hw_breakpoint_arch_parse",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220080,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220080,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225520,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225520,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254384,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:422",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254384,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490312920,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/arm64/kernel/hw_breakpoint.c:507",
      "file": "arch/arm64/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490312920,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224466260,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/arm/kernel/hw_breakpoint.c:583",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224466260,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282394848,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/powerpc/kernel/hw_breakpoint.c:132",
      "file": "arch/powerpc/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282394848,
      "name": "hw_breakpoint_arch_parse",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088880,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088880,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021216,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021216,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088464,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088464,
      "name": "hw_breakpoint_arch_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_arch_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579092560,
      "name": "hw_breakpoint_arch_parse",
      "external": true,
      "loc": "arch/x86/kernel/hw_breakpoint.c:314",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092560,
      "name": "hw_breakpoint_arch_parse",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
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
int hw_breakpoint_arch_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
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
