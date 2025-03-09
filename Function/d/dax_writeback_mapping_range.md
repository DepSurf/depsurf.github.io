# Function: <code>dax_writeback_mapping_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581495936,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:736",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495936,
      "name": "dax_writeback_mapping_range.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071581496784,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581578640,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:853",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578640,
      "name": "dax_writeback_mapping_range.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1695
    },
    {
      "addr": 18446744071581580336,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639440,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:761",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639440,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2219
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784896,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:769",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784896,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2221
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958800,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:1016",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958800,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1896
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051216,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:933",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051216,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:938",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214109,
      "name": "dax_writeback_mapping_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582206080,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286928,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286928,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572416,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572416,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582643952,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:955",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643952,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671968,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:967",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671968,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998224,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:967",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998224,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583472272,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:893",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583472272,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063968,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:1012",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063968,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290400,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:1039",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290400,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int dax_writeback_mapping_range(struct address_space * mapping, struct dax_device * dax_dev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507200,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:1025",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/fuse/dax.c:fuse_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507200,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493863896,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493863896,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1600
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287490896,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287490896,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1912
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273432716,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273432716,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1414
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582255664,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255664,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192672,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192672,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1289
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246144,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246144,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```

```json
{
  "name": "dax_writeback_mapping_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323616,
      "name": "dax_writeback_mapping_range",
      "external": true,
      "loc": "fs/dax.c:939",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_dax_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323616,
      "name": "dax_writeback_mapping_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dax_device * dax_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int dax_writeback_mapping_range(struct address_space * mapping, struct block_device * bdev, struct writeback_control * wbc)
```
</details>
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
