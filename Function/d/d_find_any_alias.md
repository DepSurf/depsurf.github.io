# Function: <code>d_find_any_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084752,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1921",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084752,
      "name": "d_find_any_alias",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248064,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1880",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248064,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325824,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1889",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325824,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381696,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1919",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381696,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581523136,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1931",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523136,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682304,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:921",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682304,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769024,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:934",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769024,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886256,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886256,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958800,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958800,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582199666,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:981",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_parent",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191760,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582246050,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:988",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_parent",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239264,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582271634,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:991",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264992,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589826,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:991",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582784,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583121459,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1016",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111568,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691907,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1016",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679376,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583909795,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:1016",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897312,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584115101,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:941",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104432,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493456264,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493456264,
      "name": "d_find_any_alias",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227023080,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227023080,
      "name": "d_find_any_alias",
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287010432,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287010432,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273139806,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273139806,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927536,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927536,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865120,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865120,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918848,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918848,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * d_find_any_alias(struct inode * inode)
```

```json
{
  "name": "d_find_any_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987216,
      "name": "d_find_any_alias",
      "external": true,
      "loc": "fs/dcache.c:960",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fh_to_dentry",
        "fs/dcache.c:__d_obtain_alias",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/ext4/fsync.c:ext4_sync_file",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987216,
      "name": "d_find_any_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
