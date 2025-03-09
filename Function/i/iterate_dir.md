# Function: <code>iterate_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074304,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:24",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:SyS_old_readdir",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_getdents64",
        "fs/compat.c:compat_SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074304,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236800,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:24",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236800,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314688,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:24",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314688,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366400,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:25",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_SyS_getdents",
        "fs/readdir.c:compat_SyS_old_readdir",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366400,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507888,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:26",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_SyS_getdents",
        "fs/readdir.c:compat_SyS_old_readdir",
        "fs/readdir.c:SyS_getdents64",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507888,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664496,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:26",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664496,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750864,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:26",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750864,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868240,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:26",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868240,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940640,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940640,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171920,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171920,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218512,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218512,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244976,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244976,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562800,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x64_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x64_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562800,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583092560,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583092560,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660528,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660528,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877568,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:87",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877568,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085344,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:87",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085344,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493429152,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__arm64_compat_sys_getdents",
        "fs/readdir.c:__arm64_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__arm64_sys_getdents",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493429152,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227009044,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227009044,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286986864,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__se_compat_sys_getdents",
        "fs/readdir.c:__se_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents",
        "fs/readdir.c:__se_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286986864,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273129524,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__se_sys_getdents",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273129524,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909376,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909376,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846960,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846960,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900688,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900688,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int iterate_dir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "iterate_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970304,
      "name": "iterate_dir",
      "external": true,
      "loc": "fs/readdir.c:40",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__x32_compat_sys_getdents",
        "fs/readdir.c:__ia32_compat_sys_getdents",
        "fs/readdir.c:__x32_compat_sys_old_readdir",
        "fs/readdir.c:__ia32_compat_sys_old_readdir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:__ia32_sys_getdents",
        "fs/readdir.c:__x64_sys_getdents",
        "fs/readdir.c:__ia32_sys_old_readdir",
        "fs/readdir.c:__x64_sys_old_readdir",
        "fs/ecryptfs/file.c:ecryptfs_readdir",
        "fs/exportfs/expfs.c:get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970304,
      "name": "iterate_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
