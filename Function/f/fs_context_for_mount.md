# Function: <code>fs_context_for_mount</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035024,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:306",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035024,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112816,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112816,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349808,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:278",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349808,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401760,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:278",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401760,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428992,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:278",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428992,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751744,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:301",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751744,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299248,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:301",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299248,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884128,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:301",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884128,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105824,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:301",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105824,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322080,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:329",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322080,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493653320,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493653320,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227185912,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227185912,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287247984,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287247984,
      "name": "fs_context_for_mount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273282538,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273282538,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081552,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081552,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019072,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019072,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072832,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072832,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```

```json
{
  "name": "fs_context_for_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144592,
      "name": "fs_context_for_mount",
      "external": true,
      "loc": "fs/fs_context.c:304",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144592,
      "name": "fs_context_for_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct fs_context * fs_context_for_mount(struct file_system_type * fs_type, unsigned int sb_flags)
```
</details>
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
