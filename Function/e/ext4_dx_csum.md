# Function: <code>ext4_dx_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604624,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:417",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604624,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796928,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:417",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796928,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886400,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:417",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886400,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082000,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:417",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082000,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231616,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:418",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231616,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421520,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:419",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421520,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521008,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:420",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521008,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689616,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689616,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791808,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791808,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583104720,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:442",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583104720,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583183776,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:438",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583183776,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210400,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:440",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210400,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553840,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:441",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553840,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089632,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:464",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089632,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584723200,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:469",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584723200,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946560,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:469",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946560,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585177888,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:471",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_handle_dirty_dx_node",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177888,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494461296,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494461296,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227896968,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227896968,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288216880,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288216880,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273868716,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273868716,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760544,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760544,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697712,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697712,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750784,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750784,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
__le32 ext4_dx_csum(struct inode * inode, struct ext4_dir_entry * dirent, int count_offset, int count, struct dx_tail * t)
```

```json
{
  "name": "ext4_dx_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582835680,
      "name": "ext4_dx_csum",
      "external": false,
      "loc": "fs/ext4/namei.c:435",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835680,
      "name": "ext4_dx_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
