# Function: <code>__swap_info_get</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993296,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1001",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:_swap_info_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993296,
      "name": "__swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099024,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1036",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:_swap_info_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099024,
      "name": "__swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1036",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:_swap_info_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239776,
      "name": "__swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071581263496,
      "name": "__swap_info_get.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1066",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:_swap_info_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323200,
      "name": "__swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581346664,
      "name": "__swap_info_get.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581434501,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498741,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581704501,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1140",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581752229,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1156",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581779637,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1155",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582063093,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1124",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492919736,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226709812,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286327056,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272840550,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581467477,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581409733,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581458789,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
  "name": "__swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581523221,
      "name": "__swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1104",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_swap_info_get"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct swap_info_struct * __swap_info_get(swp_entry_t entry)
```
</details>
</li>
</ul>
