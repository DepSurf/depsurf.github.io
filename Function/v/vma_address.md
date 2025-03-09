# Function: <code>vma_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "vma_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580722624,
      "name": "vma_address",
      "external": true,
      "loc": "mm/rmap.c:579",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk"
      ],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722624,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580838769,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:326",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580909329,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:329",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580955771,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:343",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581056955,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:344",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581196502,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:344",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501839,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:344",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581279849,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:344",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587087,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:344",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581353974,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698501,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581413478,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771941,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581614230,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:393",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992597,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:393",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581661542,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:397",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042178,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:397",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581675412,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:392",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682660,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:392",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068644,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:392",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581944612,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:389",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581952564,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:389",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382692,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:389",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350688,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:579",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ]
    },
    {
      "addr": 18446744071582366654,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:579",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885326,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:579",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350688,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582855594,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:577",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869625,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:577",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068352,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:648",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ]
    },
    {
      "addr": 18446744071583085472,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:648",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068352,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071583085472,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250288,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:728",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ]
    },
    {
      "addr": 18446744071583268080,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:728",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250288,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071583268080,
      "name": "vma_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492813744,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
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
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226622216,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286194252,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745408,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vma_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272774116,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581382326,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740677,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581325654,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679493,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581373526,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731989,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
  "name": "vma_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581437830,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800277,
      "name": "vma_address",
      "external": false,
      "loc": "mm/internal.h:352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
long unsigned int vma_address(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
