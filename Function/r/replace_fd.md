# Function: <code>replace_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117664,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:861",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117664,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283376,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:867",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283376,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361792,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:867",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361792,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417056,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:853",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417056,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558576,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:856",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558576,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715184,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:852",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715184,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801904,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:882",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801904,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920736,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920736,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993120,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993120,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227136,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:913",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227136,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275584,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1049",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:__receive_fd",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275584,
      "name": "replace_fd",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301088,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1061",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301088,
      "name": "replace_fd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620128,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1121",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620128,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155184,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1123",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155184,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728912,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1133",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728912,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945984,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1148",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "kernel/usermode_driver.c:umd_setup",
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945984,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153632,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:1277",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:receive_fd_replace",
        "fs/coredump.c:umh_pipe_setup",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153632,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493508584,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493508584,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227064968,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227064968,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287072416,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287072416,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273180574,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273180574,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961856,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961856,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899424,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899424,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953168,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953168,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int replace_fd(unsigned int fd, struct file * file, unsigned int flags)
```

```json
{
  "name": "replace_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023424,
      "name": "replace_fd",
      "external": true,
      "loc": "fs/file.c:888",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "kernel/umh.c:umh_pipe_setup",
        "fs/coredump.c:umh_pipe_setup",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023424,
      "name": "replace_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
