# Function: <code>configfs_create</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851984,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:181",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851984,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001808,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:181",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001808,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190048,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:181",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190048,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285264,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:181",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285264,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450272,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:167",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450272,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549904,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549904,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856400,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856400,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929424,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929424,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957088,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:163",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957088,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292352,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:157",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292352,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583798400,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:157",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798400,
      "name": "configfs_create",
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418784,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:157",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418784,
      "name": "configfs_create",
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647360,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:157",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647360,
      "name": "configfs_create",
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584879776,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:156",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879776,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494189056,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494189056,
      "name": "configfs_create",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227625384,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227625384,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287878800,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287878800,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273652292,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273652292,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518640,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518640,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455808,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455808,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582509120,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582509120,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * configfs_create(struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "configfs_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589776,
      "name": "configfs_create",
      "external": true,
      "loc": "fs/configfs/inode.c:164",
      "file": "fs/configfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589776,
      "name": "configfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int configfs_create(struct dentry * dentry, umode_t mode, void (*)(struct inode *) init)
```
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*)(struct inode *) init</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct inode *</code>
</li>
</ul>
</details>
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
