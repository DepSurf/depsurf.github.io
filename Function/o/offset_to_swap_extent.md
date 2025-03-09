# Function: <code>offset_to_swap_extent</code>

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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581435136,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435136,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581499376,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499376,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581705954,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:204",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_do_scheduled_discard"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581753488,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:204",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753488,
      "name": "offset_to_swap_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581780592,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:203",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780592,
      "name": "offset_to_swap_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582080858,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:203",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582523614,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583041742,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:209",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583250286,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:210",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_page_sector"
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583484766,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:212",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapdev_block",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_folio_sector"
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
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492920592,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492920592,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226711776,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226711776,
      "name": "offset_to_swap_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286330032,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286330032,
      "name": "offset_to_swap_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272841306,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272841306,
      "name": "offset_to_swap_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468112,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581468112,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581410368,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410368,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459424,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459424,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "offset_to_swap_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525776,
      "name": "offset_to_swap_extent",
      "external": false,
      "loc": "mm/swapfile.c:205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525776,
      "name": "offset_to_swap_extent.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct swap_extent * offset_to_swap_extent(struct swap_info_struct * sis, long unsigned int offset)
```
</details>
</li>
</ul>
