# Function: <code>inotify_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, struct fsnotify_mark * inode_mark, struct fsnotify_mark * vfsmount_mark, u32 mask, void * data, int data_type, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275984,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:65",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275984,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, struct fsnotify_mark * inode_mark, struct fsnotify_mark * vfsmount_mark, u32 mask, void * data, int data_type, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581441856,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:65",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441856,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, struct fsnotify_mark * inode_mark, struct fsnotify_mark * vfsmount_mark, u32 mask, const void * data, int data_type, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522672,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:65",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522672,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, struct fsnotify_mark * inode_mark, struct fsnotify_mark * vfsmount_mark, u32 mask, const void * data, int data_type, const unsigned char * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575728,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:66",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575728,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, struct fsnotify_mark * inode_mark, struct fsnotify_mark * vfsmount_mark, u32 mask, const void * data, int data_type, const unsigned char * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720128,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:66",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720128,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const unsigned char * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887200,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:66",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887200,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const unsigned char * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972080,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:67",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972080,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106212,
      "name": "inotify_handle_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582105488,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182768,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182768,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420064,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420064,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493742312,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493742312,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227264948,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227264948,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287352656,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287352656,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273349528,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273349528,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151504,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151504,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088944,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088944,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141984,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141984,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "inotify_handle_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215168,
      "name": "inotify_handle_event",
      "external": true,
      "loc": "fs/notify/inotify/inotify_fsnotify.c:58",
      "file": "fs/notify/inotify/inotify_fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215168,
      "name": "inotify_handle_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * data</code> ➡️ <code>const void * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_iter_info * iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark * inode_mark</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark * vfsmount_mark</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, inode_mark, vfsmount_mark, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>group, inode, mask, data, data_type, file_name, cookie, iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char * file_name</code> ➡️ <code>const struct qstr * file_name</code>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int inotify_handle_event(struct fsnotify_group * group, struct inode * inode, u32 mask, const void * data, int data_type, const struct qstr * file_name, u32 cookie, struct fsnotify_iter_info * iter_info)
```
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
