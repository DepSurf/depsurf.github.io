# Function: <code>__ext4_ext_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742672,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:159",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742672,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937712,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:164",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937712,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027744,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:164",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027744,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890336,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:164",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890336,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040512,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:164",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040512,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228864,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228864,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323984,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323984,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524931,
      "name": "__ext4_ext_dirty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582494128,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593664,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593664,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898528,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:155",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898528,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970448,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:155",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents_endio",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970448,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996240,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:155",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996240,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333968,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:166",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333968,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843104,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:166",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843104,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466992,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466992,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584695888,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695888,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584928576,
      "name": "__ext4_ext_dirty",
      "external": false,
      "loc": "fs/ext4/extents.c:185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_replay_shrink_inode",
        "fs/ext4/extents.c:ext4_ext_replay_update_ex",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:convert_initialized_extent",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_insert_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584928576,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494243728,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494243728,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227675060,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227675060,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287946368,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287946368,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273695002,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273695002,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562400,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562400,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499568,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499568,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552512,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552512,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int __ext4_ext_dirty(const char * where, unsigned int line, handle_t * handle, struct inode * inode, struct ext4_ext_path * path)
```

```json
{
  "name": "__ext4_ext_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633696,
      "name": "__ext4_ext_dirty",
      "external": true,
      "loc": "fs/ext4/extents.c:152",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_shift_extents",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_correct_indexes",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633696,
      "name": "__ext4_ext_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
