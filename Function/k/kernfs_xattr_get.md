# Function: <code>kernfs_xattr_get</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777056,
      "name": "kernfs_xattr_get",
      "external": false,
      "loc": "fs/kernfs/inode.c:307",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777056,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831408,
      "name": "kernfs_xattr_get",
      "external": false,
      "loc": "fs/kernfs/inode.c:307",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831408,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981008,
      "name": "kernfs_xattr_get",
      "external": false,
      "loc": "fs/kernfs/inode.c:308",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981008,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168192,
      "name": "kernfs_xattr_get",
      "external": false,
      "loc": "fs/kernfs/inode.c:308",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168192,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262848,
      "name": "kernfs_xattr_get",
      "external": false,
      "loc": "fs/kernfs/inode.c:308",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262848,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428384,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:290",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428384,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527136,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527136,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582832146,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:291",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832736,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582904898,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:291",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905488,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932482,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:294",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933296,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583267330,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:294",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268144,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770402,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:300",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771280,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584387778,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:296",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388752,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584616098,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:296",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617072,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584848210,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:295",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849152,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494158768,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494158768,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227599776,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227599776,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287839376,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287839376,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273629778,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273629778,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495872,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495872,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433104,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433104,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486352,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486352,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int kernfs_xattr_get(struct kernfs_node * kn, const char * name, void * value, size_t size)
```

```json
{
  "name": "kernfs_xattr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566912,
      "name": "kernfs_xattr_get",
      "external": true,
      "loc": "fs/kernfs/inode.c:289",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_get",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566912,
      "name": "kernfs_xattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int kernfs_xattr_get(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, void * value, size_t size)
```
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kernfs_node * kn</code>
</li>
<li>
<b>Param added. </b>
<code>const char * name</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct xattr_handler * handler</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * unused</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * suffix</code>
</li>
<li>
<b>Param reordered. </b>
<code>handler, unused, inode, suffix, value, size</code> ➡️ <code>kn, name, value, size</code>
</li>
</ul>
</details>
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
