# Function: <code>__device_add_disk</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __device_add_disk(struct device * parent, struct gendisk * disk, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:657",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662432,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1070
    },
    {
      "addr": 18446744071583665724,
      "name": "__device_add_disk.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:676",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769216,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
    },
    {
      "addr": 18446744071583772540,
      "name": "__device_add_disk.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958736,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
    },
    {
      "addr": 18446744071583962257,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062208,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446744071584065761,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:777",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459184,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071584463022,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:697",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574736,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071591373009,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:498",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584607376,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071591315635,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495904248,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495904248,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229246992,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229246992,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1392
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290111952,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290111952,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275019512,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275019512,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030944,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446744071584034497,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966736,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446744071583970261,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014704,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446744071584018257,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
```

```json
{
  "name": "__device_add_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__device_add_disk",
      "external": false,
      "loc": "block/genhd.c:691",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk_no_queue_reg",
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117248,
      "name": "__device_add_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
    },
    {
      "addr": 18446744071584120803,
      "name": "__device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __device_add_disk(struct device * parent, struct gendisk * disk, bool register_queue)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct attribute_group * * groups</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, disk, register_queue</code> ➡️ <code>parent, disk, groups, register_queue</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups, bool register_queue)
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
