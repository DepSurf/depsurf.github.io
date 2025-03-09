# Function: <code>fuse_write_update_attr</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool fuse_write_update_attr(struct inode * inode, loff_t pos, ssize_t written)
```

```json
{
  "name": "fuse_write_update_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617312,
      "name": "fuse_write_update_attr",
      "external": true,
      "loc": "fs/fuse/file.c:1093",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617312,
      "name": "fuse_write_update_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool fuse_write_update_attr(struct inode * inode, loff_t pos, ssize_t written)
```

```json
{
  "name": "fuse_write_update_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296816,
      "name": "fuse_write_update_attr",
      "external": true,
      "loc": "fs/fuse/file.c:1093",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296816,
      "name": "fuse_write_update_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool fuse_write_update_attr(struct inode * inode, loff_t pos, ssize_t written)
```

```json
{
  "name": "fuse_write_update_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585527152,
      "name": "fuse_write_update_attr",
      "external": true,
      "loc": "fs/fuse/file.c:1094",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527152,
      "name": "fuse_write_update_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool fuse_write_update_attr(struct inode * inode, loff_t pos, ssize_t written)
```

```json
{
  "name": "fuse_write_update_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585764272,
      "name": "fuse_write_update_attr",
      "external": true,
      "loc": "fs/fuse/file.c:1095",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585764272,
      "name": "fuse_write_update_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool fuse_write_update_attr(struct inode * inode, loff_t pos, ssize_t written)
```
</details>
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
