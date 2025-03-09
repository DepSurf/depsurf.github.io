# Function: <code>ksys_mount</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ksys_mount(char * dev_name, char * dir_name, char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735648,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3075",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735648,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ksys_mount(char * dev_name, char * dir_name, char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822352,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3047",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822352,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946352,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3306",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946352,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018928,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018928,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493540520,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__arm64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493540520,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227090560,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__se_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227090560,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287110704,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__se_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287110704,
      "name": "ksys_mount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273204736,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__se_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273204736,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987664,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987664,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925232,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925232,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978944,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978944,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
```

```json
{
  "name": "ksys_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049440,
      "name": "ksys_mount",
      "external": true,
      "loc": "fs/namespace.c:3337",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_block_root",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "drivers/base/devtmpfs.c:devtmpfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049440,
      "name": "ksys_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int ksys_mount(char * dev_name, char * dir_name, char * type, long unsigned int flags, void * data)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * dev_name</code> ➡️ <code>const char * dev_name</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * dir_name</code> ➡️ <code>const char * dir_name</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * type</code> ➡️ <code>const char * type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ksys_mount(const char * dev_name, const char * dir_name, const char * type, long unsigned int flags, void * data)
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
