# Function: <code>section_activate</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589950203,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:780",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590177757,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591195865,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:837",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195865,
      "name": "section_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591690757,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:844",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591690757,
      "name": "section_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591633840,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:852",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592807852,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:825",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594708924,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:828",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596452762,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:828",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596994090,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:828",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597923482,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:828",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503920536,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297815436,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297815436,
      "name": "section_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589780045,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589502868,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590223453,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "section_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590273811,
      "name": "section_activate",
      "external": false,
      "loc": "mm/sparse.c:809",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct page * section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```
</details>
</li>
</ul>
