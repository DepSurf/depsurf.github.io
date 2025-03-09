# Function: <code>securityfs_create_dentry</code>

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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471088,
      "name": "securityfs_create_dentry",
      "external": true,
      "loc": "security/inode.c:113",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471088,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563552,
      "name": "securityfs_create_dentry",
      "external": true,
      "loc": "security/inode.c:113",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563552,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582652608,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:101",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652608,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807744,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:101",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807744,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001856,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:101",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001856,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115184,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:102",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115184,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302112,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302112,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406768,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406768,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747376,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747376,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867520,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867520,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893680,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893680,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584257504,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257504,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869808,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869808,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585575264,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575264,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585806528,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806528,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586054976,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586054976,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495160696,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495160696,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228548000,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228548000,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289095904,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289095904,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274405660,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274405660,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375504,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375504,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312608,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312608,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359280,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359280,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "securityfs_create_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454464,
      "name": "securityfs_create_dentry",
      "external": false,
      "loc": "security/inode.c:107",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_symlink",
        "security/inode.c:securityfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454464,
      "name": "securityfs_create_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
struct dentry * securityfs_create_dentry(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops, const struct inode_operations * iops)
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
