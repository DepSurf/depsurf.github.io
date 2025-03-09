# Function: <code>fuse_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fuse_setxattr(struct dentry * entry, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066288,
      "name": "fuse_setxattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1722",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066288,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int fuse_setxattr(struct dentry * unused, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281184,
      "name": "fuse_setxattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1729",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281184,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414192,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414192,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497888,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497888,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649088,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649088,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842592,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842592,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946384,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946384,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126976,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126976,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233008,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233008,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560288,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560288,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672528,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672528,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693584,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693584,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584054048,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054048,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643856,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643856,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324608,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324608,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554560,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554560,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags, unsigned int extra_flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585792864,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792864,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494955928,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494955928,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228363824,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228363824,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288831680,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288831680,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274258406,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274258406,
      "name": "fuse_setxattr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446743936274258514,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583201744,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201744,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138896,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138896,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185776,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185776,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int fuse_setxattr(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "fuse_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279536,
      "name": "fuse_setxattr",
      "external": true,
      "loc": "fs/fuse/xattr.c:14",
      "file": "fs/fuse/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/xattr.c:fuse_xattr_set",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279536,
      "name": "fuse_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
<code>struct dentry * unused</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, name, value, size, flags</code> ➡️ <code>unused, inode, name, value, size, flags</code>
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
<code>struct dentry * unused</code>
</li>
<li>
<b>Param reordered. </b>
<code>unused, inode, name, value, size, flags</code> ➡️ <code>inode, name, value, size, flags</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int extra_flags</code>
</li>
</ul>
</details>
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
