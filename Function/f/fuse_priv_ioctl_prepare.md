# Function: <code>fuse_priv_ioctl_prepare</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583703461,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:403",
      "file": "fs/fuse/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584064069,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:406",
      "file": "fs/fuse/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
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
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584654596,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:417",
      "file": "fs/fuse/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_file * fuse_priv_ioctl_prepare(struct inode * inode)
```

```json
{
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585332720,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:417",
      "file": "fs/fuse/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332720,
      "name": "fuse_priv_ioctl_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct fuse_file * fuse_priv_ioctl_prepare(struct inode * inode)
```

```json
{
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562608,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:422",
      "file": "fs/fuse/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562608,
      "name": "fuse_priv_ioctl_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct fuse_file * fuse_priv_ioctl_prepare(struct inode * inode)
```

```json
{
  "name": "fuse_priv_ioctl_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585800944,
      "name": "fuse_priv_ioctl_prepare",
      "external": false,
      "loc": "fs/fuse/ioctl.c:422",
      "file": "fs/fuse/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/ioctl.c:fuse_fileattr_set",
        "fs/fuse/ioctl.c:fuse_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800944,
      "name": "fuse_priv_ioctl_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct fuse_file * fuse_priv_ioctl_prepare(struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
