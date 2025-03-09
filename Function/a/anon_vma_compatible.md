# Function: <code>anon_vma_compatible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580696677,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1133",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:reusable_anon_vma"
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
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580811045,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1035",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:reusable_anon_vma"
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
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580876405,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1188",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:reusable_anon_vma"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921376,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1204",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921376,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020992,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1205",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020992,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156064,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1214",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156064,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235856,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1238",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235856,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309920,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1240",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309920,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368464,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368464,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566784,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1222",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566784,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612224,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1260",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612224,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634800,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1264",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634800,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902672,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1261",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902672,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307264,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1273",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307264,
      "name": "anon_vma_compatible",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582811692,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1090",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804096,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025168,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1039",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017696,
      "name": "anon_vma_compatible",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583207911,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1067",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197344,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492774176,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492774176,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226592524,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286140736,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286140736,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272750254,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337312,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337312,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281024,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281024,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328512,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328512,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
```

```json
{
  "name": "anon_vma_compatible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392592,
      "name": "anon_vma_compatible",
      "external": false,
      "loc": "mm/mmap.c:1241",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:find_mergeable_anon_vma",
        "mm/mmap.c:find_mergeable_anon_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392592,
      "name": "anon_vma_compatible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
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
int anon_vma_compatible(struct vm_area_struct * a, struct vm_area_struct * b)
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
