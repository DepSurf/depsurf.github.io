# Function: <code>ext4_set_inode_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572032,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4026",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572032,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758128,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4334",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758128,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846960,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4463",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846960,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996608,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4587",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996608,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146528,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4651",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146528,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335888,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4700",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335888,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434816,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4730",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434816,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604224,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4742",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604224,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705040,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705040,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016368,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4440",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016368,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091728,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4498",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091728,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116688,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4497",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116688,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457472,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4418",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457472,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980416,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4639",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980416,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608992,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4734",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608992,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835472,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4519",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835472,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void ext4_set_inode_flags(struct inode * inode, bool init)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068336,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4538",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068336,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494362912,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494362912,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227796696,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227796696,
      "name": "ext4_set_inode_flags",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288094432,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288094432,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273791022,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273791022,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673776,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673776,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610944,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610944,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663632,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663632,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void ext4_set_inode_flags(struct inode * inode)
```

```json
{
  "name": "ext4_set_inode_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747344,
      "name": "ext4_set_inode_flags",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747344,
      "name": "ext4_set_inode_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool init</code>
</li>
</ul>
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
