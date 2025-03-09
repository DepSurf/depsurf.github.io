# Function: <code>inode_change_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int inode_change_ok(const struct inode * inode, struct iattr * attr)
```

```json
{
  "name": "inode_change_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111136,
      "name": "inode_change_ok",
      "external": true,
      "loc": "fs/attr.c:68",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111136,
      "name": "inode_change_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int inode_change_ok(const struct inode * inode, struct iattr * attr)
```

```json
{
  "name": "inode_change_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276816,
      "name": "inode_change_ok",
      "external": true,
      "loc": "fs/attr.c:55",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276816,
      "name": "inode_change_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int inode_change_ok(const struct inode * inode, struct iattr * attr)
```
</details>
</li>
</ul>
