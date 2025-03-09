# Function: <code>ext4_handle_dirty_dirblock</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693328,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693328,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795520,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795520,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108720,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:406",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108720,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187760,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:402",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187760,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214912,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:404",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214912,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583558960,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:405",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558960,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095200,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:428",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095200,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584728976,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:433",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728976,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584952256,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:433",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584952256,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585183584,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:434",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585183584,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494465608,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494465608,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227901808,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227901808,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288222032,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288222032,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273871892,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273871892,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764256,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764256,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582701424,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701424,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754496,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754496,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_handle_dirty_dirblock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839392,
      "name": "ext4_handle_dirty_dirblock",
      "external": true,
      "loc": "fs/ext4/namei.c:399",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839392,
      "name": "ext4_handle_dirty_dirblock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ext4_handle_dirty_dirblock(handle_t * handle, struct inode * inode, struct buffer_head * bh)
```
</details>
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
