# Function: <code>check_xattrs</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int check_xattrs(struct inode * inode, struct buffer_head * bh, struct ext4_xattr_entry * entry, void * end, void * value_start, const char * function, unsigned int line)
```

```json
{
  "name": "check_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585165376,
      "name": "check_xattrs",
      "external": false,
      "loc": "fs/ext4/xattr.c:191",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585165376,
      "name": "check_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 875
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
int check_xattrs(struct inode * inode, struct buffer_head * bh, struct ext4_xattr_entry * entry, void * end, void * value_start, const char * function, unsigned int line)
```

```json
{
  "name": "check_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585398144,
      "name": "check_xattrs",
      "external": false,
      "loc": "fs/ext4/xattr.c:191",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398144,
      "name": "check_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 875
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int check_xattrs(struct inode * inode, struct buffer_head * bh, struct ext4_xattr_entry * entry, void * end, void * value_start, const char * function, unsigned int line)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
