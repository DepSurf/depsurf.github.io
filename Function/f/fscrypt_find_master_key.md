# Function: <code>fscrypt_find_master_key</code>

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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303536,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303536,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590048,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:231",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590048,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660576,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:235",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660576,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689824,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:235",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689824,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015600,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:235",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015600,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487056,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:235",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487056,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct fscrypt_master_key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082896,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:274",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082896,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct fscrypt_master_key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584309728,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:277",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309728,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct fscrypt_master_key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526848,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:284",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526848,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493880248,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493880248,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227361376,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227361376,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287514352,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287514352,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273442682,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273442682,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272272,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272272,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210032,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210032,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262752,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262752,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "fscrypt_find_master_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341344,
      "name": "fscrypt_find_master_key",
      "external": true,
      "loc": "fs/crypto/keyring.c:227",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341344,
      "name": "fscrypt_find_master_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct key * fscrypt_find_master_key(struct super_block * sb, const struct fscrypt_key_specifier * mk_spec)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct key *</code> ➡️ <code>struct fscrypt_master_key *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
