# Function: <code>fscrypt_fname_alloc_buffer</code>

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
int fscrypt_fname_alloc_buffer(struct inode * inode, u32 ilen, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503600,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:246",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503600,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 ilen, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589008,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:230",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589008,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 ilen, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649072,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:232",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649072,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 ilen, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794496,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:209",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794496,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968848,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:207",
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
      "addr": 18446744071581968848,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055760,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:209",
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
      "addr": 18446744071582055760,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216816,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:208",
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
      "addr": 18446744071582216816,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297648,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446744071582297648,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582032,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:291",
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
      "addr": 18446744071582582032,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582652976,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:263",
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
      "addr": 18446744071582652976,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682064,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:263",
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
      "addr": 18446744071582682064,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007552,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:287",
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
      "addr": 18446744071583007552,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477648,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:294",
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
      "addr": 18446744071583477648,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071968,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:319",
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
      "addr": 18446744071584071968,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298640,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:319",
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
      "addr": 18446744071584298640,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515616,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:319",
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
      "addr": 18446744071584515616,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493873024,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446603336493873024,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227355436,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 3227355436,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287505792,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 13835058055287505792,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273437428,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446743936273437428,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266384,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446744071582266384,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204144,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446744071582204144,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256864,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446744071582256864,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(const struct inode * inode, u32 max_encrypted_len, struct fscrypt_str * crypto_str)
```

```json
{
  "name": "fscrypt_fname_alloc_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335456,
      "name": "fscrypt_fname_alloc_buffer",
      "external": true,
      "loc": "fs/crypto/fname.c:205",
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
      "addr": 18446744071582335456,
      "name": "fscrypt_fname_alloc_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fscrypt_fname_alloc_buffer(struct inode * inode, u32 ilen, struct fscrypt_str * crypto_str)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode * inode</code> ➡️ <code>const struct inode * inode</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 max_encrypted_len</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ilen</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, max_encrypted_len, crypto_str</code> ➡️ <code>max_encrypted_len, crypto_str</code>
</li>
</ul>
</details>
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
