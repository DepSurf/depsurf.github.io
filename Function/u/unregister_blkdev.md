# Function: <code>unregister_blkdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817248,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:342",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_exit",
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/virtio_blk.c:fini",
        "drivers/block/virtio_blk.c:init",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817248,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096400,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:343",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_exit",
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/virtio_blk.c:fini",
        "drivers/block/virtio_blk.c:init",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096400,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207904,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:343",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207904,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266080,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:344",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266080,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445760,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:389",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445760,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583656992,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:404",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656992,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763264,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:417",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763264,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952736,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952736,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056224,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056224,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452432,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:504",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452432,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584568880,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:494",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568880,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601008,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:282",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601008,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585021968,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:299",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021968,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732624,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:310",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732624,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513840,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:287",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513840,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760304,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:283",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/virtio_blk.c:virtio_blk_fini",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760304,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032640,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:283",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/virtio_blk.c:virtio_blk_fini",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032640,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495896176,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495896176,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229239292,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229239292,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290101168,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290101168,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275013072,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit",
        "drivers/mmc/core/block.c:mmc_blk_exit",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275013072,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024960,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024960,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960768,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960768,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008720,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008720,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void unregister_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "unregister_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111216,
      "name": "unregister_blkdev",
      "external": true,
      "loc": "block/genhd.c:418",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:exit_sr",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111216,
      "name": "unregister_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
