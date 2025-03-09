# Function: <code>flush_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237408,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1042",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_size_change",
        "fs/block_dev.c:check_disk_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237408,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403280,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1120",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403280,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483536,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1372",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483536,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538496,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1297",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538496,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681184,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1287",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681184,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1308",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842496,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581851427,
      "name": "flush_disk.cold.42",
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1347",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930288,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581938963,
      "name": "flush_disk.cold.43",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069216,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582076828,
      "name": "flush_disk.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146848,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582154278,
      "name": "flush_disk.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582383966,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1380",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493695872,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493695872,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227226600,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227226600,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287300256,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287300256,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273314042,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273314042,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115584,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582123014,
      "name": "flush_disk.cold",
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053024,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582060454,
      "name": "flush_disk.cold",
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106064,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582113494,
      "name": "flush_disk.cold",
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
void flush_disk(struct block_device * bdev, bool kill_dirty)
```

```json
{
  "name": "flush_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_disk",
      "external": false,
      "loc": "fs/block_dev.c:1399",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180064,
      "name": "flush_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582186445,
      "name": "flush_disk.cold",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void flush_disk(struct block_device * bdev, bool kill_dirty)
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
