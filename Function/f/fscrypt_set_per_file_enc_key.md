# Function: <code>fscrypt_set_per_file_enc_key</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582595107,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:113",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:setup_v1_file_key_derived"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596720,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582666126,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:152",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:setup_v1_file_key_derived"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665440,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582694975,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:152",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694512,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583020843,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:157",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020352,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583492874,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:158",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583492304,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584088651,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:181",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088032,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584315419,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:181",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314800,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int fscrypt_set_per_file_enc_key(struct fscrypt_inode_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_set_per_file_enc_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532715,
      "name": "fscrypt_set_per_file_enc_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:181",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532096,
      "name": "fscrypt_set_per_file_enc_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int fscrypt_set_per_file_enc_key(struct fscrypt_info * ci, const u8 * raw_key)
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
