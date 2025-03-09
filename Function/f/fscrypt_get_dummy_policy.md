# Function: <code>fscrypt_get_dummy_policy</code>

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
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582670309,
      "name": "fscrypt_get_dummy_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:36",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
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
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582699125,
      "name": "fscrypt_get_dummy_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:36",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
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
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583025125,
      "name": "fscrypt_get_dummy_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:36",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
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
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583497445,
      "name": "fscrypt_get_dummy_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:57",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
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
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584092981,
      "name": "fscrypt_get_dummy_policy",
      "external": false,
      "loc": "fs/crypto/policy.c:57",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const union fscrypt_policy * fscrypt_get_dummy_policy(struct super_block * sb)
```

```json
{
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584319941,
      "name": "fscrypt_get_dummy_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:56",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
      ],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322448,
      "name": "fscrypt_get_dummy_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
const union fscrypt_policy * fscrypt_get_dummy_policy(struct super_block * sb)
```

```json
{
  "name": "fscrypt_get_dummy_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584537413,
      "name": "fscrypt_get_dummy_policy",
      "external": true,
      "loc": "fs/crypto/policy.c:56",
      "file": "fs/crypto/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_show_test_dummy_encryption",
        "fs/crypto/policy.c:fscrypt_policy_to_inherit"
      ],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540032,
      "name": "fscrypt_get_dummy_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
const union fscrypt_policy * fscrypt_get_dummy_policy(struct super_block * sb)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
