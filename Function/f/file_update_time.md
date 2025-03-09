# Function: <code>file_update_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103744,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1771",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:handle_mm_fault",
        "fs/pipe.c:pipe_write",
        "fs/dax.c:dax_pmd_fault",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_fault",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103744,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269392,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1788",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:handle_mm_fault",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269392,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347504,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1838",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347504,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402960,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1838",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402960,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544592,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1851",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544592,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699296,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1843",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699296,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785632,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1850",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785632,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903952,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1868",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903952,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976448,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976448,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210272,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1963",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210272,
      "name": "file_update_time",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257760,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1964",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257760,
      "name": "file_update_time",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283168,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1973",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283168,
      "name": "file_update_time",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601408,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1978",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601408,
      "name": "file_update_time",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137536,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:2059",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137536,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708880,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:2078",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708880,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926320,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:2122",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926320,
      "name": "file_update_time",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129584,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:2127",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/shmem.c:shmem_file_write_iter",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "block/fops.c:blkdev_write_iter",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129584,
      "name": "file_update_time",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493482504,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493482504,
      "name": "file_update_time",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227047124,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047124,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287043968,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287043968,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273160078,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273160078,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945184,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945184,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882752,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882752,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936496,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936496,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int file_update_time(struct file * file)
```

```json
{
  "name": "file_update_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007936,
      "name": "file_update_time",
      "external": true,
      "loc": "fs/inode.c:1879",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/prfile.c:vma_do_file_update_time",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/pipe.c:pipe_write",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007936,
      "name": "file_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
