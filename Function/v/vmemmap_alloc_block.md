# Function: <code>vmemmap_alloc_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360953,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:50",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360953,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587861960,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:51",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861960,
      "name": "vmemmap_alloc_block.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071587862108,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588076672,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:51",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588076672,
      "name": "vmemmap_alloc_block.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071588076814,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588303143,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:51",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303143,
      "name": "vmemmap_alloc_block.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071588303268,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588868377,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:52",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868377,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247381,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:52",
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
      "addr": 18446744071589247381,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489688,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071589489688,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589950649,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071589950649,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590178203,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071590178203,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591196517,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:48",
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
      "addr": 18446744071591196517,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591691409,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:48",
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
      "addr": 18446744071591691409,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591634233,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:48",
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
      "addr": 18446744071591634233,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592808568,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:402",
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
      "addr": 18446744071592808568,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594709666,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:448",
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
      "addr": 18446744071594709666,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596454208,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071596454208,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596995536,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071596995536,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597925024,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071597925024,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503921056,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446603336503921056,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297816436,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297816436,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270896476,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270896476,
      "name": "vmemmap_alloc_block",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780491,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071589780491,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503314,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071589503314,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590223899,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071590223899,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * vmemmap_alloc_block(long unsigned int size, int node)
```

```json
{
  "name": "vmemmap_alloc_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590274257,
      "name": "vmemmap_alloc_block",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:49",
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
      "addr": 18446744071590274257,
      "name": "vmemmap_alloc_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * vmemmap_alloc_block(long unsigned int size, int node)
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
