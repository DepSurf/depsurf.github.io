# Function: <code>reconfigure_super</code>

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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792976,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:897",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792976,
      "name": "reconfigure_super",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865312,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865312,
      "name": "reconfigure_super",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091488,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091488,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137888,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:850",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137888,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162656,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:851",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162656,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479632,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:851",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479632,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:850",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008696,
      "name": "reconfigure_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583000416,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:893",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596050240,
      "name": "reconfigure_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583561856,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:900",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572739,
      "name": "reconfigure_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583778144,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:1010",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597477247,
      "name": "reconfigure_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583984208,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493336912,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__arm64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493336912,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226931052,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226931052,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286879952,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286879952,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273067766,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273067766,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834048,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834048,
      "name": "reconfigure_super",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771712,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771712,
      "name": "reconfigure_super",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825360,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825360,
      "name": "reconfigure_super",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context * fc)
```

```json
{
  "name": "reconfigure_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894544,
      "name": "reconfigure_super",
      "external": true,
      "loc": "fs/super.c:903",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:vfs_get_super",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894544,
      "name": "reconfigure_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int reconfigure_super(struct fs_context * fc)
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
