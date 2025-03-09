# Function: <code>free_hugepage_table</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589235441,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:834",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589479290,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:827",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589938392,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590165944,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591180973,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:902",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591180973,
      "name": "free_hugepage_table",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591676376,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:896",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591676376,
      "name": "free_hugepage_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591620276,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:994",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591620276,
      "name": "free_hugepage_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592793525,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:995",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592793525,
      "name": "free_hugepage_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594693323,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:995",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594693323,
      "name": "free_hugepage_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596431864,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:996",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596972648,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:996",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597901096,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:996",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589768232,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589490757,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590211640,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
  "name": "free_hugepage_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590262008,
      "name": "free_hugepage_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:894",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
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
void free_hugepage_table(struct page * page, struct vmem_altmap * altmap)
```
</details>
</li>
</ul>
