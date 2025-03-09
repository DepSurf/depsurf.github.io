# Function: <code>__set_pages_np</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383904,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2242",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383904,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388208,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2132",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388208,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432042,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2168",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__kernel_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428160,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579431514,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2168",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434474,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2176",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579498698,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2176",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580122,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2227",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579689629,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2331",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579703389,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2330",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579737997,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2334",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384112,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2132",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384112,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313536,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2132",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313536,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384032,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2132",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384032,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __set_pages_np(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_np",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392544,
      "name": "__set_pages_np",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2132",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392544,
      "name": "__set_pages_np",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __set_pages_np(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __set_pages_np(struct page * page, int numpages)
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
