# Function: <code>inode_inline_reclaim_one_dmap</code>

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
struct fuse_dax_mapping * inode_inline_reclaim_one_dmap(struct fuse_conn_dax * fcd, struct inode * inode, bool * retry)
```

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583683376,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:952",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:alloc_dax_mapping_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683376,
      "name": "inode_inline_reclaim_one_dmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583708544,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:952",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708544,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584069120,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:951",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069120,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584660192,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:948",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660192,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585342224,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:948",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342224,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585571424,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:948",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571424,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_inline_reclaim_one_dmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585809824,
      "name": "inode_inline_reclaim_one_dmap",
      "external": false,
      "loc": "fs/fuse/dax.c:946",
      "file": "fs/fuse/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_setup_new_dax_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809824,
      "name": "inode_inline_reclaim_one_dmap.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct fuse_dax_mapping * inode_inline_reclaim_one_dmap(struct fuse_conn_dax * fcd, struct inode * inode, bool * retry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct fuse_dax_mapping * inode_inline_reclaim_one_dmap(struct fuse_conn_dax * fcd, struct inode * inode, bool * retry)
```
</details>
</li>
</ul>
