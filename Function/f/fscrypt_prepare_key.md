# Function: <code>fscrypt_prepare_key</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582666134,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:123",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665312,
      "name": "fscrypt_prepare_key",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582693790,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:123",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071591284526,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071582693744,
      "name": "fscrypt_prepare_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019597,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:128",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071592240401,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071583019536,
      "name": "fscrypt_prepare_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583491450,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:129",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071594019201,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071583491392,
      "name": "fscrypt_prepare_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086986,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:150",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071596058116,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584086928,
      "name": "fscrypt_prepare_key",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313754,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:150",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071596581906,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584313696,
      "name": "fscrypt_prepare_key",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_inode_info * ci)
```

```json
{
  "name": "fscrypt_prepare_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531050,
      "name": "fscrypt_prepare_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:150",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071597485939,
      "name": "fscrypt_prepare_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584530992,
      "name": "fscrypt_prepare_key",
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
int fscrypt_prepare_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
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
<code>const struct fscrypt_info * ci</code> ➡️ <code>const struct fscrypt_inode_info * ci</code>
</li>
</ul>
</details>
</li>
</ul>
