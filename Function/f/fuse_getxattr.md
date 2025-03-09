# Function: <code>fuse_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct dentry * entry, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062608,
      "name": "fuse_getxattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1758",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062608,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
ssize_t fuse_getxattr(struct dentry * entry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276736,
      "name": "fuse_getxattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1779",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276736,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414704,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:64",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414704,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582498208,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498208,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649408,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649408,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842912,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842912,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946704,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946704,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127296,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127296,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233328,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233328,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560608,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560608,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672848,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672848,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693936,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:52",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693936,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584054400,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:52",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054400,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644240,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:51",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644240,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325008,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:51",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325008,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554944,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:51",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554944,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793248,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:51",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793248,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494956240,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494956240,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228364128,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228364128,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288832080,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288832080,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274258784,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274258784,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202064,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202064,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139216,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139216,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583186096,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186096,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
ssize_t fuse_getxattr(struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "fuse_getxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279856,
      "name": "fuse_getxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:49",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_get",
        "fs/fuse/acl.c:fuse_get_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279856,
      "name": "fuse_getxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, name, value, size</code> ➡️ <code>entry, inode, name, value, size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dentry * entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, inode, name, value, size</code> ➡️ <code>inode, name, value, size</code>
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
