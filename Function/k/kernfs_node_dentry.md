# Function: <code>kernfs_node_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500848,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:96",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500848,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686352,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:111",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686352,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774560,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:111",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774560,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828944,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:111",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828944,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978576,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:184",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978576,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:184",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167161,
      "name": "kernfs_node_dentry.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582165984,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:184",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262249,
      "name": "kernfs_node_dentry.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582261040,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426926,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582425936,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525710,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582524736,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:195",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830638,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582829888,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:195",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346361,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582902672,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:195",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289111,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582930384,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:195",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592248721,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071583265184,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768096,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:195",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768096,
      "name": "kernfs_node_dentry",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385360,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:198",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385360,
      "name": "kernfs_node_dentry",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613632,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:198",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613632,
      "name": "kernfs_node_dentry",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845648,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:205",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845648,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494156184,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494156184,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227597132,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227597132,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287835584,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287835584,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273627404,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273627404,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494446,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582493472,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431678,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582430704,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484926,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582483952,
      "name": "kernfs_node_dentry",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct dentry * kernfs_node_dentry(struct kernfs_node * kn, struct super_block * sb)
```

```json
{
  "name": "kernfs_node_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_node_dentry",
      "external": true,
      "loc": "fs/kernfs/mount.c:172",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565486,
      "name": "kernfs_node_dentry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582564512,
      "name": "kernfs_node_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
