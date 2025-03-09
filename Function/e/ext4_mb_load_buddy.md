# Function: <code>ext4_mb_load_buddy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_mb_load_buddy(struct super_block * sb, ext4_group_t group, struct ext4_buddy * e4b)
```

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792176,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1112",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792176,
      "name": "ext4_mb_load_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582012664,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1251",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582102719,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1251",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582068805,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1249",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582218245,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1249",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408094,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582507518,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582676622,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582778670,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583090270,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1299",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583169230,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1275",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583196059,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1609",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583539275,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1613",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584072401,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1610",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584705122,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1567",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584928849,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1706",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585160401,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1722",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494444860,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227882480,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288198728,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273857348,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582747406,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582684574,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582737262,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
  "name": "ext4_mb_load_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582822542,
      "name": "ext4_mb_load_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1238",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int ext4_mb_load_buddy(struct super_block * sb, ext4_group_t group, struct ext4_buddy * e4b)
```
</details>
</li>
</ul>
