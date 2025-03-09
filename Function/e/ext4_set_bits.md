# Function: <code>ext4_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789040,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1325",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789040,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984016,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1334",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984016,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074256,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1334",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074256,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038688,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1332",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038688,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189040,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1332",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189040,
      "name": "ext4_set_bits",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378928,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378928,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478416,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478416,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647648,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647648,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582749648,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582749648,
      "name": "ext4_set_bits",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059696,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1382",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:mb_regenerate_buddy",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059696,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138128,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1354",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138128,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164848,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1688",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164848,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506592,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1692",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506592,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494414984,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494414984,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227847924,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227847924,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288155600,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288155600,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273829042,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273829042,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718384,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718384,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655552,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655552,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708240,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708240,
      "name": "ext4_set_bits",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
```

```json
{
  "name": "ext4_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792704,
      "name": "ext4_set_bits",
      "external": true,
      "loc": "fs/ext4/mballoc.c:1321",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792704,
      "name": "ext4_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ext4_set_bits(void * bm, int cur, int len)
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
