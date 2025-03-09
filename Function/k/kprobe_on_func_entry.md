# Function: <code>kprobe_on_func_entry</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166832,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1902",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/kprobes.c:register_jprobe",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166832,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219504,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1906",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219504,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279728,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1950",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279728,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331824,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1867",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331824,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384544,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1871",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384544,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433456,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433456,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514800,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1958",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514800,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503600,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1970",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503600,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507696,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1975",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507696,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675488,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1967",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675488,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580885214,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:2158",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593936769,
      "name": "kprobe_on_func_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580885488,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581175230,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:2166",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596001317,
      "name": "kprobe_on_func_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581175536,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269784,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:2179",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596519802,
      "name": "kprobe_on_func_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581270064,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375441,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:2180",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597420213,
      "name": "kprobe_on_func_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581376064,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491700816,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491700816,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225654560,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225654560,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284721888,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284721888,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580402256,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402256,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580349424,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349424,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580393504,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393504,
      "name": "kprobe_on_func_entry",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```

```json
{
  "name": "kprobe_on_func_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449104,
      "name": "kprobe_on_func_entry",
      "external": true,
      "loc": "kernel/kprobes.c:1914",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry",
        "kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449104,
      "name": "kprobe_on_func_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
bool kprobe_on_func_entry(kprobe_opcode_t * addr, const char * sym, long unsigned int offset)
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
