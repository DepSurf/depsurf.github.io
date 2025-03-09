# Function: <code>try_to_lock_encrypted_files</code>

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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305561,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582592378,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:840",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582662899,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:850",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:850",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689232,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071591284358,
      "name": "try_to_lock_encrypted_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:850",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015008,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071592240213,
      "name": "try_to_lock_encrypted_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:890",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484960,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071594019012,
      "name": "try_to_lock_encrypted_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079648,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:947",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079648,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584306448,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:942",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584306448,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523488,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:957",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523488,
      "name": "try_to_lock_encrypted_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493882152,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227363640,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287516856,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273444432,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582274297,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582212057,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582264777,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
  "name": "try_to_lock_encrypted_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582343366,
      "name": "try_to_lock_encrypted_files",
      "external": false,
      "loc": "fs/crypto/keyring.c:696",
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int try_to_lock_encrypted_files(struct super_block * sb, struct fscrypt_master_key * mk)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
