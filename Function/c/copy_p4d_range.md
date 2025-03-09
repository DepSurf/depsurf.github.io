# Function: <code>copy_p4d_range</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905962,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1122",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581005735,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1190",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581140333,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1204",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581219034,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:947",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581292326,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581351062,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581548263,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:943",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591152,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1103",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591152,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617104,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1110",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617104,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875664,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1201",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875664,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280752,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1208",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280752,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582773296,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1165",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773296,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989488,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989488,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164736,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:1232",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164736,
      "name": "copy_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492754348,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226569616,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286114324,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272735374,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581319910,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581263999,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311110,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581375110,
      "name": "copy_p4d_range",
      "external": false,
      "loc": "mm/memory.c:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int copy_p4d_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pgd_t * dst_pgd, pgd_t * src_pgd, long unsigned int addr, long unsigned int end)
```
</details>
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
