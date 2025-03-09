# Function: <code>evict_dentries_for_decrypted_inodes</code>

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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305602,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key * mk)
```

```json
{
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589696,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:775",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589696,
      "name": "evict_dentries_for_decrypted_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key * mk)
```

```json
{
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660224,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:780",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660224,
      "name": "evict_dentries_for_decrypted_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582689324,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:780",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583015100,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:780",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583485062,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:820",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584079750,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:877",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584306550,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:872",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584523590,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:887",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:try_to_lock_encrypted_files"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493882188,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227363684,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287516908,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273444456,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582274338,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582212098,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582264818,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
  "name": "evict_dentries_for_decrypted_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582343412,
      "name": "evict_dentries_for_decrypted_inodes",
      "external": false,
      "loc": "fs/crypto/keyring.c:631",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key"
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
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key * mk)
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
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key * mk)
```
</details>
</li>
</ul>
