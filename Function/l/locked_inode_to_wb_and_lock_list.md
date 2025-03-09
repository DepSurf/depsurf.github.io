# Function: <code>locked_inode_to_wb_and_lock_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172048,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:268",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172048,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344112,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:268",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344112,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423216,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:268",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423216,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477440,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:282",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477440,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619584,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:282",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619584,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776976,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:282",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776976,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864816,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:282",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864816,
      "name": "locked_inode_to_wb_and_lock_list",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989568,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:284",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989568,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064848,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064848,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302704,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:290",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302704,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582355904,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:290",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355904,
      "name": "locked_inode_to_wb_and_lock_list",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383376,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:290",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383376,
      "name": "locked_inode_to_wb_and_lock_list",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705984,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:300",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705984,
      "name": "locked_inode_to_wb_and_lock_list",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247312,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:301",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247312,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828880,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:303",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828880,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584044416,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:303",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584044416,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259216,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:303",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259216,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493595736,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493595736,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227142884,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227142884,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287180416,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287180416,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273244112,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273244112,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033584,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033584,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971152,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971152,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024864,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024864,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct bdi_writeback * locked_inode_to_wb_and_lock_list(struct inode * inode)
```

```json
{
  "name": "locked_inode_to_wb_and_lock_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096080,
      "name": "locked_inode_to_wb_and_lock_list",
      "external": false,
      "loc": "fs/fs-writeback.c:289",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:inode_io_list_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096080,
      "name": "locked_inode_to_wb_and_lock_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
