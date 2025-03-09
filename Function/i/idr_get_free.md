# Function: <code>idr_get_free</code>

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
void * * idr_get_free(struct radix_tree_root * root, struct radix_tree_iter * iter, gfp_t gfp, int end)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588227872,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:2141",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227872,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588752818,
      "name": "idr_get_free",
      "external": false,
      "loc": "include/linux/radix-tree.h:362",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc_cmn"
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
void * * idr_get_free(struct radix_tree_root * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589156432,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:2139",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589156432,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386416,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1498",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386416,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843488,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843488,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069584,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069584,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066640,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1477",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066640,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215968,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1477",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215968,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098800,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098800,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343900,
      "name": "idr_get_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071585547056,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205432,
      "name": "idr_get_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071586702928,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374645,
      "name": "idr_get_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071595864736,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1476",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596904161,
      "name": "idr_get_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071596382080,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1476",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829254,
      "name": "idr_get_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071597277328,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503847552,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503847552,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236467188,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236467188,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297701760,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297701760,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279737472,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279737472,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671840,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671840,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397664,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397664,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115216,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115216,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void * * idr_get_free(struct xarray * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```

```json
{
  "name": "idr_get_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165600,
      "name": "idr_get_free",
      "external": true,
      "loc": "lib/radix-tree.c:1485",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165600,
      "name": "idr_get_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void * * idr_get_free(struct radix_tree_root * root, struct radix_tree_iter * iter, gfp_t gfp, int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void * * idr_get_free(struct radix_tree_root * root, struct radix_tree_iter * iter, gfp_t gfp, int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * * idr_get_free(struct radix_tree_root * root, struct radix_tree_iter * iter, gfp_t gfp, long unsigned int max)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
