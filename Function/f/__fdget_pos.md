# Function: <code>__fdget_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117408,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:772",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_lseek",
        "fs/read_write.c:SyS_llseek",
        "fs/read_write.c:SyS_read",
        "fs/read_write.c:SyS_write",
        "fs/read_write.c:SyS_readv",
        "fs/read_write.c:SyS_writev",
        "fs/read_write.c:compat_SyS_readv",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117408,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283104,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:773",
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
      "addr": 18446744071581283104,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361520,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:773",
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
      "addr": 18446744071581361520,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416784,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:759",
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
      "addr": 18446744071581416784,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558304,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:762",
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
      "addr": 18446744071581558304,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714912,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:758",
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
      "addr": 18446744071581714912,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801632,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:788",
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
      "addr": 18446744071581801632,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920464,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071581920464,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992848,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071581992848,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226864,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:819",
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
      "addr": 18446744071582226864,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275296,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:955",
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
      "addr": 18446744071582275296,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300800,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:967",
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
      "addr": 18446744071582300800,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619840,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:1027",
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
      "addr": 18446744071582619840,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154832,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:1029",
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
      "addr": 18446744071583154832,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728496,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:1039",
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
      "addr": 18446744071583728496,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945552,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:1056",
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
      "addr": 18446744071583945552,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152960,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:1185",
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
      "addr": 18446744071584152960,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493508016,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446603336493508016,
      "name": "__fdget_pos",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227064560,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 3227064560,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287071792,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 13835058055287071792,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273180156,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446743936273180156,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961584,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071581961584,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899152,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071581899152,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952896,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071581952896,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int __fdget_pos(unsigned int fd)
```

```json
{
  "name": "__fdget_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023120,
      "name": "__fdget_pos",
      "external": true,
      "loc": "fs/file.c:794",
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
      "addr": 18446744071582023120,
      "name": "__fdget_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
