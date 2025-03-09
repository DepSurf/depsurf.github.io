# Function: <code>kernfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503616,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:333",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:__cgroup_procs_write",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503616,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689216,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:337",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689216,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777328,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:264",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777328,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831680,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:264",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831680,
      "name": "kernfs_get_inode",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981280,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:265",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981280,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168768,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:265",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168768,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263840,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:265",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263840,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428048,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:247",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428048,
      "name": "kernfs_get_inode",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526800,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526800,
      "name": "kernfs_get_inode",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582832592,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:248",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832592,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905344,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:248",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905344,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932944,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:250",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932944,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267792,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267792,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583770928,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:250",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770928,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388368,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:248",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388368,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584616688,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:248",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616688,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584848800,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:247",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848800,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494158392,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494158392,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227599360,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227599360,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287838848,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287838848,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273629428,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273629428,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495536,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495536,
      "name": "kernfs_get_inode",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432768,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432768,
      "name": "kernfs_get_inode",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486016,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486016,
      "name": "kernfs_get_inode",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inode * kernfs_get_inode(struct super_block * sb, struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566576,
      "name": "kernfs_get_inode",
      "external": true,
      "loc": "fs/kernfs/inode.c:246",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/dir.c:kernfs_iop_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566576,
      "name": "kernfs_get_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
