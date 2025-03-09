# Function: <code>vmf_insert_pfn_pmd_prot</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898944,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:838",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898944,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947536,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:830",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947536,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968880,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:846",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968880,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270960,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:846",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270960,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582755840,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:840",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755840,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289520,
      "name": "vmf_insert_pfn_pmd_prot",
      "external": true,
      "loc": "mm/huge_memory.c:900",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289520,
      "name": "vmf_insert_pfn_pmd_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault * vmf, pfn_t pfn, pgprot_t pgprot, bool write)
```
</details>
</li>
</ul>
