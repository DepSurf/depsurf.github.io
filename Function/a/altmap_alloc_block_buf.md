# Function: <code>altmap_alloc_block_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587862305,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:129",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf"
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
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588077011,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:129",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf"
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
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588303466,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:129",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf"
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
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588868737,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf"
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247702,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:116",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247702,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489988,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489988,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589950953,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589950953,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590178507,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178507,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591196812,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:104",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591196812,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591691716,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
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
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591634517,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592808254,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:459",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592808254,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594709336,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:505",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594709336,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596453472,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:106",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596453472,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596994800,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:106",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596994800,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597924288,
      "name": "altmap_alloc_block_buf",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:106",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597924288,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503921444,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503921444,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297816912,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297816912,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270896720,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270896720,
      "name": "altmap_alloc_block_buf",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780795,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780795,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503618,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503618,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590224203,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590224203,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```

```json
{
  "name": "altmap_alloc_block_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590274561,
      "name": "altmap_alloc_block_buf",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:105",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590274561,
      "name": "altmap_alloc_block_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```
</details>
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
void * altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap * altmap)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
