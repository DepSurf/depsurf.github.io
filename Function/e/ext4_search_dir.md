# Function: <code>ext4_search_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, const struct qstr * d_name, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612992,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1265",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612992,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, const struct qstr * d_name, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805392,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1274",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805392,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, const struct qstr * d_name, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894816,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1276",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894816,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089408,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1276",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089408,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239008,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1277",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239008,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428768,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1278",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428768,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528288,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1279",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528288,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698096,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698096,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800304,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800304,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112688,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1382",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112688,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191696,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1371",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191696,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219616,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1458",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219616,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563328,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1459",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563328,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099584,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1505",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099584,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584733216,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1510",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584733216,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956544,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1526",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956544,
      "name": "ext4_search_dir",
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187632,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1530",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187632,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494470264,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494470264,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227906312,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227906312,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288228224,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288228224,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273875528,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273875528,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769040,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769040,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582706208,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706208,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758480,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758480,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_search_dir(struct buffer_head * bh, char * search_buf, int buf_size, struct inode * dir, struct ext4_filename * fname, unsigned int offset, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_search_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844192,
      "name": "ext4_search_dir",
      "external": true,
      "loc": "fs/ext4/namei.c:1378",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/inline.c:ext4_find_inline_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844192,
      "name": "ext4_search_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct qstr * d_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>bh, search_buf, buf_size, dir, fname, d_name, offset, res_dir</code> ➡️ <code>bh, search_buf, buf_size, dir, fname, offset, res_dir</code>
</li>
</ul>
</details>
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
