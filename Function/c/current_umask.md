# Function: <code>current_umask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209344,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:154",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mkdir",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "ipc/mqueue.c:do_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209344,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374000,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:154",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374000,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581451744,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:154",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451744,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506736,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:155",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506736,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648880,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:155",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:path_openat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648880,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811664,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:155",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811664,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898656,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:155",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:path_openat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898656,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024032,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024032,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102016,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102016,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338736,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338736,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390224,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390224,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417584,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417584,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740400,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740400,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286736,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:vfs_tmpfile",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/posix_acl.c:posix_acl_create",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286736,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870144,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/posix_acl.c:posix_acl_create",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870144,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584091904,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/posix_acl.c:posix_acl_create",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091904,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308000,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_mknod",
        "fs/posix_acl.c:posix_acl_create",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308000,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493639040,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493639040,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227177528,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:__se_sys_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227177528,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287230608,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287230608,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273275106,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:__se_sys_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273275106,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070752,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070752,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008304,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008304,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062032,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062032,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int current_umask()
```

```json
{
  "name": "current_umask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133792,
      "name": "current_umask",
      "external": true,
      "loc": "fs/fs_struct.c:156",
      "file": "fs/fs_struct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:lookup_open",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mkdir",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_mknod",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133792,
      "name": "current_umask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
