# Function: <code>dev_pagemap_mapping_shift</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581501839,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:267",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581587087,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:268",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698496,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:265",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698496,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771936,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771936,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992592,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:265",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992592,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042160,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:289",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042160,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068624,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:293",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068624,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:305",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382672,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071592227024,
      "name": "dev_pagemap_mapping_shift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:300",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885312,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    },
    {
      "addr": 18446744071594005994,
      "name": "dev_pagemap_mapping_shift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:322",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435040,
      "name": "dev_pagemap_mapping_shift.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596049321,
      "name": "dev_pagemap_mapping_shift.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:380",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:__add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650032,
      "name": "dev_pagemap_mapping_shift.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071596571767,
      "name": "dev_pagemap_mapping_shift.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:376",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:__add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844944,
      "name": "dev_pagemap_mapping_shift.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071597476286,
      "name": "dev_pagemap_mapping_shift.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286745408,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740672,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740672,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581679493,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731984,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731984,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "dev_pagemap_mapping_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800272,
      "name": "dev_pagemap_mapping_shift",
      "external": false,
      "loc": "mm/memory-failure.c:264",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800272,
      "name": "dev_pagemap_mapping_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
