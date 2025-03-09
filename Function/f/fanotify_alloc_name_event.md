# Function: <code>fanotify_alloc_name_event</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event * fanotify_alloc_name_event(struct inode * id, __kernel_fsid_t * fsid, const struct qstr * file_name, struct inode * child, gfp_t gfp)
```

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480752,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:479",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480752,
      "name": "fanotify_alloc_name_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
struct fanotify_event * fanotify_alloc_name_event(struct inode * id, __kernel_fsid_t * fsid, const struct qstr * name, struct inode * child, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507920,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:517",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507920,
      "name": "fanotify_alloc_name_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
struct fanotify_event * fanotify_alloc_name_event(struct inode * id, __kernel_fsid_t * fsid, const struct qstr * name, struct inode * child, unsigned int * hash, gfp_t gfp)
```

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582823536,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:517",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823536,
      "name": "fanotify_alloc_name_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583381104,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:590",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381104,
      "name": "fanotify_alloc_name_event.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583966560,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:593",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966560,
      "name": "fanotify_alloc_name_event.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584190000,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:597",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190000,
      "name": "fanotify_alloc_name_event.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_alloc_name_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584403984,
      "name": "fanotify_alloc_name_event",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:591",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403984,
      "name": "fanotify_alloc_name_event.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct fanotify_event * fanotify_alloc_name_event(struct inode * id, __kernel_fsid_t * fsid, const struct qstr * file_name, struct inode * child, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct qstr * name</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int * hash</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct qstr * file_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>id, fsid, file_name, child, gfp</code> ➡️ <code>id, fsid, name, child, hash, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct fanotify_event * fanotify_alloc_name_event(struct inode * id, __kernel_fsid_t * fsid, const struct qstr * name, struct inode * child, unsigned int * hash, gfp_t gfp)
```
</details>
</li>
</ul>
