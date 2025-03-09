# Function: <code>getname_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581056576,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:125",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:SyS_execveat",
        "fs/exec.c:compat_SyS_execveat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056576,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581217472,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:127",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:compat_SyS_execveat",
        "fs/exec.c:SyS_execveat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217472,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581295168,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:127",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:compat_SyS_execveat",
        "fs/exec.c:SyS_execveat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295168,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581344720,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:127",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:compat_SyS_execveat",
        "fs/exec.c:SyS_execveat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344720,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581486112,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:compat_SyS_execveat",
        "fs/exec.c:SyS_execveat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486112,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646208,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:129",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646208,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732480,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:129",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732480,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581849168,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849168,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921664,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921664,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159376,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink"
      ],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150976,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071582151408,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582205312,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197072,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071582197504,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230112,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir"
      ],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221728,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582222160,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582546928,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__x64_sys_mknod"
      ],
      "caller_func": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__do_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540432,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582540864,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583074989,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:129",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__x64_sys_mknod"
      ],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__do_sys_fsconfig",
        "io_uring/io_uring.c:io_statx_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067824,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071583068256,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641725,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:129",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__x64_sys_mknod"
      ],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__do_sys_fsconfig",
        "io_uring/xattr.c:io_setxattr_prep",
        "io_uring/xattr.c:io_getxattr_prep",
        "io_uring/statx.c:io_statx_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633968,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071583634416,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583858893,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:130",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__x64_sys_mknod"
      ],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__do_sys_fsconfig",
        "io_uring/xattr.c:io_setxattr_prep",
        "io_uring/xattr.c:io_getxattr_prep",
        "io_uring/statx.c:io_statx_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824992,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071583852656,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584065901,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:130",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__x64_sys_mknod"
      ],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:user_path_locked_at",
        "fs/fsopen.c:__do_sys_fsconfig",
        "io_uring/xattr.c:io_setxattr_prep",
        "io_uring/xattr.c:io_getxattr_prep",
        "io_uring/statx.c:io_statx_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031056,
      "name": "getname_flags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071584059744,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493402424,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__arm64_compat_sys_execveat",
        "fs/exec.c:__arm64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__arm64_sys_unlink",
        "fs/namei.c:__arm64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__arm64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493402424,
      "name": "getname_flags",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226988548,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__se_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226988548,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286959536,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__se_compat_sys_execveat",
        "fs/exec.c:__se_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286959536,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273114516,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__se_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__se_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273114516,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581890400,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890400,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581828000,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828000,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581881712,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881712,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct filename * getname_flags(const char * filename, int flags, int * empty)
```

```json
{
  "name": "getname_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951216,
      "name": "getname_flags",
      "external": true,
      "loc": "fs/namei.c:128",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__x32_compat_sys_execveat",
        "fs/exec.c:__ia32_compat_sys_execveat",
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:user_path_at_empty",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951216,
      "name": "getname_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
