# Function: <code>radix_tree_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582969121,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:326",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_create"
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
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583257700,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:492",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_create"
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
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583374022,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:533",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_create"
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
int radix_tree_extend(struct radix_tree_root * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588222656,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:619",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222656,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int radix_tree_extend(struct radix_tree_root * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772720,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:619",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free_cmn",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772720,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int radix_tree_extend(struct radix_tree_root * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151232,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:620",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151232,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589384816,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:430",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384816,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589841824,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841824,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590067920,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590067920,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062608,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062608,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211904,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211904,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094880,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094880,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542576,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071592342795,
      "name": "radix_tree_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697712,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071594204357,
      "name": "radix_tree_extend.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:409",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595858592,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071596373556,
      "name": "radix_tree_extend.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:408",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375488,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071596903227,
      "name": "radix_tree_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:408",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597270736,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071597828320,
      "name": "radix_tree_extend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503845432,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503845432,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236465276,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236465276,
      "name": "radix_tree_extend",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297699248,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297699248,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279735922,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279735922,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589670176,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589670176,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396000,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589396000,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590113552,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590113552,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct xarray * root, gfp_t gfp, long unsigned int index, unsigned int shift)
```

```json
{
  "name": "radix_tree_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163936,
      "name": "radix_tree_extend",
      "external": false,
      "loc": "lib/radix-tree.c:417",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163936,
      "name": "radix_tree_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int radix_tree_extend(struct radix_tree_root * root, gfp_t gfp, long unsigned int index, unsigned int shift)
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
