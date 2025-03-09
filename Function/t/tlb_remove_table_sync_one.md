# Function: <code>tlb_remove_table_sync_one</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581588179,
      "name": "tlb_remove_table_sync_one",
      "external": false,
      "loc": "mm/mmu_gather.c:142",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581634131,
      "name": "tlb_remove_table_sync_one",
      "external": false,
      "loc": "mm/mmu_gather.c:142",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581655811,
      "name": "tlb_remove_table_sync_one",
      "external": false,
      "loc": "mm/mmu_gather.c:142",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581924003,
      "name": "tlb_remove_table_sync_one",
      "external": false,
      "loc": "mm/mmu_gather.c:142",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582330821,
      "name": "tlb_remove_table_sync_one",
      "external": false,
      "loc": "mm/mmu_gather.c:155",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_remove_table_sync_one()
```

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582831128,
      "name": "tlb_remove_table_sync_one",
      "external": true,
      "loc": "mm/mmu_gather.c:194",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830592,
      "name": "tlb_remove_table_sync_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tlb_remove_table_sync_one()
```

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583046520,
      "name": "tlb_remove_table_sync_one",
      "external": true,
      "loc": "mm/mmu_gather.c:194",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045984,
      "name": "tlb_remove_table_sync_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tlb_remove_table_sync_one()
```

```json
{
  "name": "tlb_remove_table_sync_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228426,
      "name": "tlb_remove_table_sync_one",
      "external": true,
      "loc": "mm/mmu_gather.c:195",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227936,
      "name": "tlb_remove_table_sync_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void tlb_remove_table_sync_one()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
