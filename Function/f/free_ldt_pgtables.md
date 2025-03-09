# Function: <code>free_ldt_pgtables</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579048928,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:200",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048928,
      "name": "free_ldt_pgtables.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071579049088,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054592,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054592,
      "name": "free_ldt_pgtables.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071579054752,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579058752,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058752,
      "name": "free_ldt_pgtables.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071579058912,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068396,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067232,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070492,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068672,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076144,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076144,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078624,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078624,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085520,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085520,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108560,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071592053979,
      "name": "free_ldt_pgtables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139600,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071593820823,
      "name": "free_ldt_pgtables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:391",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183856,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071595958655,
      "name": "free_ldt_pgtables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:393",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187936,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596476053,
      "name": "free_ldt_pgtables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void free_ldt_pgtables(struct mm_struct * mm)
```

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:393",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217152,
      "name": "free_ldt_pgtables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071597371818,
      "name": "free_ldt_pgtables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070844,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069024,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579003470,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001760,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070428,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068608,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ldt_pgtables",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074522,
      "name": "free_ldt_pgtables",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_arch_exit_mmap",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073360,
      "name": "free_ldt_pgtables.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void free_ldt_pgtables(struct mm_struct * mm)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void free_ldt_pgtables(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void free_ldt_pgtables(struct mm_struct * mm)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
