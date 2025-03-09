# Function: <code>alloc_anon_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157168,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1048",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157168,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322176,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1071",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322176,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401360,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1079",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401360,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456432,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1084",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456432,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598416,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1084",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598416,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756016,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1123",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756016,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842544,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1123",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842544,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967088,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1142",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967088,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040304,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040304,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275024,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1218",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275024,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582325024,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1222",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325024,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352960,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1220",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352960,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674048,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1204",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674048,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217984,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1220",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217984,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583795760,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1237",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583795760,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013376,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1232",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013376,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232384,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1543",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232384,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493565776,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493565776,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227114196,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227114196,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287143808,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287143808,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273223282,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273223282,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582009040,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009040,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946608,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946608,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000320,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000320,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inode * alloc_anon_inode(struct super_block * s)
```

```json
{
  "name": "alloc_anon_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582071520,
      "name": "alloc_anon_inode",
      "external": true,
      "loc": "fs/libfs.c:1182",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_create_pool",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup_ring",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071520,
      "name": "alloc_anon_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
