# Function: <code>fscrypt_hash_inode_number</code>

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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665584,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:228",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665584,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582694608,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:253",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694608,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:258",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592240669,
      "name": "fscrypt_hash_inode_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583020448,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:259",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594019476,
      "name": "fscrypt_hash_inode_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583492432,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:282",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058274,
      "name": "fscrypt_hash_inode_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584088192,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:282",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582064,
      "name": "fscrypt_hash_inode_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584314960,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void fscrypt_hash_inode_number(struct fscrypt_inode_info * ci, const struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_hash_inode_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hash_inode_number",
      "external": true,
      "loc": "fs/crypto/keysetup.c:283",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/policy.c:fscrypt_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597486097,
      "name": "fscrypt_hash_inode_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584532256,
      "name": "fscrypt_hash_inode_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void fscrypt_hash_inode_number(struct fscrypt_info * ci, const struct fscrypt_master_key * mk)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_info * ci</code> ➡️ <code>struct fscrypt_inode_info * ci</code>
</li>
</ul>
</details>
</li>
</ul>
