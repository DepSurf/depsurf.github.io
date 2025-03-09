# Function: <code>p4d_set_huge</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:896",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:965",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1008",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1046",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1046",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410464,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410464,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411104,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411104,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414272,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414272,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477152,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477152,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555568,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:679",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555568,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662448,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:686",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662448,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676608,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:686",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676608,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710736,
      "name": "p4d_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:698",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710736,
      "name": "p4d_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1063",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1063",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "p4d_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1045",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int p4d_set_huge(p4d_t * p4d, phys_addr_t addr, pgprot_t prot)
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
