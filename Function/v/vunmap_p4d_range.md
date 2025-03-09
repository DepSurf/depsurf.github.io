# Function: <code>vunmap_p4d_range</code>

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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580970408,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:105",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581072875,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:103",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581208752,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:103",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581292432,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:103",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581367027,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581426755,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629888,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:133",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629888,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675152,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:133",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675152,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581713400,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:358",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vunmap_range_noflush"
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581985296,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:386",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vunmap_range_noflush"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388608,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:387",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vunmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388608,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582894880,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:393",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894880,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110032,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:382",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110032,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292288,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:382",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vunmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292288,
      "name": "vunmap_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492828336,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226632884,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286213444,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vunmap_page_range"
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272782870,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581395603,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581336595,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581386803,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vunmap_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581451123,
      "name": "vunmap_p4d_range",
      "external": false,
      "loc": "mm/vmalloc.c:106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
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
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void vunmap_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, pgtbl_mod_mask * mask)
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
