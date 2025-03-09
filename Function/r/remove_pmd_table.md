# Function: <code>remove_pmd_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587349203,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:863",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587849374,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:811",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588064175,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:801",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588290755,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:947",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table"
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
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588855995,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:955",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589235271,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:969",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589479120,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:962",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589938187,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589938187,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165739,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165739,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591181532,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1037",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181532,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591676912,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1031",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591676912,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591620312,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1101",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591620312,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592793561,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1102",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592793561,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594693369,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1102",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594693369,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596430928,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1103",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596430928,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596971712,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1103",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596971712,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597900160,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1103",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597900160,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1225
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297809848,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/powerpc/mm/book3s64/radix_pgtable.c:790",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589768027,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589768027,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589490518,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490518,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1181
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590211435,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211435,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```

```json
{
  "name": "remove_pmd_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590261803,
      "name": "remove_pmd_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590261803,
      "name": "remove_pmd_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
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
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void remove_pmd_table(pmd_t * pmd_start, long unsigned int addr, long unsigned int end, bool direct, struct vmem_altmap * altmap)
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
