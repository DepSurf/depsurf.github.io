# Function: <code>security_inode_setsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244032,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:716",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_iop_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244032,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582462736,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:727",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_iop_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462736,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555200,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:736",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_security_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555200,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642192,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1341",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_security_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642192,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582796480,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1290",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_security_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796480,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994032,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:832",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_security_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994032,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105600,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1353",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/kernfs/inode.c:kernfs_security_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105600,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291680,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1366",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291680,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583396720,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396720,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736192,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1554",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736192,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856528,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1556",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856528,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882336,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1607",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882336,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246640,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246640,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584855536,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1620",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855536,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559456,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1661",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559456,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585790352,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:2554",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790352,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038512,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:2628",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038512,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495148776,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495148776,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228536456,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228536456,
      "name": "security_inode_setsecurity",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289072160,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289072160,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274396588,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274396588,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365456,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365456,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302560,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302560,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349232,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349232,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int security_inode_setsecurity(struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "security_inode_setsecurity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444416,
      "name": "security_inode_setsecurity",
      "external": true,
      "loc": "security/security.c:1406",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444416,
      "name": "security_inode_setsecurity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
