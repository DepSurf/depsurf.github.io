# Function: <code>map_ldt_struct</code>

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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049200,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:116",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049200,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053952,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:116",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053952,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579059024,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059024,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579067914,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066592,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071579069279,
      "name": "map_ldt_struct.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070010,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068928,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077985,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076656,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579080155,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079040,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579087019,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086000,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110107,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109072,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071592054080,
      "name": "map_ldt_struct.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140192,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071593820929,
      "name": "map_ldt_struct.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184544,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071595958761,
      "name": "map_ldt_struct.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188608,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071596476161,
      "name": "map_ldt_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```

```json
{
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:288",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217824,
      "name": "map_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071597371926,
      "name": "map_ldt_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070362,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069280,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579003028,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002000,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069946,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068864,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "map_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074042,
      "name": "map_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:204",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:ldt_dup_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072704,
      "name": "map_ldt_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
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
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int map_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt, int slot)
```
</details>
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
