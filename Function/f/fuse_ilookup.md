# Function: <code>fuse_ilookup</code>

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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668560,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:369",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668560,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689600,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:369",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689600,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050656,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:371",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050656,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640080,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:409",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640080,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585320656,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:416",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320656,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585550592,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:416",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550592,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
```

```json
{
  "name": "fuse_ilookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788928,
      "name": "fuse_ilookup",
      "external": true,
      "loc": "fs/fuse/inode.c:485",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788928,
      "name": "fuse_ilookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fuse_ilookup(struct fuse_conn * fc, u64 nodeid, struct fuse_mount * * fm)
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
