# Function: <code>fsnotify_add_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272512,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:399",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272512,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int fsnotify_add_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438032,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:422",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438032,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int fsnotify_add_mark(struct fsnotify_mark * mark, struct fsnotify_group * group, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518976,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:422",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518976,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int fsnotify_add_mark(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572576,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:614",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572576,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fsnotify_add_mark(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716912,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:613",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716912,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fsnotify_add_mark(struct fsnotify_mark * mark, struct inode * inode, struct vfsmount * mnt, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883856,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:618",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark",
        "kernel/audit_tree.c:tag_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883856,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968832,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:652",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968832,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101984,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101984,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179440,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179440,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416656,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:683",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416656,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470784,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:683",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470784,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497824,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497824,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812704,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:708",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812704,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367376,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:744",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367376,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951472,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:744",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951472,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174768,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:744",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174768,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int obj_type, int add_flags)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388736,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:709",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388736,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493737616,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493737616,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227261540,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227261540,
      "name": "fsnotify_add_mark",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287347280,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287347280,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273346140,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273346140,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148176,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148176,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582085616,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085616,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138656,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138656,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fsnotify_add_mark(struct fsnotify_mark * mark, fsnotify_connp_t * connp, unsigned int type, int allow_dups, __kernel_fsid_t * fsid)
```

```json
{
  "name": "fsnotify_add_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211696,
      "name": "fsnotify_add_mark",
      "external": true,
      "loc": "fs/notify/mark.c:679",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_fsnotify.c:audit_alloc_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211696,
      "name": "fsnotify_add_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fsnotify_group * group</code>
</li>
<li>
<b>Param reordered. </b>
<code>mark, group, inode, mnt, allow_dups</code> ➡️ <code>mark, inode, mnt, allow_dups</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>fsnotify_connp_t * connp</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount * mnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__kernel_fsid_t * fsid</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param added. </b>
<code>int add_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>int allow_dups</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__kernel_fsid_t * fsid</code>
</li>
</ul>
</details>
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
