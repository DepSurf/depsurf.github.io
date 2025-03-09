# Function: <code>fuse_sync_bucket_alloc</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_sync_bucket_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584049286,
      "name": "fuse_sync_bucket_alloc",
      "external": false,
      "loc": "fs/fuse/inode.c:503",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_sync_fs_writes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_sync_bucket_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584638646,
      "name": "fuse_sync_bucket_alloc",
      "external": false,
      "loc": "fs/fuse/inode.c:541",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_sync_fs_writes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_sync_bucket_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585319238,
      "name": "fuse_sync_bucket_alloc",
      "external": false,
      "loc": "fs/fuse/inode.c:554",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_sync_fs_writes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_sync_bucket_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585549174,
      "name": "fuse_sync_bucket_alloc",
      "external": false,
      "loc": "fs/fuse/inode.c:554",
      "file": "fs/fuse/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_sync_fs_writes"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fuse_sync_bucket * fuse_sync_bucket_alloc()
```

```json
{
  "name": "fuse_sync_bucket_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778080,
      "name": "fuse_sync_bucket_alloc",
      "external": false,
      "loc": "fs/fuse/inode.c:623",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_sync_fs_writes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778080,
      "name": "fuse_sync_bucket_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct fuse_sync_bucket * fuse_sync_bucket_alloc()
```
</details>
</li>
</ul>
