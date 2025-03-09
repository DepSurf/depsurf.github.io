# Function: <code>clear_rdrand_cpuid_bit</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148858,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:823",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148656,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579151504,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579151306,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151104,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579154064,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579168182,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:851",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168048,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579172525,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164790,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164656,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071591252946,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579172342,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:820",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172208,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071591196680,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579205828,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:824",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205680,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071592063544,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579256347,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:800",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256160,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071593830259,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318347,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:798",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318160,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071595961321,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326203,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:870",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326016,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071596478666,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579355995,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:864",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355808,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071597374439,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579151674,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151472,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579154432,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579082179,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082064,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579085991,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579151226,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151024,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579153984,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```

```json
{
  "name": "clear_rdrand_cpuid_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156362,
      "name": "clear_rdrand_cpuid_bit",
      "external": false,
      "loc": "arch/x86/kernel/cpu/amd.c:825",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156160,
      "name": "clear_rdrand_cpuid_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071579159120,
      "name": "clear_rdrand_cpuid_bit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```
</details>
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
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clear_rdrand_cpuid_bit(struct cpuinfo_x86 * c)
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
