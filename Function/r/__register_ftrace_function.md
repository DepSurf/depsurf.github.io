# Function: <code>__register_ftrace_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176155,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:408",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211259,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:387",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580252027,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:387",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580264971,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:400",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580318587,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:376",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580379250,
      "name": "__register_ftrace_function",
      "external": false,
      "loc": "kernel/trace/ftrace.c:365",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435616,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:310",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435616,
      "name": "__register_ftrace_function",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:307",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580492723,
      "name": "__register_ftrace_function.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580488256,
      "name": "__register_ftrace_function",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537440,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537440,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627392,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:302",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_function",
        "kernel/trace/ftrace.c:register_ftrace_function_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627392,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618192,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:302",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_function",
        "kernel/trace/ftrace.c:register_ftrace_function_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618192,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620832,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:302",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620832,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792512,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:302",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792512,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013840,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:299",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013840,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314304,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:299",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314304,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409696,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:330",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409696,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517456,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:330",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517456,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491819272,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491819272,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225767612,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225767612,
      "name": "__register_ftrace_function",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284883008,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284883008,
      "name": "__register_ftrace_function",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272129336,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272129336,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506240,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506240,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580453264,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453264,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497488,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497488,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __register_ftrace_function(struct ftrace_ops * ops)
```

```json
{
  "name": "__register_ftrace_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553760,
      "name": "__register_ftrace_function",
      "external": true,
      "loc": "kernel/trace/ftrace.c:308",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553760,
      "name": "__register_ftrace_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __register_ftrace_function(struct ftrace_ops * ops)
```
</details>
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
