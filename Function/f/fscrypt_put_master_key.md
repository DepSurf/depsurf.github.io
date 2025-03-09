# Function: <code>fscrypt_put_master_key</code>

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
void fscrypt_put_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081328,
      "name": "fscrypt_put_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:67",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081328,
      "name": "fscrypt_put_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void fscrypt_put_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584308208,
      "name": "fscrypt_put_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:67",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308208,
      "name": "fscrypt_put_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void fscrypt_put_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584525248,
      "name": "fscrypt_put_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:67",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525248,
      "name": "fscrypt_put_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void fscrypt_put_master_key(struct fscrypt_master_key * mk)
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
