# Function: <code>xattr_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146736,
      "name": "xattr_getsecurity",
      "external": true,
      "loc": "fs/xattr.c:146",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146736,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311888,
      "name": "xattr_getsecurity",
      "external": true,
      "loc": "fs/xattr.c:154",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311888,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391504,
      "name": "xattr_getsecurity",
      "external": true,
      "loc": "fs/xattr.c:233",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391504,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446832,
      "name": "xattr_getsecurity",
      "external": true,
      "loc": "fs/xattr.c:233",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446832,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588800,
      "name": "xattr_getsecurity",
      "external": true,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588800,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581746635,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581833163,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:233",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581957465,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582030169,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268769,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:271",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582318801,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:309",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582346269,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:319",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582668509,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:319",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583206788,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:321",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779424,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:341",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779424,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
ssize_t xattr_getsecurity(struct mnt_idmap * idmap, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996608,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:339",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996608,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
ssize_t xattr_getsecurity(struct mnt_idmap * idmap, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209248,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:339",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209248,
      "name": "xattr_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493554500,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227103292,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287126720,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273214708,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998905,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581936473,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581990185,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582060649,
      "name": "xattr_getsecurity",
      "external": false,
      "loc": "fs/xattr.c:234",
      "file": "fs/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_getxattr"
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
ssize_t xattr_getsecurity(struct inode * inode, const char * name, void * value, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
ssize_t xattr_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * value, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
