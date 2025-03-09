# Function: <code>ext4_xattr_block_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, sector_t block_nr, struct ext4_xattr_header * hdr)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847120,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:140",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847120,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, sector_t block_nr, struct ext4_xattr_header * hdr)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042400,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:139",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042400,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132464,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:133",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132464,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230800,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:147",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230800,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379264,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:148",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379264,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570112,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570112,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671504,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671504,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842896,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842896,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947040,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947040,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264464,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:151",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583264464,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365584,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:151",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_xattr_block_list",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365584,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388096,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:151",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388096,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733280,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:151",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733280,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289008,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:151",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289008,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584937965,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:153",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:__ext4_xattr_check_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585165636,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:153",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585398404,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:153",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494622264,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494622264,
      "name": "ext4_xattr_block_csum_verify",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228067184,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228067184,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288428112,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288428112,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273997600,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273997600,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915776,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915776,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852928,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852928,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582904384,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582904384,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_xattr_block_csum_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991456,
      "name": "ext4_xattr_block_csum_verify",
      "external": false,
      "loc": "fs/ext4/xattr.c:149",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991456,
      "name": "ext4_xattr_block_csum_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct buffer_head * bh</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t block_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ext4_xattr_header * hdr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int ext4_xattr_block_csum_verify(struct inode * inode, struct buffer_head * bh)
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
