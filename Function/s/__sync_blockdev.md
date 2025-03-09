# Function: <code>__sync_blockdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581234149,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:173",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:set_blocksize",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:__blkdev_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242720,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581405290,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:191",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406736,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485527,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:446",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489728,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581539759,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:454",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543856,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581682479,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:442",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686688,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846720,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:443",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849600,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933856,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:480",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937120,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071648,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074944,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582149232,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150688,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385750,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:484",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390144,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440390,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:516",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442784,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582467323,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:520",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469680,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892451,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:187",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892944,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493701264,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493702528,
      "name": "__sync_blockdev",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227224808,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227230348,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287297592,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287306336,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273317334,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273319000,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117968,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119424,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055408,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056864,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108448,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109904,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```

```json
{
  "name": "__sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178595,
      "name": "__sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:485",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/sync.c:__sync_filesystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182832,
      "name": "__sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __sync_blockdev(struct block_device * bdev, int wait)
```
</details>
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
