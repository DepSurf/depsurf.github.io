# Function: <code>move_normal_pmd</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581266284,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581340872,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581400194,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
bool move_normal_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597056,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597056,
      "name": "move_normal_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581643296,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:214",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643296,
      "name": "move_normal_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581664800,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:213",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664800,
      "name": "move_normal_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933376,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:223",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933376,
      "name": "move_normal_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342320,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:223",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342320,
      "name": "move_normal_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582843600,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:225",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843600,
      "name": "move_normal_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060032,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:236",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060032,
      "name": "move_normal_pmd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241504,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:236",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241504,
      "name": "move_normal_pmd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581369042,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312031,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581360242,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
  "name": "move_normal_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581424131,
      "name": "move_normal_pmd",
      "external": false,
      "loc": "mm/mremap.c:195",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
bool move_normal_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool move_normal_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```
</details>
</li>
</ul>
