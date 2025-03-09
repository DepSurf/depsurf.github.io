# Function: <code>subsection_mask_set</code>

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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522400,
      "name": "subsection_mask_set",
      "external": true,
      "loc": "mm/sparse.c:220",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522400,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586992,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586992,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799008,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:212",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799008,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846912,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:211",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846912,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581877744,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:211",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877744,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169344,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:185",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169344,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627104,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:185",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627104,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151440,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:185",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151440,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361776,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:185",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361776,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598224,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:184",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598224,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493024984,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493024984,
      "name": "subsection_mask_set",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286454224,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286454224,
      "name": "subsection_mask_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270697794,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_map_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555728,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555728,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497376,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497376,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547040,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547040,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```

```json
{
  "name": "subsection_mask_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612160,
      "name": "subsection_mask_set",
      "external": false,
      "loc": "mm/sparse.c:222",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:subsection_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612160,
      "name": "subsection_mask_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void subsection_mask_set(long unsigned int * map, long unsigned int pfn, long unsigned int nr_pages)
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
