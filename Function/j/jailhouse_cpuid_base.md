# Function: <code>jailhouse_cpuid_base</code>

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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579297856,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:26",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297856,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322464,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322464,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579337880,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579342056,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371605,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:43",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371376,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071579371552,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370597,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370368,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579370544,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374341,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374112,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579374288,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435701,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435472,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579435648,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
uint32_t jailhouse_cpuid_base()
```

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505221,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504848,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071593847525,
      "name": "jailhouse_cpuid_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603413,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602912,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579616165,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615664,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579645221,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:45",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644720,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579337960,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270485,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270336,
      "name": "jailhouse_cpuid_base.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579337880,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jailhouse_cpuid_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579346328,
      "name": "jailhouse_cpuid_base",
      "external": false,
      "loc": "arch/x86/kernel/jailhouse.c:27",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect",
        "arch/x86/kernel/jailhouse.c:jailhouse_detect"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
uint32_t jailhouse_cpuid_base()
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
uint32_t jailhouse_cpuid_base()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
uint32_t jailhouse_cpuid_base()
```
</details>
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
uint32_t jailhouse_cpuid_base()
```
</details>
</li>
</ul>
