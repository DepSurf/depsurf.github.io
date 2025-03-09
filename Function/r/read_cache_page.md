# Function: <code>read_cache_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476256,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2291",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/symlink.c:ext4_encrypted_follow_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476256,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554848,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2468",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:SyS_swapon",
        "fs/namei.c:page_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554848,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580619984,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2584",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:SyS_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619984,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649616,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2718",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649616,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580733648,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2888",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SYSC_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733648,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869120,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2888",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869120,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940704,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2865",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940704,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035120,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2915",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035120,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090688,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090688,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282272,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2878",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:copy_insn",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partitions/core.c:read_part_sector",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282272,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326256,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3195",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:copy_insn",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partitions/core.c:read_part_sector",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326256,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337936,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3442",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partitions/core.c:read_part_sector",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337936,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586240,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3557",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partitions/core.c:read_part_sector",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586240,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, filler_t * filler, struct file * file)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942752,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3608",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partitions/core.c:read_part_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942752,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, filler_t * filler, struct file * file)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582377216,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3602",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377216,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, filler_t * filler, struct file * file)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585504,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3770",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585504,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, filler_t * filler, struct file * file)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756928,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:3777",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756928,
      "name": "read_cache_page",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492456360,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492456360,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226330676,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:vfs_dedupe_get_page",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226330676,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285733360,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:vfs_dedupe_get_page",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285733360,
      "name": "read_cache_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272528122,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:vfs_dedupe_get_page",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272528122,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059536,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059536,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006768,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006768,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050736,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050736,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct page * read_cache_page(struct address_space * mapping, long unsigned int index, int (*)(void *, struct page *) filler, void * data)
```

```json
{
  "name": "read_cache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112384,
      "name": "read_cache_page",
      "external": true,
      "loc": "mm/filemap.c:2869",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:prepare_uprobe",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/namei.c:page_get_link",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "block/partition-generic.c:read_dev_sector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112384,
      "name": "read_cache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(void *, struct page *) filler</code> ➡️ <code>filler_t * filler</code>
</li>
</ul>
</details>
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
