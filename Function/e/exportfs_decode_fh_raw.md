# Function: <code>exportfs_decode_fh_raw</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:421",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591360286,
      "name": "exportfs_decode_fh_raw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583590080,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:421",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303110,
      "name": "exportfs_decode_fh_raw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583613216,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:421",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592288196,
      "name": "exportfs_decode_fh_raw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583971632,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:421",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594070225,
      "name": "exportfs_decode_fh_raw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584554240,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585231152,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:420",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585231152,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585460768,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:445",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585460768,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
```

```json
{
  "name": "exportfs_decode_fh_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695584,
      "name": "exportfs_decode_fh_raw",
      "external": true,
      "loc": "fs/exportfs/expfs.c:429",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695584,
      "name": "exportfs_decode_fh_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
struct dentry * exportfs_decode_fh_raw(struct vfsmount * mnt, struct fid * fid, int fh_len, int fileid_type, int (*)(void *, struct dentry *) acceptable, void * context)
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
