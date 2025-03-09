# Function: <code>vfs_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046608,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4186",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046608,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2102
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209504,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4336",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209504,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2391
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286992,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4293",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286992,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2444
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335472,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4359",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335472,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2379
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581476496,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4355",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476496,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2391
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643456,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4401",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643456,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2389
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720272,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4390",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720272,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2385
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838000,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4391",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838000,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2479
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581910464,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910464,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2479
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147808,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4217",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147808,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2769
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194048,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4217",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194048,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2636
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210496,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4448",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210496,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2984
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528768,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4531",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528768,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2633
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583055760,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4626",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583055760,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2564
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622160,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4682",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622160,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2564
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841120,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4754",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841120,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2724
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
int vfs_rename(struct renamedata * rd)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584047152,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4762",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047152,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3519
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493391400,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493391400,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2384
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226972836,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226972836,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2400
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286939904,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286939904,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2720
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273106064,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273106064,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1804
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879200,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879200,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2479
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816800,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816800,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2479
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870512,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870512,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2479
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
int vfs_rename(struct inode * old_dir, struct dentry * old_dentry, struct inode * new_dir, struct dentry * new_dentry, struct inode * * delegated_inode, unsigned int flags)
```

```json
{
  "name": "vfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935856,
      "name": "vfs_rename",
      "external": true,
      "loc": "fs/namei.c:4386",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/ecryptfs/inode.c:ecryptfs_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935856,
      "name": "vfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2477
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct renamedata * rd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * old_dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * old_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * new_dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * new_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * * delegated_inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
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
