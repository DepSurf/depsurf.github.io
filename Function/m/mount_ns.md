# Function: <code>mount_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006272,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:954",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006272,
      "name": "mount_ns",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165552,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:968",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165552,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242528,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:1014",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242528,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289888,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:1017",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289888,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429552,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:1017",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429552,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587760,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:1072",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587760,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673712,
      "name": "mount_ns",
      "external": true,
      "loc": "fs/super.c:1057",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "ipc/mqueue.c:mqueue_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673712,
      "name": "mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * ns</code>
</li>
<li>
<b>Param added. </b>
<code>struct user_namespace * user_ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>fs_type, flags, data, fill_super</code> ➡️ <code>fs_type, flags, data, ns, user_ns, fill_super</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct dentry * mount_ns(struct file_system_type * fs_type, int flags, void * data, void * ns, struct user_namespace * user_ns, int (*)(struct super_block *, void *, int) fill_super)
```
</details>
</li>
</ul>
