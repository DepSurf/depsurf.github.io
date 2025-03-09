# Function: <code>ext4_initialize_dirent_tail</code>

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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689840,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689840,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792032,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792032,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105488,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:303",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105488,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184544,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:299",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184544,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210944,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:301",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210944,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554960,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:302",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554960,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090448,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:325",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090448,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724064,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:330",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724064,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947424,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:330",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947424,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178736,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:330",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178736,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494461736,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494461736,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227897368,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227897368,
      "name": "ext4_initialize_dirent_tail",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288217200,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288217200,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273868926,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273868926,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760768,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760768,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697936,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697936,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751008,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751008,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
```

```json
{
  "name": "ext4_initialize_dirent_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582835904,
      "name": "ext4_initialize_dirent_tail",
      "external": true,
      "loc": "fs/ext4/namei.c:296",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835904,
      "name": "ext4_initialize_dirent_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void ext4_initialize_dirent_tail(struct buffer_head * bh, unsigned int blocksize)
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
