# Function: <code>setup_per_mode_enc_key</code>

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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct crypto_skcipher * * tfms, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:126",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594256,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071582596955,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:158",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664752,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071591341894,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:158",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693984,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071591284639,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:163",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019792,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    },
    {
      "addr": 18446744071592240543,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:164",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491680,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071594019342,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:187",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087344,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071596058144,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:187",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314112,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071596581934,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int setup_per_mode_enc_key(struct fscrypt_inode_info * ci, struct fscrypt_master_key * mk, struct fscrypt_prepared_key * keys, u8 hkdf_context, bool include_fs_uuid)
```

```json
{
  "name": "setup_per_mode_enc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_enc_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:188",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531408,
      "name": "setup_per_mode_enc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071597485967,
      "name": "setup_per_mode_enc_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int setup_per_mode_enc_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, struct crypto_skcipher * * tfms, u8 hkdf_context, bool include_fs_uuid)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_prepared_key * keys</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_skcipher * * tfms</code>
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
