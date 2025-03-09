# Function: <code>page_cache_seek_hole_data</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532832,
      "name": "page_cache_seek_hole_data",
      "external": true,
      "loc": "fs/buffer.c:3538",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_seek_data_actor",
        "fs/iomap.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532832,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675440,
      "name": "page_cache_seek_hole_data",
      "external": true,
      "loc": "fs/buffer.c:3506",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_seek_data_actor",
        "fs/iomap.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675440,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046960,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap.c:657",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_seek_data_actor",
        "fs/iomap.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046960,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140832,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap.c:1291",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_seek_data_actor",
        "fs/iomap.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140832,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310784,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310784,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409840,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409840,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582703568,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703568,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774848,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774848,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    }
  ]
}
```
</details>
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494013504,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494013504,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227478896,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227478896,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287664336,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287664336,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273524374,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273524374,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378576,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378576,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316272,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316272,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582369056,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369056,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```

```json
{
  "name": "page_cache_seek_hole_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448752,
      "name": "page_cache_seek_hole_data",
      "external": false,
      "loc": "fs/iomap/seek.c:74",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448752,
      "name": "page_cache_seek_hole_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
loff_t page_cache_seek_hole_data(struct inode * inode, loff_t offset, loff_t length, int whence)
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
