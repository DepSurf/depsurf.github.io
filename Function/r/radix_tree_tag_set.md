# Function: <code>radix_tree_tag_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966208,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:592",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/buffer.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966208,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253392,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:762",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/buffer.c:__set_page_dirty",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253392,
      "name": "radix_tree_tag_set",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369472,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:1277",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/buffer.c:__set_page_dirty",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_insert_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369472,
      "name": "radix_tree_tag_set",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218176,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:1423",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/buffer.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218176,
      "name": "radix_tree_tag_set",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588768144,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:1421",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/shmem.c:shmem_add_seals",
        "fs/buffer.c:__set_page_dirty",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_mapping_entry",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768144,
      "name": "radix_tree_tag_set",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct radix_tree_root * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146944,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:1422",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_fcntl",
        "fs/buffer.c:__set_page_dirty",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_mapping_entry",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146944,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589382960,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:988",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382960,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589840064,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840064,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066160,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066160,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065232,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:967",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065232,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585214560,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:967",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214560,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097648,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:968",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097648,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:968",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343485,
      "name": "radix_tree_tag_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071585545328,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:968",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205021,
      "name": "radix_tree_tag_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071586700928,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:968",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374234,
      "name": "radix_tree_tag_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071595862544,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:967",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903735,
      "name": "radix_tree_tag_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071596379776,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:967",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597828828,
      "name": "radix_tree_tag_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071597275024,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503841936,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503841936,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236460928,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236460928,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297694048,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297694048,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279734092,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279734092,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668416,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668416,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589394240,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589394240,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111792,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111792,
      "name": "radix_tree_tag_set",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * radix_tree_tag_set(struct xarray * root, long unsigned int index, unsigned int tag)
```

```json
{
  "name": "radix_tree_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162160,
      "name": "radix_tree_tag_set",
      "external": true,
      "loc": "lib/radix-tree.c:975",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162160,
      "name": "radix_tree_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
