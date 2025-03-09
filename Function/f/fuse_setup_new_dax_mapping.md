# Function: <code>fuse_setup_new_dax_mapping</code>

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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684240,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:430",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684240,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709152,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:430",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709152,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:431",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069696,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071592289196,
      "name": "fuse_setup_new_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:431",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660784,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071594071263,
      "name": "fuse_setup_new_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:431",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342832,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071596091735,
      "name": "fuse_setup_new_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:431",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572032,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071596615099,
      "name": "fuse_setup_new_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
```

```json
{
  "name": "fuse_setup_new_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_setup_new_dax_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:431",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810432,
      "name": "fuse_setup_new_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071597520982,
      "name": "fuse_setup_new_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_setup_new_dax_mapping(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap * iomap)
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
