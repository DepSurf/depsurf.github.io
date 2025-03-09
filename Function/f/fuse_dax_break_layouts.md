# Function: <code>fuse_dax_break_layouts</code>

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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583683120,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:686",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common",
        "fs/fuse/dax.c:inode_inline_reclaim_one_dmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683120,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583707472,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:686",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707472,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068032,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:685",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068032,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659104,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:685",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659104,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341184,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:685",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341184,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571136,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:685",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571136,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```

```json
{
  "name": "fuse_dax_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585809536,
      "name": "fuse_dax_break_layouts",
      "external": true,
      "loc": "fs/fuse/dax.c:685",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_open_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809536,
      "name": "fuse_dax_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int fuse_dax_break_layouts(struct inode * inode, u64 dmap_start, u64 dmap_end)
```
</details>
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
