# Function: <code>ext4_es_remove_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843824,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843824,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038688,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038688,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582128800,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128800,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927920,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927920,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078240,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:945",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078240,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266160,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266160,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363472,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1066",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363472,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531440,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1066",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531440,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632560,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632560,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941616,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941616,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016048,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1433",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016048,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041584,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1433",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041584,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379008,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1433",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379008,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892224,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1433",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892224,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584517216,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1431",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517216,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584745664,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1463",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584745664,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584978368,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1495",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978368,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494283304,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494283304,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227717544,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227717544,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287996208,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287996208,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273728588,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273728588,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601296,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601296,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582538464,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582538464,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582591408,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582591408,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int ext4_es_remove_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_remove_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673216,
      "name": "ext4_es_remove_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1415",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/ioctl.c:swap_inode_data",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673216,
      "name": "ext4_es_remove_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
