# Function: <code>ext4_free_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829904,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:1008",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829904,
      "name": "ext4_free_data",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025904,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:896",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025904,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116032,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:896",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116032,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955232,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:897",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955232,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104288,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104288,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582292448,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:904",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292448,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391200,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:904",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391200,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560144,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560144,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661088,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661088,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972960,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:902",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972960,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048576,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:903",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048576,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074176,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:903",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074176,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412704,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:906",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412704,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928224,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:906",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928224,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554448,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:913",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554448,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783200,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:921",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783200,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016064,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:921",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016064,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494313552,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494313552,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227749180,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227749180,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288033600,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288033600,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273753328,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273753328,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629824,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629824,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566992,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566992,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619680,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619680,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void ext4_free_data(handle_t * handle, struct inode * inode, struct buffer_head * this_bh, __le32 * first, __le32 * last)
```

```json
{
  "name": "ext4_free_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582701840,
      "name": "ext4_free_data",
      "external": false,
      "loc": "fs/ext4/indirect.c:898",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701840,
      "name": "ext4_free_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
