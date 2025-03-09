# Function: <code>iomap_readpage_actor</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139936,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap.c:292",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139936,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300208,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300208,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399232,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399232,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582690800,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:245",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readahead_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690800,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764176,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:237",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readahead_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764176,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793120,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:237",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readahead_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793120,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494005888,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494005888,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227465484,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227465484,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287648544,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287648544,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273514840,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273514840,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367968,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367968,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305664,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305664,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358448,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358448,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```

```json
{
  "name": "iomap_readpage_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438080,
      "name": "iomap_readpage_actor",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:207",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpages_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438080,
      "name": "iomap_readpage_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap)
```
</details>
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
<code>struct iomap * srcmap</code>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
loff_t iomap_readpage_actor(struct inode * inode, loff_t pos, loff_t length, void * data, struct iomap * iomap, struct iomap * srcmap)
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
