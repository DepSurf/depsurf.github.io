# Function: <code>kprobe_add_area_blacklist</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604741081,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2120",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332992,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604842758,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2124",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385584,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604876776,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434512,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580516227,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2224",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516480,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580504461,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2248",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504704,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580508573,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2253",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508816,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580676372,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2247",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580676640,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886254,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2465",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886528,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627808534,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2472",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176624,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619571398,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2485",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270848,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621874486,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2470",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes",
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376912,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510913696,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist",
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist",
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist",
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist",
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist",
        "arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491701808,
      "name": "kprobe_add_area_blacklist",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243401712,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225655488,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302551892,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284723200,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604782233,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403312,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604751148,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350480,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604859420,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580394560,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "kprobe_add_area_blacklist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604880918,
      "name": "kprobe_add_area_blacklist",
      "external": true,
      "loc": "kernel/kprobes.c:2167",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:init_kprobes"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist",
        "arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450176,
      "name": "kprobe_add_area_blacklist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end)
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
