# Function: <code>simple_xattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152400,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:941",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setxattr",
        "fs/kernfs/inode.c:kernfs_iop_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152400,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317584,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:900",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_iop_removexattr",
        "fs/kernfs/inode.c:kernfs_iop_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317584,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396864,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:898",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396864,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581452176,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:895",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452176,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594160,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:896",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594160,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752720,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752720,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839248,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:893",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839248,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581963776,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963776,
      "name": "simple_xattr_set",
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036528,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036528,
      "name": "simple_xattr_set",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272000,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:965",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272000,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321904,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:997",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321904,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349792,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1026",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349792,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582670352,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1027",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582670352,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211936,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1079",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211936,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583789728,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1182",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789728,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags, ssize_t * removed_size)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006400,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1186",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006400,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
struct simple_xattr * simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219168,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:1206",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219168,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493561320,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493561320,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227108424,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227108424,
      "name": "simple_xattr_set",
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287135504,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287135504,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273219488,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273219488,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005264,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005264,
      "name": "simple_xattr_set",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942832,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942832,
      "name": "simple_xattr_set",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996544,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996544,
      "name": "simple_xattr_set",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs * xattrs, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "simple_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067008,
      "name": "simple_xattr_set",
      "external": true,
      "loc": "fs/xattr.c:894",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "fs/kernfs/inode.c:kernfs_xattr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067008,
      "name": "simple_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>ssize_t * removed_size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t * removed_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct simple_xattr *</code>
</li>
</ul>
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
