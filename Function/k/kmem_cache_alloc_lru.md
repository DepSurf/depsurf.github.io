# Function: <code>kmem_cache_alloc_lru</code>

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
void * kmem_cache_alloc_lru(struct kmem_cache * s, struct list_lru * lru, gfp_t gfpflags)
```

```json
{
  "name": "kmem_cache_alloc_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687408,
      "name": "kmem_cache_alloc_lru",
      "external": true,
      "loc": "mm/slub.c:3272",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_inode",
        "fs/dcache.c:__d_alloc",
        "fs/inode.c:alloc_inode",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/ext4/super.c:ext4_alloc_inode",
        "fs/squashfs/super.c:squashfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/ecryptfs/super.c:ecryptfs_alloc_inode",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "ipc/mqueue.c:mqueue_alloc_inode",
        "block/bdev.c:bdev_alloc_inode",
        "lib/xarray.c:xas_split_alloc",
        "lib/xarray.c:xas_alloc",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:xas_nomem",
        "drivers/dax/super.c:dax_alloc_inode",
        "net/socket.c:sock_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687408,
      "name": "kmem_cache_alloc_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
void * kmem_cache_alloc_lru(struct kmem_cache * s, struct list_lru * lru, gfp_t gfpflags)
```

```json
{
  "name": "kmem_cache_alloc_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215392,
      "name": "kmem_cache_alloc_lru",
      "external": true,
      "loc": "mm/slub.c:3480",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_inode",
        "fs/dcache.c:__d_alloc",
        "fs/inode.c:alloc_inode",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/ext4/super.c:ext4_alloc_inode",
        "fs/squashfs/super.c:squashfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/ecryptfs/super.c:ecryptfs_alloc_inode",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "ipc/mqueue.c:mqueue_alloc_inode",
        "block/bdev.c:bdev_alloc_inode",
        "drivers/dax/super.c:dax_alloc_inode",
        "net/socket.c:sock_alloc_inode",
        "lib/xarray.c:xas_split_alloc",
        "lib/xarray.c:xas_alloc",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:xas_nomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215392,
      "name": "kmem_cache_alloc_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
void * kmem_cache_alloc_lru(struct kmem_cache * s, struct list_lru * lru, gfp_t gfpflags)
```

```json
{
  "name": "kmem_cache_alloc_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433808,
      "name": "kmem_cache_alloc_lru",
      "external": true,
      "loc": "mm/slub.c:3498",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_inode",
        "fs/dcache.c:__d_alloc",
        "fs/inode.c:alloc_inode",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/ext4/super.c:ext4_alloc_inode",
        "fs/squashfs/super.c:squashfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/ecryptfs/super.c:ecryptfs_alloc_inode",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "ipc/mqueue.c:mqueue_alloc_inode",
        "block/bdev.c:bdev_alloc_inode",
        "drivers/dax/super.c:dax_alloc_inode",
        "net/socket.c:sock_alloc_inode",
        "lib/xarray.c:xas_split_alloc",
        "lib/xarray.c:xas_alloc",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:xas_nomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433808,
      "name": "kmem_cache_alloc_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
void * kmem_cache_alloc_lru(struct kmem_cache * s, struct list_lru * lru, gfp_t gfpflags)
```

```json
{
  "name": "kmem_cache_alloc_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417088,
      "name": "kmem_cache_alloc_lru",
      "external": true,
      "loc": "mm/slub.c:3876",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_inode",
        "fs/dcache.c:__d_alloc",
        "fs/inode.c:alloc_inode",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/ext4/super.c:ext4_alloc_inode",
        "fs/squashfs/super.c:squashfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/ecryptfs/super.c:ecryptfs_alloc_inode",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "ipc/mqueue.c:mqueue_alloc_inode",
        "block/bdev.c:bdev_alloc_inode",
        "drivers/dax/super.c:dax_alloc_inode",
        "net/socket.c:sock_alloc_inode",
        "lib/xarray.c:xas_split_alloc",
        "lib/xarray.c:xas_alloc",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:xas_nomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417088,
      "name": "kmem_cache_alloc_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
void * kmem_cache_alloc_lru(struct kmem_cache * s, struct list_lru * lru, gfp_t gfpflags)
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
