# Function: <code>ext4_mb_mark_bb</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160224,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3290",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_del_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160224,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583186704,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3822",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186704,
      "name": "ext4_mb_mark_bb",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3893",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592264514,
      "name": "ext4_mb_mark_bb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583529840,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3890",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594046234,
      "name": "ext4_mb_mark_bb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071584063472,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
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
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3860",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596079132,
      "name": "ext4_mb_mark_bb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071584696352,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
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
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4079",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596602374,
      "name": "ext4_mb_mark_bb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584921600,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1050
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
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, bool state)
```

```json
{
  "name": "ext4_mb_mark_bb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_bb",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4151",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597507891,
      "name": "ext4_mb_mark_bb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585154432,
      "name": "ext4_mb_mark_bb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ext4_mb_mark_bb(struct super_block * sb, ext4_fsblk_t block, int len, int state)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int state</code> ➡️ <code>bool state</code>
</li>
</ul>
</details>
</li>
</ul>
