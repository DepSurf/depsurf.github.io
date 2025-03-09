# Function: <code>ext4_alloc_da_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571312,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:2881",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/migrate.c:ext4_ind_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571312,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757456,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3070",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/migrate.c:ext4_ind_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757456,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846272,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3097",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/migrate.c:ext4_ind_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846272,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995904,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3213",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995904,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145840,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3206",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145840,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334928,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3207",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334928,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433856,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3238",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433856,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603280,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3251",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603280,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704096,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704096,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015344,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3107",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015344,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090576,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3127",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090576,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115536,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3126",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115536,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456256,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3049",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456256,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978928,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3093",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978928,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584607376,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3181",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584607376,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584833872,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:2995",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833872,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066736,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3034",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066736,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494361672,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494361672,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227795668,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227795668,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288092944,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288092944,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273790012,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273790012,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672832,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672832,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610000,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610000,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582662688,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662688,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_alloc_da_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_alloc_da_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582746368,
      "name": "ext4_alloc_da_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:3214",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582746368,
      "name": "ext4_alloc_da_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
