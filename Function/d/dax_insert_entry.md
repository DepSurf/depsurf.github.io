# Function: <code>dax_insert_entry</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044224,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:709",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044224,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:715",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204880,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071582214082,
      "name": "dax_insert_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285712,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285712,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569760,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569760,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641328,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:732",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641328,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582670272,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:744",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582670272,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996528,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:744",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996528,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467920,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:745",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467920,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void * dax_insert_entry(struct xa_state * xas, struct vm_fault * vmf, const struct iomap_iter * iter, void * entry, pfn_t pfn, long unsigned int flags)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584060496,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:856",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060496,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void * dax_insert_entry(struct xa_state * xas, struct vm_fault * vmf, const struct iomap_iter * iter, void * entry, pfn_t pfn, long unsigned int flags)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286912,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:883",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286912,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
void * dax_insert_entry(struct xa_state * xas, struct vm_fault * vmf, const struct iomap_iter * iter, void * entry, pfn_t pfn, long unsigned int flags)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503712,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:869",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503712,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
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
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493861672,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493861672,
      "name": "dax_insert_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287488768,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287488768,
      "name": "dax_insert_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273428374,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273428374,
      "name": "dax_insert_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254448,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254448,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192080,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192080,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244928,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244928,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```

```json
{
  "name": "dax_insert_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321776,
      "name": "dax_insert_entry",
      "external": false,
      "loc": "fs/dax.c:716",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321776,
      "name": "dax_insert_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter * iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space * mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>bool dirty</code>
</li>
<li>
<b>Param reordered. </b>
<code>xas, mapping, vmf, entry, pfn, flags, dirty</code> ➡️ <code>xas, vmf, iter, entry, pfn, flags</code>
</li>
</ul>
</details>
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
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * dax_insert_entry(struct xa_state * xas, struct address_space * mapping, struct vm_fault * vmf, void * entry, pfn_t pfn, long unsigned int flags, bool dirty)
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
