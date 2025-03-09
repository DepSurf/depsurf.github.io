# Function: <code>wait_on_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580469981,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519306,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543464,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580562016,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587205,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767722,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886631,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952444,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198296,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564311,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821239,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:527",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580547779,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613919,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632201,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580654124,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684612,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891866,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015874,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105190,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361466,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749989,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016966,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:504",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580613880,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580681183,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699432,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580721308,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751693,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960269,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090064,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180353,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442714,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837717,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107014,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:522",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580642690,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714395,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732781,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756928,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786746,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006417,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137588,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228435,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497243,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984677,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582077266,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:530",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580724904,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790941,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819689,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844276,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580876136,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119241,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258984,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359543,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637819,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134122,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226708,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580860765,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927309,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956746,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580980480,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013381,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255537,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581404718,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508108,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800202,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321987,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582416510,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:543",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935358,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003325,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032730,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057506,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087075,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338811,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488192,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594038,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887338,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420196,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515968,
      "name": "wait_on_page_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:545",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066528,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2814",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066528,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581122496,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122496,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581310330,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2835",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:__unmap_and_move",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305760,
      "name": "wait_on_page_writeback.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071581305888,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348240,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2827",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:__unmap_and_move",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348240,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367360,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2824",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:__unmap_and_move",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367360,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615792,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2879",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:__unmap_and_move",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615792,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993968,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:30",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993968,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430336,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:30",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430336,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635552,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:31",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635552,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806912,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:31",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806912,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492494072,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492494072,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226364524,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/migrate.c:migrate_pages",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226364524,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285780960,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285780960,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272554742,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272554742,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091344,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091344,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038528,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038528,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581082544,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082544,
      "name": "wait_on_page_writeback",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_writeback(struct page * page)
```

```json
{
  "name": "wait_on_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581145072,
      "name": "wait_on_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145072,
      "name": "wait_on_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void wait_on_page_writeback(struct page * page)
```
</details>
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
