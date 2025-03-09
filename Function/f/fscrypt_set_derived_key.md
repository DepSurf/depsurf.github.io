# Function: <code>fscrypt_set_derived_key</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308560,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308560,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493886344,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493886344,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227367064,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227367064,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287521712,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287521712,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273447428,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273447428,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582277296,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277296,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215056,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215056,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267776,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267776,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```

```json
{
  "name": "fscrypt_set_derived_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582346336,
      "name": "fscrypt_set_derived_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:184",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582346336,
      "name": "fscrypt_set_derived_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fscrypt_set_derived_key(struct fscrypt_info * ci, const u8 * derived_key)
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
