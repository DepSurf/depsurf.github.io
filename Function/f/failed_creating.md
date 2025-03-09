# Function: <code>failed_creating</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582109984,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:283",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582118893,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:352",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109984,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582326368,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:289",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582337200,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:352",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326368,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582417184,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:289",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582428016,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:352",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417184,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582500176,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:323",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582511552,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500176,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582651392,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:325",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582663168,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651392,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582845584,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:347",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582856660,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845584,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582953760,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:347",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071582964932,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953760,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137685,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:357",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583145841,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:346",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137685,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243861,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583251905,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243861,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583570573,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:358",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583578881,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570573,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583690732,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:368",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583699303,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:350",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687920,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715276,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:372",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583724183,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:352",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712448,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584076024,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:372",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071584084825,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:425",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073024,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584667969,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:372",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071584679452,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:425",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664576,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585350805,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:395",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585364636,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:440",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585580965,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:395",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585595036,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:440",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585818935,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:402",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815648,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494967920,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446603336494979196,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494967920,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228375444,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 3228385180,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228375444,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288847452,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 13835058055288860448,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288847452,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274268880,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446743936274279306,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274268880,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583212597,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583220641,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212597,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583149749,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583157793,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149749,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583196629,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583204673,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196629,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```

```json
{
  "name": "failed_creating",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583290517,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/debugfs/inode.c:359",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file"
      ]
    },
    {
      "addr": 18446744071583298561,
      "name": "failed_creating",
      "external": false,
      "loc": "fs/tracefs/inode.c:347",
      "file": "fs/tracefs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290517,
      "name": "failed_creating",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct dentry * failed_creating(struct dentry * dentry)
```
</details>
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
