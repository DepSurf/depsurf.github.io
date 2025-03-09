# Function: <code>fsnotify_find_inode_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_inode_mark(struct fsnotify_group * group, struct inode * inode)
```

```json
{
  "name": "fsnotify_find_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269824,
      "name": "fsnotify_find_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:79",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269824,
      "name": "fsnotify_find_inode_mark",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark * fsnotify_find_inode_mark(struct fsnotify_group * group, struct inode * inode)
```

```json
{
  "name": "fsnotify_find_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435552,
      "name": "fsnotify_find_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:79",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435552,
      "name": "fsnotify_find_inode_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct fsnotify_mark * fsnotify_find_inode_mark(struct fsnotify_group * group, struct inode * inode)
```

```json
{
  "name": "fsnotify_find_inode_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516672,
      "name": "fsnotify_find_inode_mark",
      "external": true,
      "loc": "fs/notify/inode_mark.c:79",
      "file": "fs/notify/inode_mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_tree.c:tag_mount",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516672,
      "name": "fsnotify_find_inode_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct fsnotify_mark * fsnotify_find_inode_mark(struct fsnotify_group * group, struct inode * inode)
```
</details>
</li>
</ul>
