# Function: <code>ext4_es_is_delayed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582034938,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents"
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
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582125050,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents"
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
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581924258,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:118",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582074526,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:119",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:119",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582262550,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:119",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged",
        "fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582323580,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:119",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_da_get_block_prep"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582319648,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582365228,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582425629,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319648,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582414320,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582486752,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582533190,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583296,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:171",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486752,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582583264,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582586792,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634694,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684256,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586000,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582684224,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582896776,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936706,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995376,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895424,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582995344,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582968696,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011138,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071056,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967424,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583071024,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028354,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043726,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096784,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993488,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583096736,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583331308,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583372238,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436432,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329952,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583436384,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583840886,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886135,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583955152,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838624,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583955072,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584464310,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510887,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582224,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462240,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071584582112,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584693196,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584740727,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584808944,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584691136,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071584808832,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584925884,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584972999,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585059042,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923824,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071585041712,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494236484,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494286056,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494338856,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494235752,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446603336494338824,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227669408,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3227719940,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 3227772956,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227665944,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3227772892,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287940508,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287999356,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged",
        "fs/ext4/extents_status.c:ext4_es_free_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288064352,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287935952,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 13835058055288064304,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273691182,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273730564,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273771458,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273688274,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446743936273771418,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555528,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603430,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652992,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554736,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582652960,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582492696,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540598,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582590160,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491904,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582590128,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582545640,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593542,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582642848,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544848,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582642816,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delayed(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delayed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582626760,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fill_es_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675609,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_can_be_merged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726144,
      "name": "ext4_es_is_delayed",
      "external": false,
      "loc": "fs/ext4/extents_status.h:172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_es_is_delonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625968,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582726112,
      "name": "ext4_es_is_delayed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int ext4_es_is_delayed(struct extent_status * es)
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
