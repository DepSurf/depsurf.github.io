# Function: <code>hw_breakpoint_parse</code>

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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580826352,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:420",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826352,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893120,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:403",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893120,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580990640,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990640,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044624,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044624,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224048,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:406",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224048,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581266624,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:406",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266624,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581285328,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:406",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285328,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529440,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:406",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529440,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581879849,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:406",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582312009,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:717",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582513257,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:717",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582681737,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:689",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492400552,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492400552,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226285648,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226285648,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285662960,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285662960,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013472,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013472,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580959600,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959600,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581004672,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004672,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```

```json
{
  "name": "hw_breakpoint_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581065872,
      "name": "hw_breakpoint_parse",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:390",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065872,
      "name": "hw_breakpoint_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
```
</details>
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
int hw_breakpoint_parse(struct perf_event * bp, const struct perf_event_attr * attr, struct arch_hw_breakpoint * hw)
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
