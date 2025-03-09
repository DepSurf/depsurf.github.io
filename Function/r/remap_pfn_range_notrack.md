# Function: <code>remap_pfn_range_notrack</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612224,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2280",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612224,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2375",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592199543,
      "name": "remap_pfn_range_notrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581879232,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2468",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593976030,
      "name": "remap_pfn_range_notrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071582278896,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1466
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
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2439",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596032224,
      "name": "remap_pfn_range_notrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071582771408,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1461
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
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2439",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596554189,
      "name": "remap_pfn_range_notrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071582988592,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range_notrack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remap_pfn_range_notrack",
      "external": true,
      "loc": "mm/memory.c:2462",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597457942,
      "name": "remap_pfn_range_notrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583162896,
      "name": "remap_pfn_range_notrack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1405
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```
</details>
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
