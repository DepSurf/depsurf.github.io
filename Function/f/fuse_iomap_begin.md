# Function: <code>fuse_iomap_begin</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684784,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:560",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684784,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709920,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:560",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709920,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 767
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:561",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070480,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    },
    {
      "addr": 18446744071592289217,
      "name": "fuse_iomap_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:561",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584661616,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071594071284,
      "name": "fuse_iomap_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:561",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343680,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071596091756,
      "name": "fuse_iomap_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:561",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572880,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071596615120,
      "name": "fuse_iomap_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "fuse_iomap_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_iomap_begin",
      "external": false,
      "loc": "fs/fuse/dax.c:561",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811280,
      "name": "fuse_iomap_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071597521003,
      "name": "fuse_iomap_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fuse_iomap_begin(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```
</details>
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
