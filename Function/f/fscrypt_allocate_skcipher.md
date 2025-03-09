# Function: <code>fscrypt_allocate_skcipher</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310366,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071582308112,
      "name": "fscrypt_allocate_skcipher",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:67",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596843,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071582594080,
      "name": "fscrypt_allocate_skcipher",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:74",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664128,
      "name": "fscrypt_allocate_skcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071591341782,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582693790,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:74",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583019597,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:79",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583491450,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:79",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584086986,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:100",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584313754,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:100",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584531050,
      "name": "fscrypt_allocate_skcipher",
      "external": false,
      "loc": "fs/crypto/keysetup.c:100",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493885688,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493885688,
      "name": "fscrypt_allocate_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227366404,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227366404,
      "name": "fscrypt_allocate_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287520800,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287520800,
      "name": "fscrypt_allocate_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273446960,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273446960,
      "name": "fscrypt_allocate_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279102,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071582276848,
      "name": "fscrypt_allocate_skcipher",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216862,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071582214608,
      "name": "fscrypt_allocate_skcipher",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269582,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071582267328,
      "name": "fscrypt_allocate_skcipher",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```

```json
{
  "name": "fscrypt_allocate_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_allocate_skcipher",
      "external": true,
      "loc": "fs/crypto/keysetup.c:70",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348140,
      "name": "fscrypt_allocate_skcipher.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071582345888,
      "name": "fscrypt_allocate_skcipher",
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct crypto_skcipher * fscrypt_allocate_skcipher(struct fscrypt_mode * mode, const u8 * raw_key, const struct inode * inode)
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
