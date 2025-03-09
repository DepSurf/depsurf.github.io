# Function: <code>vfs_kern_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124160,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:934",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:do_mount",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124160,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289936,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:934",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289936,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369136,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:962",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369136,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581425093,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:963",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424784,
      "name": "vfs_kern_mount.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071581425056,
      "name": "vfs_kern_mount",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581566357,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1030",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565984,
      "name": "vfs_kern_mount.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071581566256,
      "name": "vfs_kern_mount",
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581722197,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1040",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721824,
      "name": "vfs_kern_mount.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071581722096,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581809237,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:952",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount_data",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808864,
      "name": "vfs_kern_mount.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071581809136,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581928120,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927872,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071581928016,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000728,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000480,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071582000624,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582235768,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:995",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:init_mount_tree"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:init_mount_tree",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235488,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071582235664,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284568,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:995",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:init_mount_tree"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:init_mount_tree",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284288,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071582284464,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582310344,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1002",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310064,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071582310240,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582629832,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1011",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629552,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071582629728,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583166245,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1052",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165872,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071583166080,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583740997,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1158",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740576,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071583740800,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583957573,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1121",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957152,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071583957376,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584167189,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:1134",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166768,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071584166992,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493519760,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493519320,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446603336493519512,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227074248,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227073936,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3227074092,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287085512,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287085072,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 13835058055287085344,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273187808,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273187452,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446743936273187604,
      "name": "vfs_kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581969464,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969216,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071581969360,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581907032,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906784,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071581906928,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960744,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960496,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071581960640,
      "name": "vfs_kern_mount",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct vfsmount * vfs_kern_mount(struct file_system_type * type, int flags, const char * name, void * data)
```

```json
{
  "name": "vfs_kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582031400,
      "name": "vfs_kern_mount",
      "external": true,
      "loc": "fs/namespace.c:979",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": [
        "fs/namespace.c:kern_mount",
        "fs/namespace.c:mnt_init",
        "fs/libfs.c:simple_pin_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031216,
      "name": "vfs_kern_mount.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071582031360,
      "name": "vfs_kern_mount",
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
