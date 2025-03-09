# Function: <code>ext4_xattr_shift_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n, int blocksize)
```

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846672,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:1230",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846672,
      "name": "ext4_xattr_shift_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n, int blocksize)
```

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582041840,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:1319",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041840,
      "name": "ext4_xattr_shift_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582140805,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:1320",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582246444,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2469",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582395404,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2505",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585904,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582687270,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2520",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582860122,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582964282,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583279978,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2508",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583381210,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2515",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583403543,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2515",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583747879,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2498",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584304972,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2513",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n)
```

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932496,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2533",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932496,
      "name": "ext4_xattr_shift_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n)
```

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160032,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2576",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160032,
      "name": "ext4_xattr_shift_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n)
```

```json
{
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392752,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2576",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392752,
      "name": "ext4_xattr_shift_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494639304,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228084468,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288450444,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274009366,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582933018,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582870170,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582921626,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_shift_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583008682,
      "name": "ext4_xattr_shift_entries",
      "external": false,
      "loc": "fs/ext4/xattr.c:2521",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n, int blocksize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry * entry, int value_offs_shift, void * to, void * from, size_t n)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
