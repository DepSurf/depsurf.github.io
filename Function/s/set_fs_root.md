# Function: <code>set_fs_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209376,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:13",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chroot",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mntns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209376,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374032,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:13",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374032,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581451776,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:13",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451776,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506768,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:14",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506768,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648912,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:14",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648912,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811696,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:14",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811696,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898688,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:14",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898688,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024064,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024064,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102048,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102048,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338768,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:init_mount_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338768,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390256,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:init_mount_tree",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390256,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417616,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417616,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740432,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740432,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286784,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286784,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870208,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870208,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584091968,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091968,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308064,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init",
        "fs/init.c:init_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308064,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493639080,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493639080,
      "name": "set_fs_root",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227177576,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227177576,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287230640,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287230640,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273275138,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273275138,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070784,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070784,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008336,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008336,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062064,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062064,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void set_fs_root(struct fs_struct * fs, const struct path * path)
```

```json
{
  "name": "set_fs_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133824,
      "name": "set_fs_root",
      "external": true,
      "loc": "fs/fs_struct.c:15",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_chroot",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mnt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133824,
      "name": "set_fs_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
