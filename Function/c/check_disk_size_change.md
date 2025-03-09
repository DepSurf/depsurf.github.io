# Function: <code>check_disk_size_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237600,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1067",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:invalidate_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237600,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403408,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403408,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483648,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1394",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483648,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538608,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1319",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538608,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681296,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1309",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681296,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1332",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851467,
      "name": "check_disk_size_change.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581850864,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1371",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939003,
      "name": "check_disk_size_change.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581938400,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1423",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076870,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582076224,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154320,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582151520,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": false,
      "loc": "fs/block_dev.c:1400",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384208,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071582391200,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493703792,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493703792,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227231240,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227231240,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287307744,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287307744,
      "name": "check_disk_size_change",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273320064,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273320064,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123056,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582120256,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060496,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582057696,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113536,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582110736,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
```

```json
{
  "name": "check_disk_size_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_disk_size_change",
      "external": true,
      "loc": "fs/block_dev.c:1419",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:invalidate_partitions",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186487,
      "name": "check_disk_size_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582183696,
      "name": "check_disk_size_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool verbose</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void check_disk_size_change(struct gendisk * disk, struct block_device * bdev, bool verbose)
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
