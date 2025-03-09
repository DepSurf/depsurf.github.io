# Function: <code>ext4_kvfree_array_rcu</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836624,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836624,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147470,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155088,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583229875,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236416,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261536,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261536,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604544,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604544,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584141088,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:35",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141088,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584775216,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:35",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775216,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584998560,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:35",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998560,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585230624,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:33",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585230624,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494510312,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494510312,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227947540,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227947540,
      "name": "ext4_kvfree_array_rcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288277456,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288277456,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273906446,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273906446,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805360,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805360,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742512,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742512,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794240,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794240,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void ext4_kvfree_array_rcu(void * to_free)
```

```json
{
  "name": "ext4_kvfree_array_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880720,
      "name": "ext4_kvfree_array_rcu",
      "external": true,
      "loc": "fs/ext4/resize.c:34",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_alloc_flex_bg_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880720,
      "name": "ext4_kvfree_array_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void ext4_kvfree_array_rcu(void * to_free)
```
</details>
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
