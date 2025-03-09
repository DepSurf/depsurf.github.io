# Function: <code>ext4_fill_raw_inode</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_fill_raw_inode(struct inode * inode, struct ext4_inode * raw_inode)
```

```json
{
  "name": "ext4_fill_raw_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_raw_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4340",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965920,
      "name": "ext4_fill_raw_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071594039403,
      "name": "ext4_fill_raw_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int ext4_fill_raw_inode(struct inode * inode, struct ext4_inode * raw_inode)
```

```json
{
  "name": "ext4_fill_raw_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_raw_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4427",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593616,
      "name": "ext4_fill_raw_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071596072405,
      "name": "ext4_fill_raw_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int ext4_fill_raw_inode(struct inode * inode, struct ext4_inode * raw_inode)
```

```json
{
  "name": "ext4_fill_raw_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_raw_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4212",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819920,
      "name": "ext4_fill_raw_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    },
    {
      "addr": 18446744071596595908,
      "name": "ext4_fill_raw_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int ext4_fill_raw_inode(struct inode * inode, struct ext4_inode * raw_inode)
```

```json
{
  "name": "ext4_fill_raw_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_raw_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4231",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052880,
      "name": "ext4_fill_raw_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1230
    },
    {
      "addr": 18446744071597501427,
      "name": "ext4_fill_raw_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int ext4_fill_raw_inode(struct inode * inode, struct ext4_inode * raw_inode)
```
</details>
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
