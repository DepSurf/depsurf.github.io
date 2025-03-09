# Function: <code>sync_global_pgds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end, int removed)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276400,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:166",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276400,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end, int removed)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275776,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:95",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275776,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291216,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:95",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291216,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288720,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:133",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288720,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307856,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:133",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307856,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589237382,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:181",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319888,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589481420,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:180",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344192,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589941134,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359856,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590168686,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364096,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390960,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:arch_sync_kernel_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390960,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591268344,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268344,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591210927,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591210927,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592084811,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:213",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592084811,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593851869,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593851869,
      "name": "sync_global_pgds",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637472,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637472,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579651520,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651520,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685392,
      "name": "sync_global_pgds",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685392,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589770974,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360000,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589493805,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291136,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590214382,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359920,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "sync_global_pgds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590264750,
      "name": "sync_global_pgds",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_sync_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368352,
      "name": "sync_global_pgds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int removed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end)
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
