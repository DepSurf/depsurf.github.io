# Function: <code>sync_blockdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581234144,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:186",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:set_blocksize",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:__blkdev_put"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234144,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581405290,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:204",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400224,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485527,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:459",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478560,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581539759,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:467",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539216,
      "name": "sync_blockdev.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581539248,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581682479,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:455",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681936,
      "name": "sync_blockdev.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581681968,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846720,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:456",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839824,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933856,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:493",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927200,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071648,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064800,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582149232,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142464,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385750,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:497",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "block/partitions/core.c:blk_drop_partitions",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383856,
      "name": "sync_blockdev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440390,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:529",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "block/partitions/core.c:blk_drop_partitions",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439264,
      "name": "sync_blockdev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582467323,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:533",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466384,
      "name": "sync_blockdev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892451,
      "name": "sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:200",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890592,
      "name": "sync_blockdev",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585590578,
      "name": "sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:195",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585589952,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357250,
      "name": "sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:194",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586356640,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586603871,
      "name": "sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:194",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "block/partitions/core.c:bdev_disk_changed",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603280,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586874343,
      "name": "sync_blockdev",
      "external": true,
      "loc": "block/bdev.c:197",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_mark_dead",
        "block/bdev.c:bdev_mark_dead",
        "block/bdev.c:bdev_release",
        "block/bdev.c:bdev_release",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:bdev_freeze",
        "block/bdev.c:bdev_freeze",
        "block/bdev.c:set_blocksize",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/super.c:fs_bdev_freeze",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "block/ioctl.c:blkdev_common_ioctl",
        "block/partitions/core.c:bdev_disk_changed",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872416,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493701264,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493692312,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227224808,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227220156,
      "name": "sync_blockdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287297592,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287292832,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273317334,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273310708,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117968,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111200,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055408,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048640,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108448,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101680,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_blockdev(struct block_device * bdev)
```

```json
{
  "name": "sync_blockdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178595,
      "name": "sync_blockdev",
      "external": true,
      "loc": "fs/block_dev.c:498",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": [
        "fs/super.c:kill_block_super",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174544,
      "name": "sync_blockdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
