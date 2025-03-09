# Function: <code>insert_pfn_pud</code>

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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581144336,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:798",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581267672,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:798",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581415212,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:795",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498041,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:814",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581606299,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:852",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581676875,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:858",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896288,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:880",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896288,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942480,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:872",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942480,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967632,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:888",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967632,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270320,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:888",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270320,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750832,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:882",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750832,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284560,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:942",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284560,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583504480,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:939",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504480,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, bool write)
```

```json
{
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583698960,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:1154",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698960,
      "name": "insert_pfn_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581645611,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:858",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581586473,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:858",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581636923,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:858",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
  "name": "insert_pfn_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581702030,
      "name": "insert_pfn_pud",
      "external": false,
      "loc": "mm/huge_memory.c:858",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
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
void insert_pfn_pud(struct vm_area_struct * vma, long unsigned int addr, pud_t * pud, pfn_t pfn, pgprot_t prot, bool write)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pud, pfn, prot, write</code> ➡️ <code>vma, addr, pud, pfn, write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
