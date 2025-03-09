# Function: <code>__d_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087024,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:468",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:dentry_unhash",
        "fs/dcache.c:d_drop",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087024,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252640,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:439",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252640,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330432,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:439",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330432,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386192,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:473",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386192,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529573,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:497",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526352,
      "name": "__d_drop",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581683282,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:481",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681856,
      "name": "__d_drop.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581681904,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581769906,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768512,
      "name": "__d_drop.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581768560,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581888698,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885776,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581885824,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961258,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958320,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581958368,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202679,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191152,
      "name": "__d_drop",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582250167,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238656,
      "name": "__d_drop",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582275895,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:479",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264384,
      "name": "__d_drop",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582594375,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:479",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582400,
      "name": "__d_drop",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583124614,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117376,
      "name": "__d_drop",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583695270,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687376,
      "name": "__d_drop",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583913158,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905264,
      "name": "__d_drop",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119014,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:505",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:__dentry_kill"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111984,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493460944,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493454824,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336493454888,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227028544,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227028312,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3227028368,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287016496,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287016096,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055287016192,
      "name": "__d_drop",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273143362,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273138544,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936273138600,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581929994,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927056,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581927104,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867578,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864640,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581864688,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921306,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918368,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581918416,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __d_drop(struct dentry * dentry)
```

```json
{
  "name": "__d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991834,
      "name": "__d_drop",
      "external": true,
      "loc": "fs/dcache.c:494",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991472,
      "name": "__d_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581991520,
      "name": "__d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
