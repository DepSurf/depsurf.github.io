# Function: <code>pagevec_lookup_range_tag</code>

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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, int tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808048,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:992",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808048,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, int tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945200,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1003",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945200,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021344,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1004",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021344,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085392,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1010",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085392,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141376,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141376,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326144,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1116",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326144,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368192,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1118",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368192,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387184,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1119",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387184,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636304,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1110",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636304,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002512,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1118",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002512,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437920,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1122",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437920,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492515552,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492515552,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226385480,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226385480,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285806720,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285806720,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272572704,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272572704,
      "name": "pagevec_lookup_range_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110224,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110224,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057296,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057296,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101424,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101424,
      "name": "pagevec_lookup_range_tag",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
```

```json
{
  "name": "pagevec_lookup_range_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163680,
      "name": "pagevec_lookup_range_tag",
      "external": true,
      "loc": "mm/swap.c:1050",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163680,
      "name": "pagevec_lookup_range_tag",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, int tag)
```
</details>
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
<code>int tag</code> ➡️ <code>xa_mark_t tag</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
unsigned int pagevec_lookup_range_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, long unsigned int end, xa_mark_t tag)
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
