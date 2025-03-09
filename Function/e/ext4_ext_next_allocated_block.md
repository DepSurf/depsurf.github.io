# Function: <code>ext4_ext_next_allocated_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745456,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1595",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745456,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940416,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1601",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940416,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030448,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1601",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030448,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892992,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1601",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892992,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043168,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1601",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043168,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236192,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1595",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236192,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332112,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1595",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332112,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582501872,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501872,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601968,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601968,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912816,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1593",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_determine_hole",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912816,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984640,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1592",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_determine_hole",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984640,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010064,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1595",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010064,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347104,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1633",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347104,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857072,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1634",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857072,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584481200,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1642",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481200,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584710032,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1642",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584710032,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584942656,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1642",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_determine_insert_hole",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942656,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494252072,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494252072,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227684160,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227684160,
      "name": "ext4_ext_next_allocated_block",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287956192,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287956192,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273702204,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273702204,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570704,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570704,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507872,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507872,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560816,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560816,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ext4_lblk_t ext4_ext_next_allocated_block(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_next_allocated_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642016,
      "name": "ext4_ext_next_allocated_block",
      "external": true,
      "loc": "fs/ext4/extents.c:1612",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642016,
      "name": "ext4_ext_next_allocated_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
