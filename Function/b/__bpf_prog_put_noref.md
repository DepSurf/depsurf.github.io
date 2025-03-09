# Function: <code>__bpf_prog_put_noref</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580812640,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812640,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944088,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1725",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580925152,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1693",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925152,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928512,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1694",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928512,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1764",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131952,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071592180218,
      "name": "__bpf_prog_put_noref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2008",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403744,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071593954129,
      "name": "__bpf_prog_put_noref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2033",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754800,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071596013629,
      "name": "__bpf_prog_put_noref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2111",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915312,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071596533625,
      "name": "__bpf_prog_put_noref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2151",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041184,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071597434456,
      "name": "__bpf_prog_put_noref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492133592,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492133592,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226031848,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031848,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285340656,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285340656,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272299330,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299330,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580781440,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781440,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580727616,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727616,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772688,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772688,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```

```json
{
  "name": "__bpf_prog_put_noref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580830912,
      "name": "__bpf_prog_put_noref",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1339",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830912,
      "name": "__bpf_prog_put_noref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __bpf_prog_put_noref(struct bpf_prog * prog, bool deferred)
```
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
