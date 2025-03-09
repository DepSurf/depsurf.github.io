# Function: <code>sget_userns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581005120,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:459",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_single",
        "fs/proc/root.c:proc_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005120,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163376,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:463",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163376,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1222
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240384,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:462",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240384,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1178
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287760,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:465",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287760,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427408,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:469",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427408,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1167
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581585584,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:483",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585584,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```

```json
{
  "name": "sget_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671520,
      "name": "sget_userns",
      "external": true,
      "loc": "fs/super.c:487",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_ns",
        "fs/super.c:sget",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671520,
      "name": "sget_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1167
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct super_block * sget_userns(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, struct user_namespace * user_ns, void * data)
```
</details>
</li>
</ul>
