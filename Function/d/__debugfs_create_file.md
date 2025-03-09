# Function: <code>__debugfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329168,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:303",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329168,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419968,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:303",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419968,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503568,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:337",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503568,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582654880,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:339",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654880,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847968,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:361",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847968,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956688,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:361",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956688,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:371",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137152,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583137858,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243328,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583244034,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:372",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569216,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071583570746,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:382",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690800,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071591360685,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:386",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715344,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071591303510,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:386",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076096,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071592289648,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:386",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668032,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071594071734,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:409",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349744,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071596091934,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:409",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579904,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071596615298,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:416",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819600,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071597521223,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494967208,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494967208,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228374900,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228374900,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288846784,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288846784,
      "name": "__debugfs_create_file",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274268322,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274268322,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212064,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583212770,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149216,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583149922,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196096,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583196802,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```

```json
{
  "name": "__debugfs_create_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__debugfs_create_file",
      "external": false,
      "loc": "fs/debugfs/inode.c:373",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debugfs_create_file_size",
        "fs/debugfs/inode.c:debugfs_create_file_unsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289984,
      "name": "__debugfs_create_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071583290690,
      "name": "__debugfs_create_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct dentry * __debugfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * proxy_fops, const struct file_operations * real_fops)
```
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
