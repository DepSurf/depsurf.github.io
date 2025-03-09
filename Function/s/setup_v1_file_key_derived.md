# Function: <code>setup_v1_file_key_derived</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582311959,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int setup_v1_file_key_derived(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597840,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:267",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597840,
      "name": "setup_v1_file_key_derived",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int setup_v1_file_key_derived(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668688,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:265",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668688,
      "name": "setup_v1_file_key_derived",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582698397,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:265",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583024397,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:265",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583496646,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:265",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584092598,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:267",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584319558,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:267",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584537030,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:268",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493890016,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227370140,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287526432,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273450122,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582280695,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582218455,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271175,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_v1_file_key_derived",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582349735,
      "name": "setup_v1_file_key_derived",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:286",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int setup_v1_file_key_derived(struct fscrypt_info * ci, const u8 * raw_master_key)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int setup_v1_file_key_derived(struct fscrypt_info * ci, const u8 * raw_master_key)
```
</details>
</li>
</ul>
