# Function: <code>next_present_section_nr</code>

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
int next_present_section_nr(int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070929,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:191",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070929,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int next_present_section_nr(int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182045,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:187",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182045,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602997468,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:187",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604796633,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:188",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604899905,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:199",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604933780,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
long unsigned int next_present_section_nr(long unsigned int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800177,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1346",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800177,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long unsigned int next_present_section_nr(long unsigned int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591332589,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1384",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332589,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long unsigned int next_present_section_nr(long unsigned int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591275289,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1454",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591275289,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long unsigned int next_present_section_nr(long unsigned int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592215996,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1511",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215996,
      "name": "next_present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long unsigned int next_present_section_nr(long unsigned int section_nr)
```

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593994669,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1557",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593994669,
      "name": "next_present_section_nr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627888180,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1896",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619651158,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:2021",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621958166,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:2039",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510973544,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302629088,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270698404,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604839240,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604808301,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604916424,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
  "name": "next_present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604937951,
      "name": "next_present_section_nr",
      "external": false,
      "loc": "mm/sparse.c:201",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
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
int next_present_section_nr(int section_nr)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int next_present_section_nr(int section_nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr)
```
</details>
</li>
</ul>
