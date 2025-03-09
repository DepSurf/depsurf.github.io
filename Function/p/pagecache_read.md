# Function: <code>pagecache_read</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582969568,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969568,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285984,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285984,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401520,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401520,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424464,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424464,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773936,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773936,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334016,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334016,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982912,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982912,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211744,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211744,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585444624,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444624,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494645880,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494645880,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228089572,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228089572,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288457248,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288457248,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274013542,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274013542,
      "name": "pagecache_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582938304,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938304,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582875456,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875456,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582926912,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926912,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagecache_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583014000,
      "name": "pagecache_read",
      "external": false,
      "loc": "fs/ext4/verity.c:41",
      "file": "fs/ext4/verity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/verity.c:ext4_get_verity_descriptor",
        "fs/ext4/verity.c:ext4_get_verity_descriptor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014000,
      "name": "pagecache_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pagecache_read(struct inode * inode, void * buf, size_t count, loff_t pos)
```
</details>
</li>
</ul>
