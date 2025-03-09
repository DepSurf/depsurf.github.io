# Function: <code>fuse_file_release</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665568,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:298",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665568,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024624,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:301",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024624,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584612464,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:304",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612464,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585291744,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:304",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291744,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522128,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:305",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522128,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```

```json
{
  "name": "fuse_file_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758992,
      "name": "fuse_file_release",
      "external": true,
      "loc": "fs/fuse/file.c:306",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_release",
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758992,
      "name": "fuse_file_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void fuse_file_release(struct inode * inode, struct fuse_file * ff, unsigned int open_flags, fl_owner_t id, bool isdir)
```
</details>
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
