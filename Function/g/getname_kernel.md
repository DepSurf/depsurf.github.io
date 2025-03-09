# Function: <code>getname_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056192,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:210",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:do_file_open_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056192,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581217104,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:212",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217104,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294800,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:212",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294800,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344368,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:212",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344368,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485744,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485744,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645856,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:215",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645856,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732128,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:215",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732128,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848800,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848800,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921296,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921296,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150592,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150592,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196688,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196688,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221344,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221344,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540048,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:221",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540048,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067408,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:222",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067408,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633520,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:222",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633520,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822768,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:223",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822768,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028592,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:223",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/init.c:init_rmdir",
        "fs/init.c:init_unlink",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028592,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493402008,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493402008,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226988160,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226988160,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286958816,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286958816,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273114178,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273114178,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890032,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890032,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827632,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827632,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881344,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881344,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
struct filename * getname_kernel(const char * filename)
```

```json
{
  "name": "getname_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950848,
      "name": "getname_kernel",
      "external": true,
      "loc": "fs/namei.c:213",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950848,
      "name": "getname_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
