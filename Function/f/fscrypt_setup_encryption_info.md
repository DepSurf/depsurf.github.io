# Function: <code>fscrypt_setup_encryption_info</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666720,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:477",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666720,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695632,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:501",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695632,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:534",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021552,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
    },
    {
      "addr": 18446744071592240860,
      "name": "fscrypt_setup_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:521",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493536,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 799
    },
    {
      "addr": 18446744071594019642,
      "name": "fscrypt_setup_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:534",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088912,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
    },
    {
      "addr": 18446744071596058344,
      "name": "fscrypt_setup_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:553",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316272,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    },
    {
      "addr": 18446744071596582134,
      "name": "fscrypt_setup_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_encryption_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_encryption_info",
      "external": false,
      "loc": "fs/crypto/keysetup.c:555",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533632,
      "name": "fscrypt_setup_encryption_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
    },
    {
      "addr": 18446744071597486196,
      "name": "fscrypt_setup_encryption_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fscrypt_setup_encryption_info(struct inode * inode, const union fscrypt_policy * policy, const u8 * nonce, bool need_dirhash_key)
```
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
