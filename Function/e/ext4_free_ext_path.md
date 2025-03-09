# Function: <code>ext4_free_ext_path</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_free_ext_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584506359,
      "name": "ext4_free_ext_path",
      "external": true,
      "loc": "fs/ext4/extents.c:122",
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
      "addr": 18446744071584476576,
      "name": "ext4_free_ext_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_free_ext_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734855,
      "name": "ext4_free_ext_path",
      "external": true,
      "loc": "fs/ext4/extents.c:122",
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
      "addr": 18446744071584705376,
      "name": "ext4_free_ext_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path * path)
```

```json
{
  "name": "ext4_free_ext_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584967383,
      "name": "ext4_free_ext_path",
      "external": true,
      "loc": "fs/ext4/extents.c:122",
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
      "addr": 18446744071584938000,
      "name": "ext4_free_ext_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path * path)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
