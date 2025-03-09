# Function: <code>find_inode_bit</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090272,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:741",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090272,
      "name": "find_inode_bit.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582279776,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:711",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279776,
      "name": "find_inode_bit.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582377296,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:711",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377296,
      "name": "find_inode_bit.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582545712,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:711",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545712,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582647840,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647840,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957664,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:711",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957664,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031824,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:715",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031824,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057456,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:716",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057456,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583395296,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:718",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395296,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910080,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:718",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910080,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535936,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:717",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535936,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765040,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:717",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765040,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998112,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:717",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998112,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494299824,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494299824,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227732792,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227732792,
      "name": "find_inode_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288016880,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288016880,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273741862,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273741862,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582616576,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616576,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582553744,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553744,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582606432,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606432,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_bit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582688960,
      "name": "find_inode_bit",
      "external": false,
      "loc": "fs/ext4/ialloc.c:709",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688960,
      "name": "find_inode_bit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int find_inode_bit(struct super_block * sb, ext4_group_t group, struct buffer_head * bitmap, long unsigned int * ino)
```
</details>
</li>
</ul>
