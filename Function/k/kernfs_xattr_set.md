# Function: <code>kernfs_xattr_set</code>

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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777152,
      "name": "kernfs_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:322",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777152,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831504,
      "name": "kernfs_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:322",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831504,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981104,
      "name": "kernfs_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:323",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981104,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168288,
      "name": "kernfs_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:323",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168288,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262944,
      "name": "kernfs_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:323",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262944,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428528,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:300",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428528,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527280,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527280,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582832032,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:301",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832832,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582904784,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:301",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905584,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932379,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:304",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933392,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583267099,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:304",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268240,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770283,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:310",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771392,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584387643,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:306",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388880,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584615963,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:306",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617200,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584848059,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:305",
      "file": "fs/kernfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849280,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494158976,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494158976,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227599908,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227599908,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287839616,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287839616,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273629954,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273629954,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496016,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496016,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433248,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433248,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486496,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486496,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(struct kernfs_node * kn, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567056,
      "name": "kernfs_xattr_set",
      "external": true,
      "loc": "fs/kernfs/inode.c:299",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set",
        "security/selinux/hooks.c:selinux_kernfs_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567056,
      "name": "kernfs_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernfs_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
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
<code>handler, unused, inode, suffix, value, size, flags</code> ➡️ <code>kn, name, value, size, flags</code>
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
