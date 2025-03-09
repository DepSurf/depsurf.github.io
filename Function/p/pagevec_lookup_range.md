# Function: <code>pagevec_lookup_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808000,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:983",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808000,
      "name": "pagevec_lookup_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945152,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:994",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945152,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021296,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:995",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021296,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085344,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1001",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085344,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141328,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141328,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326096,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1107",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326096,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368144,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1109",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368144,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387136,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1110",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387136,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636256,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1101",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636256,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002448,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1109",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002448,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492515464,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492515464,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226385408,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226385408,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285806624,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285806624,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272572624,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272572624,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110176,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110176,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057248,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057248,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101376,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101376,
      "name": "pagevec_lookup_range",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```

```json
{
  "name": "pagevec_lookup_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163632,
      "name": "pagevec_lookup_range",
      "external": true,
      "loc": "mm/swap.c:1041",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163632,
      "name": "pagevec_lookup_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int pagevec_lookup_range(struct pagevec * pvec, struct address_space * mapping, long unsigned int * start, long unsigned int end)
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
