# Function: <code>__fscrypt_fname_encrypted_size</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "__fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584074781,
      "name": "__fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:269",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075472,
      "name": "__fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "__fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584301469,
      "name": "__fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:269",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302128,
      "name": "__fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "__fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584518445,
      "name": "__fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:269",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519152,
      "name": "__fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
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
