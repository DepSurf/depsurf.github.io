# Function: <code>vfat_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991936,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:905",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991936,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204720,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:905",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204720,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294208,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:916",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294208,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1369
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378976,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:916",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378976,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529696,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:905",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529696,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:898",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721760,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
    },
    {
      "addr": 18446744071582723726,
      "name": "vfat_rename.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:894",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825936,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
    },
    {
      "addr": 18446744071582827384,
      "name": "vfat_rename.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583000032,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583002343,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106224,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583108535,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426352,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1479
    },
    {
      "addr": 18446744071583427843,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540224,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1479
    },
    {
      "addr": 18446744071591354185,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct user_namespace * mnt_userns, struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:896",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563328,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
    },
    {
      "addr": 18446744071591297107,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct user_namespace * mnt_userns, struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:896",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921888,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
    },
    {
      "addr": 18446744071592281979,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct user_namespace * mnt_userns, struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:892",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500944,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
    },
    {
      "addr": 18446744071594064383,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167568,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:931",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167568,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396576,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:931",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396576,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1469
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585631504,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:931",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631504,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1469
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494815464,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494815464,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228234628,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228234628,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288654704,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288654704,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1768
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274141514,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274141514,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074960,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583077271,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012112,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583014423,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063568,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583065879,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int vfat_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "vfat_rename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfat_rename",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:895",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152848,
      "name": "vfat_rename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071583155159,
      "name": "vfat_rename.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
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
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>old_dir, old_dentry, new_dir, new_dentry, flags</code> ➡️ <code>mnt_userns, old_dir, old_dentry, new_dir, new_dentry, flags</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt_userns, old_dir, old_dentry, new_dir, new_dentry, flags</code> ➡️ <code>old_dir, old_dentry, new_dir, new_dentry</code>
</li>
</ul>
</details>
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
