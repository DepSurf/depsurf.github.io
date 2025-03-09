# Function: <code>arch_syscall_match_sym_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595119104,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:35",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595288580,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:35",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595535915,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:35",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596456016,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:35",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602781887,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:36",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513447,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:52",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513447,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571159,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:52",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571159,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628280,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628280,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674856,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674856,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779400,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:66",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779400,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591322132,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:84",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322132,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591263951,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:84",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591263951,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592175051,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:84",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592175051,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593948574,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:96",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593948574,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627825445,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:116",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619589381,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:119",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621892725,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:119",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510927560,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/arm64/include/asm/ftrace.h:73",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225917316,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/arm/include/asm/ftrace.h:61",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225917316,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285103420,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/powerpc/include/asm/ftrace.h:88",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285103420,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270661442,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "kernel/trace/trace_syscalls.c:36",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643656,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643656,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589880,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589880,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634904,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634904,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```

```json
{
  "name": "arch_syscall_match_sym_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692408,
      "name": "arch_syscall_match_sym_name",
      "external": false,
      "loc": "arch/x86/include/asm/ftrace.h:49",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692408,
      "name": "arch_syscall_match_sym_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool arch_syscall_match_sym_name(const char * sym, const char * name)
```
</details>
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
bool arch_syscall_match_sym_name(const char * sym, const char * name)
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
