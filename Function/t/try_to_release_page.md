# Function: <code>try_to_release_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580473376,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:2719",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_active_list",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473376,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550192,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:2892",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550192,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580612672,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3008",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612672,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580641072,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3142",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641072,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580723200,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3318",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723200,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580859152,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3318",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859152,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927680,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3387",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927680,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581023776,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3514",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023776,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581079088,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079088,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262512,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3505",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_complete_page2",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidatepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262512,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304512,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3599",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_complete_page2",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidatepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304512,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322560,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3847",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidatepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322560,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568176,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3958",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidatepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568176,
      "name": "try_to_release_page",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994736,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/folio-compat.c:148",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/migrate.c:move_to_new_folio",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994736,
      "name": "try_to_release_page",
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492442072,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492442072,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226318672,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226318672,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285714784,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285714784,
      "name": "try_to_release_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272518676,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272518676,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047936,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047936,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580995216,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995216,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039136,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039136,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int try_to_release_page(struct page * page, gfp_t gfp_mask)
```

```json
{
  "name": "try_to_release_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581100768,
      "name": "try_to_release_page",
      "external": true,
      "loc": "mm/filemap.c:3471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:move_to_new_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:block_invalidatepage",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100768,
      "name": "try_to_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int try_to_release_page(struct page * page, gfp_t gfp)
```
</details>
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
