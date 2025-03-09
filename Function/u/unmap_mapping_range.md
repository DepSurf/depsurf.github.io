# Function: <code>unmap_mapping_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580671744,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2408",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_page",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache_range",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_fallocate",
        "fs/dax.c:__dax_fault",
        "fs/kernfs/file.c:kernfs_unmap_bin_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671744,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784432,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2480",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_fault",
        "fs/kernfs/file.c:kernfs_unmap_bin_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784432,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846912,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2498",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/kernfs/file.c:kernfs_unmap_bin_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846912,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892576,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2704",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_page",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:grab_mapping_entry",
        "fs/kernfs/file.c:kernfs_drain_open_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892576,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990048,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2825",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/kernfs/file.c:kernfs_drain_open_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990048,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127024,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2896",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/kernfs/file.c:kernfs_drain_open_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127024,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206272,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2633",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206272,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280688,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280688,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339408,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339408,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537152,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3074",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537152,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580528,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3237",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580528,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601680,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3328",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601680,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866256,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3426",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866256,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262720,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3585",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262720,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754640,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3557",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:unmap_and_kill",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754640,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970128,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3560",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:unmap_and_kill",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970128,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148672,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:3639",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:unmap_and_kill",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/gpu/drm/drm_drv.c:drm_dev_unplug",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148672,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492745392,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492745392,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226577528,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226577528,
      "name": "unmap_mapping_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286101536,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286101536,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272730188,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272730188,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308256,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308256,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252064,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252064,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299456,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299456,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void unmap_mapping_range(struct address_space * mapping, const loff_t holebegin, const loff_t holelen, int even_cows)
```

```json
{
  "name": "unmap_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363440,
      "name": "unmap_mapping_range",
      "external": true,
      "loc": "mm/memory.c:2726",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_pagecache_range",
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_pagecache",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/memory-failure.c:memory_failure",
        "fs/dax.c:dax_layout_busy_page",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "drivers/dax/bus.c:kill_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363440,
      "name": "unmap_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
