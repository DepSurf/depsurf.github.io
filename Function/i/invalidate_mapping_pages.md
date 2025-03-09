# Function: <code>invalidate_mapping_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546784,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:454",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546784,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636192,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:465",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636192,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703280,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:494",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703280,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736832,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:493",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736832,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823808,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823808,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960624,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:542",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/fadvise.c:ksys_fadvise64_64",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960624,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036848,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:543",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:vfs_fadvise",
        "mm/fadvise.c:vfs_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036848,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:vfs_fadvise",
        "mm/fadvise.c:vfs_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101580,
      "name": "invalidate_mapping_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581100704,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157648,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157648,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343536,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343536,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 947
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386240,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:632",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386240,
      "name": "invalidate_mapping_pages",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406048,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:529",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406048,
      "name": "invalidate_mapping_pages",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657312,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:530",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:invalidate_bdev",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657312,
      "name": "invalidate_mapping_pages",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027456,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:564",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:__invalidate_device",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027456,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461120,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:556",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:__invalidate_device",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461120,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666272,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:556",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/libfs.c:direct_write_fallback",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "block/bdev.c:__invalidate_device",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666272,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837152,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/libfs.c:direct_write_fallback",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "block/bdev.c:bdev_mark_dead",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837152,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492535712,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492535712,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226400836,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226400836,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285831552,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285831552,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272586292,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272586292,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126496,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126496,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073456,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073456,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117696,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117696,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
long unsigned int invalidate_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180160,
      "name": "invalidate_mapping_pages",
      "external": true,
      "loc": "mm/truncate.c:546",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "fs/inode.c:inode_lru_isolate",
        "fs/block_dev.c:invalidate_bdev",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/md/md-bitmap.c:md_bitmap_file_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180160,
      "name": "invalidate_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
