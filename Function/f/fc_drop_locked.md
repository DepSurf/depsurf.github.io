# Function: <code>fc_drop_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035136,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:330",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035136,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112928,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112928,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349920,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:302",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount_fc",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349920,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401872,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:302",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount_fc",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401872,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429104,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:302",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429104,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751856,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:325",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751856,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299408,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:325",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299408,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884336,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:325",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884336,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106112,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:346",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106112,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322368,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:374",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:vfs_cmd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322368,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493653528,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__arm64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493653528,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227187952,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227187952,
      "name": "fc_drop_locked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287248112,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287248112,
      "name": "fc_drop_locked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273284308,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273284308,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081664,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081664,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019184,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019184,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072944,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072944,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void fc_drop_locked(struct fs_context * fc)
```

```json
{
  "name": "fc_drop_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144704,
      "name": "fc_drop_locked",
      "external": true,
      "loc": "fs/fs_context.c:328",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_tree",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144704,
      "name": "fc_drop_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void fc_drop_locked(struct fs_context * fc)
```
</details>
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
