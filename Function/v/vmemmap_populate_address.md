# Function: <code>vmemmap_populate_address</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t * vmemmap_populate_address(long unsigned int addr, int node, struct vmem_altmap * altmap, struct page * reuse)
```

```json
{
  "name": "vmemmap_populate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594710895,
      "name": "vmemmap_populate_address",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:634",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_populate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594710895,
      "name": "vmemmap_populate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
pte_t * vmemmap_populate_address(long unsigned int addr, int node, struct vmem_altmap * altmap, struct page * reuse)
```

```json
{
  "name": "vmemmap_populate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596456304,
      "name": "vmemmap_populate_address",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:245",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596456304,
      "name": "vmemmap_populate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
pte_t * vmemmap_populate_address(long unsigned int addr, int node, struct vmem_altmap * altmap, struct page * reuse)
```

```json
{
  "name": "vmemmap_populate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596997632,
      "name": "vmemmap_populate_address",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:245",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596997632,
      "name": "vmemmap_populate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
pte_t * vmemmap_populate_address(long unsigned int addr, int node, struct vmem_altmap * altmap, struct page * reuse)
```

```json
{
  "name": "vmemmap_populate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597926960,
      "name": "vmemmap_populate_address",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:245",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597926960,
      "name": "vmemmap_populate_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
pte_t * vmemmap_populate_address(long unsigned int addr, int node, struct vmem_altmap * altmap, struct page * reuse)
```
</details>
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
