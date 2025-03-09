# Function: <code>radix_tree_tag_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966352,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:638",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "lib/radix-tree.c:radix_tree_delete_item"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966352,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256672,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256672,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372384,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1367",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372384,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221680,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1497",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221680,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588771696,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1495",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771696,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * radix_tree_tag_clear(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589150416,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1496",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memfd.c:memfd_fcntl",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150416,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383968,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1050",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383968,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589841008,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841008,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590067104,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590067104,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063696,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063696,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212992,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212992,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097040,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1030",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097040,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1030",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343417,
      "name": "radix_tree_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585545120,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1030",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594204953,
      "name": "radix_tree_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586700720,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1030",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374166,
      "name": "radix_tree_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071595862320,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903674,
      "name": "radix_tree_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071596379552,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597828767,
      "name": "radix_tree_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071597274800,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503844512,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503844512,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236464024,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236464024,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297697856,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297697856,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279735062,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279735062,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589669360,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669360,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589395184,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395184,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590112736,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112736,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * radix_tree_tag_clear(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163104,
      "name": "radix_tree_tag_clear",
      "external": true,
      "loc": "lib/radix-tree.c:1037",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163104,
      "name": "radix_tree_tag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
