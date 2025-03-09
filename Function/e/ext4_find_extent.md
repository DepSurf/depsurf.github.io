# Function: <code>ext4_find_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744656,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:860",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744656,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939696,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:873",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939696,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029728,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:873",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029728,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892304,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:873",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892304,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042480,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:873",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042480,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235424,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:861",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235424,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331344,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:861",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331344,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500240,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500240,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600336,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600336,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911408,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:834",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911408,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983232,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:832",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983232,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583008976,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:833",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008976,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346016,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:872",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346016,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856016,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:874",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856016,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584480128,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:883",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480128,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584708864,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:883",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708864,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584941488,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:883",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941488,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494250432,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494250432,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227682464,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227682464,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287955200,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287955200,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273700844,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273700844,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569072,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569072,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582506240,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582506240,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559184,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559184,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
struct ext4_ext_path * ext4_find_extent(struct inode * inode, ext4_lblk_t block, struct ext4_ext_path * * orig_path, int flags)
```

```json
{
  "name": "ext4_find_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640400,
      "name": "ext4_find_extent",
      "external": true,
      "loc": "fs/ext4/extents.c:865",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640400,
      "name": "ext4_find_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
