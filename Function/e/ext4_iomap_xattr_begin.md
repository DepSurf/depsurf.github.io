# Function: <code>ext4_iomap_xattr_begin</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582897984,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4845",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897984,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969904,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4854",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969904,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995696,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4860",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995696,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4898",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333392,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071592251238,
      "name": "ext4_iomap_xattr_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4901",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840288,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071594032151,
      "name": "ext4_iomap_xattr_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4905",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463696,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071596065436,
      "name": "ext4_iomap_xattr_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4904",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692592,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071596589358,
      "name": "ext4_iomap_xattr_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_xattr_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_xattr_begin",
      "external": false,
      "loc": "fs/ext4/extents.c:4939",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925280,
      "name": "ext4_iomap_xattr_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071597495142,
      "name": "ext4_iomap_xattr_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_iomap_xattr_begin(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```
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
