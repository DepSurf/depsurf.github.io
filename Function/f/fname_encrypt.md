# Function: <code>fname_encrypt</code>

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
int fname_encrypt(struct inode * inode, const struct qstr * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503888,
      "name": "fname_encrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:44",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503888,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589280,
      "name": "fname_encrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:39",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589280,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649216,
      "name": "fname_encrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:39",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649216,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794608,
      "name": "fname_encrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:25",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794608,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969808,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:38",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969808,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:38",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058118,
      "name": "fname_encrypt.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582056768,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218946,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582217648,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299757,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582298480,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493874024,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493874024,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227356324,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227356324,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287507040,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287507040,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273438244,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273438244,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268493,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582267216,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206253,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582204976,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258973,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582257696,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:37",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:__fscrypt_encrypt_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337565,
      "name": "fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582336288,
      "name": "fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int fname_encrypt(struct inode * inode, const struct qstr * iname, struct fscrypt_str * oname)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * out</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int olen</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_str * oname</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fname_encrypt(struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```
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
