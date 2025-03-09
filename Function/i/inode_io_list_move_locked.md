# Function: <code>inode_io_list_move_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165168,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165168,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581334800,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334800,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581413936,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413936,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468224,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581468224,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581610352,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610352,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581768640,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768640,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581855216,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:135",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855216,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581979824,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:136",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979824,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582054816,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054816,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289712,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289712,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342800,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342800,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370416,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370416,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582694044,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:redirty_tail_locked"
      ],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691216,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583250620,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:redirty_tail_locked"
      ],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243664,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823408,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823408,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584040752,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040752,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255552,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:118",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:redirty_tail_locked",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255552,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493593344,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493593344,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227129864,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227129864,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287164864,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287164864,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273236130,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273236130,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023552,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023552,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961120,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961120,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582014832,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014832,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool inode_io_list_move_locked(struct inode * inode, struct bdi_writeback * wb, struct list_head * head)
```

```json
{
  "name": "inode_io_list_move_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582085808,
      "name": "inode_io_list_move_locked",
      "external": false,
      "loc": "fs/fs-writeback.c:119",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:redirty_tail",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085808,
      "name": "inode_io_list_move_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
