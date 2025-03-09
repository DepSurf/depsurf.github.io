# Function: <code>mount_capable</code>

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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792304,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:479",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792304,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864672,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864672,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090816,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090816,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136928,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136928,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161696,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:486",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161696,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478672,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:486",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478672,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999504,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999504,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560864,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:528",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560864,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777008,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:535",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777008,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983680,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:689",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:vfs_cmd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983680,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493335648,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__arm64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493335648,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226930276,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226930276,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286878592,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286878592,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273066732,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273066732,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833408,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833408,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771072,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771072,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824720,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824720,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
```

```json
{
  "name": "mount_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893920,
      "name": "mount_capable",
      "external": true,
      "loc": "fs/super.c:485",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893920,
      "name": "mount_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool mount_capable(struct fs_context * fc)
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
