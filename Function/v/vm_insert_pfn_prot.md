# Function: <code>vm_insert_pfn_prot</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "vm_insert_pfn_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800720,
      "name": "vm_insert_pfn_prot",
      "external": true,
      "loc": "mm/memory.c:1622",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800720,
      "name": "vm_insert_pfn_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "vm_insert_pfn_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864960,
      "name": "vm_insert_pfn_prot",
      "external": true,
      "loc": "mm/memory.c:1618",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864960,
      "name": "vm_insert_pfn_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "vm_insert_pfn_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909936,
      "name": "vm_insert_pfn_prot",
      "external": true,
      "loc": "mm/memory.c:1769",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909936,
      "name": "vm_insert_pfn_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "vm_insert_pfn_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008624,
      "name": "vm_insert_pfn_prot",
      "external": true,
      "loc": "mm/memory.c:1872",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008624,
      "name": "vm_insert_pfn_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "vm_insert_pfn_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137456,
      "name": "vm_insert_pfn_prot",
      "external": true,
      "loc": "mm/memory.c:1883",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137456,
      "name": "vm_insert_pfn_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot)
```
</details>
</li>
</ul>
