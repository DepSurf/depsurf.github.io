# Function: <code>xas_find_marked</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424176,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1122",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_entries_tag",
        "mm/filemap.c:find_get_entries_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589424176,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589881792,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1141",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881792,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590107728,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107728,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112128,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112128,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261632,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1300",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261632,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585145200,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1301",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145200,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1301",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592344711,
      "name": "xas_find_marked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071585596112,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1308",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206267,
      "name": "xas_find_marked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586751392,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1308",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375233,
      "name": "xas_find_marked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071595915440,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1306",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596904746,
      "name": "xas_find_marked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071596433232,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1306",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829839,
      "name": "xas_find_marked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071597328592,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503889648,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503889648,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236518040,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236518040,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297755232,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297755232,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279781246,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279781246,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589709984,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709984,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435776,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435776,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153360,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153360,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```

```json
{
  "name": "xas_find_marked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590203760,
      "name": "xas_find_marked",
      "external": true,
      "loc": "lib/xarray.c:1150",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find",
        "lib/xarray.c:__xa_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590203760,
      "name": "xas_find_marked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * xas_find_marked(struct xa_state * xas, long unsigned int max, xa_mark_t mark)
```
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
