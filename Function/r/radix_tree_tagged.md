# Function: <code>radix_tree_tagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int radix_tree_tagged(struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965776,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1438",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:mapping_tagged",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965776,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int radix_tree_tagged(struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252816,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1613",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252816,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int radix_tree_tagged(struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368704,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1924",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368704,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588217680,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:2091",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217680,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int radix_tree_tagged(const struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767648,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:2088",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767648,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int radix_tree_tagged(const struct radix_tree_root * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589156523,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:2089",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146704,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589386507,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381088,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589843580,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838208,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590069676,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064304,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585066735,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1457",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061152,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216063,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1457",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210448,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585098895,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1458",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093440,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585547161,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1458",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342765,
      "name": "radix_tree_tagged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585542528,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586703030,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1458",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594204327,
      "name": "radix_tree_tagged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586697648,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595864838,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1458",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373526,
      "name": "radix_tree_tagged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071595858512,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596382182,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1456",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903197,
      "name": "radix_tree_tagged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071596375408,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597277430,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1456",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597828290,
      "name": "radix_tree_tagged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071597270656,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503847648,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503841664,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236467276,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236460652,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297701900,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297693264,
      "name": "radix_tree_tagged",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279737572,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279732194,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589671932,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666560,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589397756,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392384,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590115308,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109936,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int radix_tree_tagged(const struct xarray * root, unsigned int tag)
```

```json
{
  "name": "radix_tree_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590165692,
      "name": "radix_tree_tagged",
      "external": true,
      "loc": "lib/radix-tree.c:1465",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590160272,
      "name": "radix_tree_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>const struct radix_tree_root * root</code>
</li>
</ul>
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
<code>const struct radix_tree_root * root</code> ➡️ <code>const struct xarray * root</code>
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
