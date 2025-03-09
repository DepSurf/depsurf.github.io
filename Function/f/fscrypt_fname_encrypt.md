# Function: <code>fscrypt_fname_encrypt</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:112",
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
      "addr": 18446744071582584914,
      "name": "fscrypt_fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582583616,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:86",
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
      "addr": 18446744071591341512,
      "name": "fscrypt_fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582654464,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:86",
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
      "addr": 18446744071591284245,
      "name": "fscrypt_fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582683520,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:90",
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
      "addr": 18446744071592240009,
      "name": "fscrypt_fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583009104,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:97",
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
      "addr": 18446744071594018830,
      "name": "fscrypt_fname_encrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583479456,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072688,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:98",
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
      "addr": 18446744071584072688,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584299360,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:98",
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
      "addr": 18446744071584299360,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```

```json
{
  "name": "fscrypt_fname_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584516336,
      "name": "fscrypt_fname_encrypt",
      "external": true,
      "loc": "fs/crypto/fname.c:98",
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
      "addr": 18446744071584516336,
      "name": "fscrypt_fname_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fscrypt_fname_encrypt(const struct inode * inode, const struct qstr * iname, u8 * out, unsigned int olen)
```
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
