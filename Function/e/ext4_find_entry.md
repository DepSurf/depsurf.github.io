# Function: <code>ext4_find_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613344,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1344",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613344,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1796
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805712,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1353",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805712,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1789
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895136,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1355",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895136,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1789
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090112,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1337",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090112,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239712,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1338",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239712,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429488,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1339",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429488,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529008,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1340",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529008,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582700096,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1581",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700096,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802304,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802304,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114768,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1588",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_delete",
        "fs/ext4/namei.c:ext4_rename_delete",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114768,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583193776,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1577",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename_delete",
        "fs/ext4/namei.c:ext4_rename_delete",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583193776,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221440,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1664",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221440,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565248,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1665",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565248,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113626,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1711",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_get_parent"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101616,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584747146,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1716",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_get_parent"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735280,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970762,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1731",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_get_parent"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958784,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585201786,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1735",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_get_parent"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_resetent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189872,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494472312,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494472312,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227908360,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227908360,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288231168,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288231168,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273877088,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273877088,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771040,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771040,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708208,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708208,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760288,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760288,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct buffer_head * ext4_find_entry(struct inode * dir, const struct qstr * d_name, struct ext4_dir_entry_2 * * res_dir, int * inlined)
```

```json
{
  "name": "ext4_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846192,
      "name": "ext4_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1582",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846192,
      "name": "ext4_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
