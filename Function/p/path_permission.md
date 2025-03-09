# Function: <code>path_permission</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int path_permission(const struct path * path, int mask)
```

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044144,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121159,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591283217,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ]
    },
    {
      "addr": 18446744071582502956,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513094,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590519121,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:3013",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591283217,
      "name": "path_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int path_permission(const struct path * path, int mask)
```

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267136,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437991,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592231667,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ]
    },
    {
      "addr": 18446744071582818012,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828419,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591326848,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2996",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231667,
      "name": "path_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int path_permission(const struct path * path, int mask)
```

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558300,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955054,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594011641,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "fs/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ]
    },
    {
      "addr": 18446744071583375240,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387479,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593004039,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2762",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011641,
      "name": "path_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581930797,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583512990,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627905569,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583960345,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583973027,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594895249,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2916",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582114093,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583728030,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619668593,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183752,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196759,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595286598,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2530",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582254413,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583928878,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621974721,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584397736,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584411287,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596124438,
      "name": "path_permission",
      "external": false,
      "loc": "include/linux/fs.h:2765",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_find_other"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int path_permission(const struct path * path, int mask)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int path_permission(const struct path * path, int mask)
```
</details>
</li>
</ul>
