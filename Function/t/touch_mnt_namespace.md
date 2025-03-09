# Function: <code>touch_mnt_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void touch_mnt_namespace(struct mnt_namespace * ns)
```

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121536,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:791",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:SyS_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121536,
      "name": "touch_mnt_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void touch_mnt_namespace(struct mnt_namespace * ns)
```

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287280,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:791",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287280,
      "name": "touch_mnt_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void touch_mnt_namespace(struct mnt_namespace * ns)
```

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365920,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:792",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365920,
      "name": "touch_mnt_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439067,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:793",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425216,
      "name": "touch_mnt_namespace.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581580955,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:860",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565408,
      "name": "touch_mnt_namespace.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581736901,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:870",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719200,
      "name": "touch_mnt_namespace.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581823589,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:782",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806864,
      "name": "touch_mnt_namespace.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581947574,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925648,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020150,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998256,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255769,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:806",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231232,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305065,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:806",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:shrink_submounts",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279424,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332675,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:813",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304928,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582653267,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:822",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624160,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583192402,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:858",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160128,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767762,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:969",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734608,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984931,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:878",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951408,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584197475,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:866",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159328,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493542068,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493515760,
      "name": "touch_mnt_namespace.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227093040,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:set_mount_attributes",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:set_mount_attributes",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227072408,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287112496,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287080688,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273207022,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273185790,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581988886,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966992,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926454,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904560,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581980166,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958272,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_mnt_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582050660,
      "name": "touch_mnt_namespace",
      "external": false,
      "loc": "fs/namespace.c:790",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:commit_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031520,
      "name": "touch_mnt_namespace.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void touch_mnt_namespace(struct mnt_namespace * ns)
```
</details>
</li>
</ul>
