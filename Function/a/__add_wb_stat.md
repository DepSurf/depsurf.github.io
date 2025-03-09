# Function: <code>__add_wb_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580519826,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:57",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:wb_writeout_inc",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181393,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:57",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085141,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:57",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580605904,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344561,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313647,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580673202,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423668,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401981,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:58",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580710996,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478283,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485912,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796564,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:65",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620443,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:65",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637112,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:65",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580936609,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779543,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830600,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004198,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866119,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933904,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:66",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068498,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581990849,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113961,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581124466,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066943,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219753,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __add_wb_stat(struct bdi_writeback * wb, enum wb_stat_item item, s64 amount)
```

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581304352,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ]
    },
    {
      "addr": 18446744071582288992,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    },
    {
      "addr": 18446744071583522064,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304352,
      "name": "__add_wb_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071582288992,
      "name": "__add_wb_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583522064,
      "name": "__add_wb_stat.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581358026,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355496,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656956,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581377228,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382976,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677696,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581626214,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704782,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036582,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:67",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492499364,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493595052,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494939896,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226366116,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 3227142240,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3228350196,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285783024,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287183072,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288813348,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272556706,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273244778,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274245456,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581093314,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035679,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188489,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581040476,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973241,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125641,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581084514,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026959,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172521,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_wb_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581146434,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099841,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266221,
      "name": "__add_wb_stat",
      "external": false,
      "loc": "include/linux/backing-dev.h:71",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __add_wb_stat(struct bdi_writeback * wb, enum wb_stat_item item, s64 amount)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __add_wb_stat(struct bdi_writeback * wb, enum wb_stat_item item, s64 amount)
```
</details>
</li>
</ul>
