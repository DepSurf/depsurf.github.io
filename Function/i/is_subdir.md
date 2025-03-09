# Function: <code>is_subdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099328,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3302",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_connected",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:is_path_reachable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099328,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264896,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3469",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264896,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342736,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3479",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342736,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398224,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3509",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398224,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539824,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3521",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_connected",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539824,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581681568,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3044",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/namei.c:path_parent_directory",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681568,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581768224,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:2998",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768224,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581885472,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885472,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581958016,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958016,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582190432,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3088",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190432,
      "name": "is_subdir",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582237904,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3095",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237904,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582263648,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3121",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263648,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582581376,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3123",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581376,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583112912,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3147",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112912,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681696,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3203",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681696,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583899840,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3203",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899840,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584107264,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3030",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namespace.c:__ia32_sys_listmount",
        "fs/namespace.c:__ia32_sys_listmount",
        "fs/namespace.c:__x64_sys_listmount",
        "fs/namespace.c:__x64_sys_listmount",
        "fs/namespace.c:do_statmount",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/pnode.c:propagate_mnt",
        "fs/pnode.c:propagate_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107264,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493454144,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493454144,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227025228,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_connected",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227025228,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287014352,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287014352,
      "name": "is_subdir",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273139328,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273139328,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926752,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926752,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581864336,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864336,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581918064,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918064,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_subdir(struct dentry * new_dentry, struct dentry * old_dentry)
```

```json
{
  "name": "is_subdir",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989136,
      "name": "is_subdir",
      "external": true,
      "loc": "fs/dcache.c:3067",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/namei.c:follow_dotdot_rcu",
        "fs/namespace.c:is_path_reachable",
        "fs/namespace.c:copy_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989136,
      "name": "is_subdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
