# Function: <code>fscrypt_get_devices</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582676860,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:36",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582705607,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:36",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
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
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583032167,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:36",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
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
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583506070,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:37",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * * fscrypt_get_devices(struct super_block * sb, unsigned int * num_devs)
```

```json
{
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101024,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:24",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101024,
      "name": "fscrypt_get_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct block_device * * fscrypt_get_devices(struct super_block * sb, unsigned int * num_devs)
```

```json
{
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584328528,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:24",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328528,
      "name": "fscrypt_get_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct block_device * * fscrypt_get_devices(struct super_block * sb, unsigned int * num_devs)
```

```json
{
  "name": "fscrypt_get_devices",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546064,
      "name": "fscrypt_get_devices",
      "external": false,
      "loc": "fs/crypto/inline_crypt.c:24",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546064,
      "name": "fscrypt_get_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct block_device * * fscrypt_get_devices(struct super_block * sb, unsigned int * num_devs)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
