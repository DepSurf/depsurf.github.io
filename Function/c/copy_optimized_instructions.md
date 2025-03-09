# Function: <code>copy_optimized_instructions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239530,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:174",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
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
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238925,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:175",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
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
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579251373,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:175",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 * dest, u8 * src)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246080,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:186",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246080,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262560,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:186",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262560,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273760,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:186",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273760,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297760,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:191",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297760,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314240,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314240,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579318320,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318320,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347296,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:198",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347296,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346656,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:199",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346656,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351264,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:199",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351264,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408976,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:199",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408976,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476160,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476160,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568704,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:207",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568704,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580384,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:207",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580384,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610176,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:207",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610176,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314224,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314224,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248816,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248816,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314144,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314144,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```

```json
{
  "name": "copy_optimized_instructions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322416,
      "name": "copy_optimized_instructions",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:177",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322416,
      "name": "copy_optimized_instructions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int copy_optimized_instructions(u8 * dest, u8 * src)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * real</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int copy_optimized_instructions(u8 * dest, u8 * src, u8 * real)
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
