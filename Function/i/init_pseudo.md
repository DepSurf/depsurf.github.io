# Function: <code>init_pseudo</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965440,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:291",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965440,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038192,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038192,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275872,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:366",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/char/mem.c:devmem_fs_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275872,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326000,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:368",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/char/mem.c:devmem_fs_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326000,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353936,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:369",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353936,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675008,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:369",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/zsmalloc.c:zs_init_fs_context",
        "mm/secretmem.c:secretmem_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "block/bdev.c:bd_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675008,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219936,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:369",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/zsmalloc.c:zs_init_fs_context",
        "mm/secretmem.c:secretmem_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "block/bdev.c:bd_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219936,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799264,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:370",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/secretmem.c:secretmem_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "block/bdev.c:bd_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799264,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016272,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:365",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/secretmem.c:secretmem_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "block/bdev.c:bd_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016272,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229216,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:621",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_fs_init_fs_context",
        "mm/secretmem.c:secretmem_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "block/bdev.c:bd_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "drivers/gpu/drm/drm_drv.c:drm_fs_init_fs_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229216,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493563680,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493563680,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227111372,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227111372,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287145552,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287145552,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273221384,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273221384,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006928,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006928,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944496,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944496,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998208,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998208,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```

```json
{
  "name": "init_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068816,
      "name": "init_pseudo",
      "external": true,
      "loc": "fs/libfs.c:297",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_init_fs_context",
        "fs/pipe.c:pipefs_init_fs_context",
        "fs/nsfs.c:nsfs_init_fs_context",
        "fs/block_dev.c:bd_init_fs_context",
        "fs/anon_inodes.c:anon_inodefs_init_fs_context",
        "fs/aio.c:aio_init_fs_context",
        "drivers/virtio/virtio_balloon.c:balloon_init_fs_context",
        "drivers/dax/super.c:dax_init_fs_context",
        "drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context",
        "net/socket.c:sockfs_init_fs_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068816,
      "name": "init_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct pseudo_fs_context * init_pseudo(struct fs_context * fc, long unsigned int magic)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
