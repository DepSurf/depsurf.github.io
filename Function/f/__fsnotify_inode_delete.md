# Function: <code>__fsnotify_inode_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266544,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_delete",
        "fs/inode.c:__destroy_inode",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266544,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432272,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432272,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513392,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513392,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568120,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566128,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581712392,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710256,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581879338,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877072,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963957,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:33",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962192,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582096661,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094864,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582174021,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172224,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410389,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409120,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464013,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462128,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582490989,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489136,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582805547,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803344,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583359330,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356224,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942738,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939376,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166050,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162592,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584380242,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376784,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493729116,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493727000,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227254524,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227252604,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287336896,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287334144,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273338916,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273337120,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582142757,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140960,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582080197,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078400,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133237,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131440,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __fsnotify_inode_delete(struct inode * inode)
```

```json
{
  "name": "__fsnotify_inode_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206273,
      "name": "__fsnotify_inode_delete",
      "external": true,
      "loc": "fs/notify/fsnotify.c:20",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": [
        "fs/dcache.c:dentry_unlink_inode",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204480,
      "name": "__fsnotify_inode_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
