# Function: <code>__set_pages_p</code>

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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384032,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2223",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384032,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388336,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2113",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388336,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432170,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2149",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__kernel_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428288,
      "name": "__set_pages_p",
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579431642,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2149",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434602,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2157",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579498826,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2157",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580266,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2208",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579689805,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2312",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579703565,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2311",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579738173,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:2315",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush"
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384240,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2113",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384240,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313664,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2113",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313664,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384160,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2113",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384160,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
```

```json
{
  "name": "__set_pages_p",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392672,
      "name": "__set_pages_p",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:2113",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:set_direct_map_default_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392672,
      "name": "__set_pages_p",
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
int __set_pages_p(struct page * page, int numpages)
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
int __set_pages_p(struct page * page, int numpages)
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
int __set_pages_p(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __set_pages_p(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __set_pages_p(struct page * page, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __set_pages_p(struct page * page, int numpages)
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
