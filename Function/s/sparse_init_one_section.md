# Function: <code>sparse_init_one_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595149806,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:232",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_add_one_section"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587861845,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:234",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588076557,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:234",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init"
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588303024,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:274",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init"
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588868253,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:280",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, long unsigned int * pageblock_bitmap)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246873,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:260",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246873,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589489214,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:282",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489214,
      "name": "sparse_init_one_section.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589949939,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:331",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589949939,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590177450,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590177450,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591195687,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:328",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195687,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591690646,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:327",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591690646,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591633496,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:327",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591633496,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592807512,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:301",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592807512,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594708596,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:301",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594708596,
      "name": "sparse_init_one_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596453151,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:301",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596994479,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:301",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597923890,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:300",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503920124,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503920124,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297815260,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297815260,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270697380,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589779738,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589779738,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589502561,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589502561,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590223146,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590223146,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "sparse_init_one_section",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590273504,
      "name": "sparse_init_one_section",
      "external": false,
      "loc": "mm/sparse.c:333",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273504,
      "name": "sparse_init_one_section.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, long unsigned int * pageblock_bitmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, long unsigned int * pageblock_bitmap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
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
void sparse_init_one_section(struct mem_section * ms, long unsigned int pnum, struct page * mem_map, struct mem_section_usage * usage, long unsigned int flags)
```
</details>
</li>
</ul>
