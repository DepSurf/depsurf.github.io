# Function: <code>ext4_handle_inode_extension</code>

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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944832,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:283",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944832,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018144,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:284",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018144,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043856,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:283",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043856,
      "name": "ext4_handle_inode_extension",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:283",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381120,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071592254581,
      "name": "ext4_handle_inode_extension.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:283",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896064,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
    },
    {
      "addr": 18446744071594035551,
      "name": "ext4_handle_inode_extension.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:298",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521504,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071596068747,
      "name": "ext4_handle_inode_extension.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:308",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750368,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071596592417,
      "name": "ext4_handle_inode_extension.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t count)
```

```json
{
  "name": "ext4_handle_inode_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584983040,
      "name": "ext4_handle_inode_extension",
      "external": false,
      "loc": "fs/ext4/file.c:308",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584983040,
      "name": "ext4_handle_inode_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
ssize_t ext4_handle_inode_extension(struct inode * inode, loff_t offset, ssize_t written, size_t count)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t written</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, offset, written, count</code> ➡️ <code>inode, offset, count</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t count</code> ➡️ <code>ssize_t count</code>
</li>
</ul>
</details>
</li>
</ul>
