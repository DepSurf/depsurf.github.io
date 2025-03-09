# Function: <code>__pagevec_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541248,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:984",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541248,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629504,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:810",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629504,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696720,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:810",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696720,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730496,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:823",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:filemap_range_has_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730496,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816496,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:834",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816496,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953552,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:806",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953552,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029712,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:808",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029712,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093744,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:814",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093744,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150528,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150528,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581336176,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:925",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336176,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379760,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:948",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379760,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400720,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:986",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400720,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:977",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592191395,
      "name": "__pagevec_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581651568,
      "name": "__pagevec_release",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:994",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593967078,
      "name": "__pagevec_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582020352,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:1090",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596025634,
      "name": "__pagevec_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582453024,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492527800,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492527800,
      "name": "__pagevec_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226394180,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226394180,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285821248,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285821248,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272580660,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272580660,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119376,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119376,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066368,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066368,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110576,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110576,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __pagevec_release(struct pagevec * pvec)
```

```json
{
  "name": "__pagevec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173664,
      "name": "__pagevec_release",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_seek_hole_data",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unlock_mapping",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173664,
      "name": "__pagevec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __pagevec_release(struct pagevec * pvec)
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
