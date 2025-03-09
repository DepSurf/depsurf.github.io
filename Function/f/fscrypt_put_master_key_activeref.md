# Function: <code>fscrypt_put_master_key_activeref</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_put_master_key_activeref(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key_activeref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584082706,
      "name": "fscrypt_put_master_key_activeref",
      "external": true,
      "loc": "fs/crypto/keyring.c:82",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_destroy_keyring"
      ],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keysetup.c:put_crypt_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081488,
      "name": "fscrypt_put_master_key_activeref.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071584082400,
      "name": "fscrypt_put_master_key_activeref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void fscrypt_put_master_key_activeref(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key_activeref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584308896,
      "name": "fscrypt_put_master_key_activeref",
      "external": true,
      "loc": "fs/crypto/keyring.c:82",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keysetup.c:put_crypt_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308896,
      "name": "fscrypt_put_master_key_activeref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
void fscrypt_put_master_key_activeref(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_put_master_key_activeref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584526106,
      "name": "fscrypt_put_master_key_activeref",
      "external": true,
      "loc": "fs/crypto/keyring.c:82",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keysetup.c:put_crypt_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597485767,
      "name": "fscrypt_put_master_key_activeref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584526000,
      "name": "fscrypt_put_master_key_activeref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
void fscrypt_put_master_key_activeref(struct super_block * sb, struct fscrypt_master_key * mk)
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
