# Function: <code>ftrace_ops_trampoline</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580300676,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1124",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300592,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361632,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1113",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361632,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417552,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1062",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417552,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471088,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1059",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471088,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519232,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519232,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608800,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1051",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608720,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580598912,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1050",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598832,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601792,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1050",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601712,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772896,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1051",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772816,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991072,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1045",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991072,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288736,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1045",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288736,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383744,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1076",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383744,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491600,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1076",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491600,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491799808,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491799808,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225747492,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225747492,
      "name": "ftrace_ops_trampoline",
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284854592,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284854592,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272112338,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272112338,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580488032,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488032,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435056,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435056,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479280,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479280,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```

```json
{
  "name": "ftrace_ops_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535488,
      "name": "ftrace_ops_trampoline",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1060",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:is_ftrace_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535488,
      "name": "ftrace_ops_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ftrace_ops * ftrace_ops_trampoline(long unsigned int addr)
```
</details>
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
