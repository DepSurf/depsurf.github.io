# Function: <code>hmm_vma_fault</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int hmm_vma_fault(struct vm_area_struct * vma, struct hmm_range * range, long unsigned int start, long unsigned int end, hmm_pfn_t * pfns, bool write, bool block)
```

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389664,
      "name": "hmm_vma_fault",
      "external": true,
      "loc": "mm/hmm.c:663",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389664,
      "name": "hmm_vma_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int hmm_vma_fault(struct hmm_range * range, bool block)
```

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546624,
      "name": "hmm_vma_fault",
      "external": true,
      "loc": "mm/hmm.c:828",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546624,
      "name": "hmm_vma_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
int hmm_vma_fault(struct hmm_range * range, bool block)
```

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631824,
      "name": "hmm_vma_fault",
      "external": true,
      "loc": "mm/hmm.c:874",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631824,
      "name": "hmm_vma_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
    }
  ]
}
```
</details>
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
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582034736,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:61",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034736,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582083584,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:61",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083584,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582108752,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:61",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108752,
      "name": "hmm_vma_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk * walk)
```

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582424976,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:63",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424976,
      "name": "hmm_vma_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582940544,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:63",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940544,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497296,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:63",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497296,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712304,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:63",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712304,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
  "name": "hmm_vma_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912560,
      "name": "hmm_vma_fault",
      "external": false,
      "loc": "mm/hmm.c:63",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912560,
      "name": "hmm_vma_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int hmm_vma_fault(struct vm_area_struct * vma, struct hmm_range * range, long unsigned int start, long unsigned int end, hmm_pfn_t * pfns, bool write, bool block)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Param removed. </b>
<code>hmm_pfn_t * pfns</code>
</li>
<li>
<b>Param removed. </b>
<code>bool write</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, range, start, end, pfns, write, block</code> ➡️ <code>range, block</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int hmm_vma_fault(struct hmm_range * range, bool block)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk * walk)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk * walk)
```
</details>
</li>
</ul>
