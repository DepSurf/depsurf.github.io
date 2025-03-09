# Function: <code>ecryptfs_getxattr_lower</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003136,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1036",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_getxattr",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003136,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215984,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1025",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_getxattr",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215984,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305536,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1023",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305536,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390400,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1026",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390400,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541136,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1022",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541136,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732832,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1020",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732832,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836544,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1025",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836544,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011472,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1011",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011472,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117552,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117552,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583432931,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437552,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583546627,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1037",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551296,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569299,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1043",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574736,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929171,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1043",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933008,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584508771,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1043",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512848,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585177907,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1045",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182384,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585406963,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1045",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411440,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585642003,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1064",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646336,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494826920,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494826920,
      "name": "ecryptfs_getxattr_lower",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228245924,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228245924,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288671520,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288671520,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274151584,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274151584,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086288,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086288,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023440,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023440,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074896,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074896,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
ssize_t ecryptfs_getxattr_lower(struct dentry * lower_dentry, struct inode * lower_inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr_lower",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164176,
      "name": "ecryptfs_getxattr_lower",
      "external": true,
      "loc": "fs/ecryptfs/inode.c:1033",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_xattr_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164176,
      "name": "ecryptfs_getxattr_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<code>struct inode * lower_inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>lower_dentry, name, value, size</code> ➡️ <code>lower_dentry, lower_inode, name, value, size</code>
</li>
</ul>
</details>
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
