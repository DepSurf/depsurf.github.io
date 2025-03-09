# Function: <code>ext4_ext_drop_refs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744000,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:710",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744000,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939024,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939024,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029056,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029056,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891664,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891664,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041840,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041840,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234768,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:711",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234768,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330688,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:711",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330688,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499616,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499616,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599152,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599152,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932869,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:684",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
      ],
      "caller_func": [
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911248,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007362,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:684",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
      ],
      "caller_func": [
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983072,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033090,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:684",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
      ],
      "caller_func": [
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008800,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583369794,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
      ],
      "caller_func": [
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345840,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881879,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:723",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
      ],
      "caller_func": [
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855808,
      "name": "ext4_ext_drop_refs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584506359,
      "name": "ext4_ext_drop_refs",
      "external": false,
      "loc": "fs/ext4/extents.c:109",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584734855,
      "name": "ext4_ext_drop_refs",
      "external": false,
      "loc": "fs/ext4/extents.c:109",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584967383,
      "name": "ext4_ext_drop_refs",
      "external": false,
      "loc": "fs/ext4/extents.c:109",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_ext_precache"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494249176,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494249176,
      "name": "ext4_ext_drop_refs",
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227681060,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227681060,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287953520,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287953520,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273699770,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273699770,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567888,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567888,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505056,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505056,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558000,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558000,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void ext4_ext_drop_refs(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_ext_drop_refs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639216,
      "name": "ext4_ext_drop_refs",
      "external": true,
      "loc": "fs/ext4/extents.c:715",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_clu_mapped",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/extents.c:ext4_find_extent",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639216,
      "name": "ext4_ext_drop_refs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path * path)
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
