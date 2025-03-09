# Function: <code>__f_unlock_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283184,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:787",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283184,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361600,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:787",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361600,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416864,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:773",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek",
        "fs/readdir.c:compat_SyS_getdents",
        "fs/readdir.c:compat_SyS_old_readdir",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416864,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558384,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:776",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:compat_SyS_lseek",
        "fs/readdir.c:compat_SyS_getdents",
        "fs/readdir.c:compat_SyS_old_readdir",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558384,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714992,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:772",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714992,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801712,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:802",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801712,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920544,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920544,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992928,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992928,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226944,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:833",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226944,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275376,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:969",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275376,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300880,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:981",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300880,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619920,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:1041",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x64_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x64_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619920,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154944,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:1043",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154944,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728624,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:1053",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728624,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945696,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:1068",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945696,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153344,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:1197",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153344,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493508128,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__arm64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__arm64_compat_sys_getdents",
        "fs/readdir.c:__arm64_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__arm64_sys_getdents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493508128,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227064652,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__se_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227064652,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287071952,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__se_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__se_compat_sys_getdents",
        "fs/readdir.c:__se_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents",
        "fs/readdir.c:__se_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287071952,
      "name": "__f_unlock_pos",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273180254,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273180254,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961664,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961664,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899232,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899232,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952976,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952976,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void __f_unlock_pos(struct file * f)
```

```json
{
  "name": "__f_unlock_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023200,
      "name": "__f_unlock_pos",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_writev",
        "fs/read_write.c:do_compat_readv",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:ksys_write",
        "fs/read_write.c:ksys_read",
        "fs/read_write.c:__ia32_sys_llseek",
        "fs/read_write.c:__x64_sys_llseek",
        "fs/read_write.c:ksys_lseek",
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023200,
      "name": "__f_unlock_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __f_unlock_pos(struct file * f)
```
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
