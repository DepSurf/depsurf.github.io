# Function: <code>mount_pseudo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581153920,
      "name": "mount_pseudo",
      "external": true,
      "loc": "fs/libfs.c:211",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153920,
      "name": "mount_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct dentry * mount_pseudo(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319328,
      "name": "mount_pseudo",
      "external": true,
      "loc": "fs/libfs.c:239",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319328,
      "name": "mount_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_pseudo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581190182,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263878,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456198,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:nsfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478342,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545094,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "fs/anon_inodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/anon_inodes.c:anon_inodefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563942,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584350774,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2070",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:balloon_mount"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_pseudo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581238358,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312870,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512374,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:nsfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533830,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599014,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "fs/anon_inodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/anon_inodes.c:anon_inodefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621014,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432310,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:balloon_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387110,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2120",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_mount"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_pseudo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581369878,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452998,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654534,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:nsfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676358,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743350,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "fs/anon_inodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/anon_inodes.c:anon_inodefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765686,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840438,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:balloon_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585816550,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2166",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_mount"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_pseudo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581519733,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612565,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817445,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:nsfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839429,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911925,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "fs/anon_inodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/anon_inodes.c:anon_inodefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933669,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071125,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:balloon_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586061109,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2182",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_mount"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_pseudo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581605621,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698917,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904437,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:nsfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926805,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bd_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996421,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "fs/anon_inodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/anon_inodes.c:anon_inodefs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018101,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585178773,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:balloon_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586205525,
      "name": "mount_pseudo",
      "external": false,
      "loc": "include/linux/fs.h:2268",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_mount"
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
struct dentry * mount_pseudo(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct dentry_operations * dops, long unsigned int magic)
```
</details>
</li>
</ul>
