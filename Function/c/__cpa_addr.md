# Function: <code>__cpa_addr</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359760,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:256",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359760,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374352,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374352,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378640,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378640,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579418260,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:264",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417696,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579418068,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:264",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417728,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579421268,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:272",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420800,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484852,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:272",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484384,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564596,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:275",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564016,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672660,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:293",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671984,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686564,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:294",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685888,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720932,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:294",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:cpa_process_alias",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720416,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374544,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374544,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304928,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304928,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374464,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374464,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```

```json
{
  "name": "__cpa_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382944,
      "name": "__cpa_addr",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:257",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:__cpa_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382944,
      "name": "__cpa_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int __cpa_addr(struct cpa_data * cpa, long unsigned int idx)
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
