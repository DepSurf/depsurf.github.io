# Function: <code>fuse_setup_one_mapping</code>

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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682336,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:181",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_upgrade_dax_mapping",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682336,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706960,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:181",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706960,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067184,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:182",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067184,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655488,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:182",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655488,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585337296,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:182",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337296,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567232,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:182",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567232,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
```

```json
{
  "name": "fuse_setup_one_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805568,
      "name": "fuse_setup_one_mapping",
      "external": false,
      "loc": "fs/fuse/dax.c:182",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_iomap_begin",
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805568,
      "name": "fuse_setup_one_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int fuse_setup_one_mapping(struct inode * inode, long unsigned int start_idx, struct fuse_dax_mapping * dmap, bool writable, bool upgrade)
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
