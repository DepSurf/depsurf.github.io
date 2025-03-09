# Function: <code>fscrypt_fname_disk_to_usr</code>

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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506016,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:283",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506016,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591200,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:271",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591200,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651328,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:280",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651328,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796656,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:257",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796656,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969488,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:252",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969488,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056448,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:254",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056448,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217328,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:253",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217328,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298160,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298160,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583136,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:344",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583136,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653920,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:315",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653920,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582683008,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:315",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683008,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:337",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239895,
      "name": "fscrypt_fname_disk_to_usr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071583008528,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478848,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:344",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478848,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073984,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:369",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073984,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:369",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596581665,
      "name": "fscrypt_fname_disk_to_usr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071584300656,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int fscrypt_fname_disk_to_usr(const struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:369",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_ci_compare",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597485526,
      "name": "fscrypt_fname_disk_to_usr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071584517632,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493873632,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493873632,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227355948,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227355948,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287506496,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287506496,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273437942,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273437942,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266896,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266896,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204656,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204656,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257376,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257376,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fscrypt_fname_disk_to_usr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335968,
      "name": "fscrypt_fname_disk_to_usr",
      "external": true,
      "loc": "fs/crypto/fname.c:250",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_get_symlink",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335968,
      "name": "fscrypt_fname_disk_to_usr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int fscrypt_fname_disk_to_usr(struct inode * inode, u32 hash, u32 minor_hash, const struct fscrypt_str * iname, struct fscrypt_str * oname)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode * inode</code> ➡️ <code>const struct inode * inode</code>
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
