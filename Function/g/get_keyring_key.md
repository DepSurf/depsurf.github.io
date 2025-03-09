# Function: <code>get_keyring_key</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582591401,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:569",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582661913,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:574",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
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
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582691161,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:574",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
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
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583016937,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:574",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
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
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583488592,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:574",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret * secret)
```

```json
{
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584080384,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:630",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080384,
      "name": "get_keyring_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret * secret)
```

```json
{
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:633",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307168,
      "name": "get_keyring_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071596581856,
      "name": "get_keyring_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret * secret)
```

```json
{
  "name": "get_keyring_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_keyring_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:648",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524208,
      "name": "get_keyring_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071597485738,
      "name": "get_keyring_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret * secret)
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
