# Function: <code>fuse_conn_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582102624,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:625",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102624,
      "name": "fuse_conn_put",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582318384,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:635",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318384,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582406752,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:636",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406752,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582490512,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:629",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490512,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582641712,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:629",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641712,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582835104,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:632",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835104,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582939888,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:635",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939888,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583120048,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120048,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583226576,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226576,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583550736,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:648",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583550736,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583662352,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:722",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662352,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583683392,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:762",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683392,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584042384,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:809",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_kill_sb_blk",
        "fs/fuse/inode.c:fuse_kill_sb_anon",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042384,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584631136,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:851",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_kill_sb_blk",
        "fs/fuse/inode.c:fuse_kill_sb_anon",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631136,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311392,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:864",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_kill_sb_blk",
        "fs/fuse/inode.c:fuse_kill_sb_anon",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311392,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585541312,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:864",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_kill_sb_blk",
        "fs/fuse/inode.c:fuse_kill_sb_anon",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541312,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585779680,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:941",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_kill_sb_blk",
        "fs/fuse/inode.c:fuse_kill_sb_anon",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779680,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494948608,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494948608,
      "name": "fuse_conn_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228357132,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228357132,
      "name": "fuse_conn_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288822032,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288822032,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274251944,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274251944,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195312,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195312,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132464,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132464,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179344,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179344,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_conn_put(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_conn_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583273168,
      "name": "fuse_conn_put",
      "external": true,
      "loc": "fs/fuse/inode.c:633",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_put_super",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_read",
        "fs/fuse/control.c:fuse_conn_max_background_write",
        "fs/fuse/control.c:fuse_conn_max_background_read",
        "fs/fuse/control.c:fuse_conn_waiting_read",
        "fs/fuse/control.c:fuse_conn_abort_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273168,
      "name": "fuse_conn_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
