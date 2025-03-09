# Function: <code>add_master_key</code>

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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303648,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446744071582303648,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590928,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:470",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590928,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661440,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:475",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661440,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582690688,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:475",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690688,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016464,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:475",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016464,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488064,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:475",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488064,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083184,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:531",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083184,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310016,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:534",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310016,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, struct fscrypt_key_specifier * key_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:549",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527136,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071597485808,
      "name": "add_master_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493880384,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446603336493880384,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227361500,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 3227361500,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287514512,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 13835058055287514512,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273442764,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446743936273442764,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272384,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446744071582272384,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210144,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446744071582210144,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262864,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446744071582262864,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```

```json
{
  "name": "add_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341456,
      "name": "add_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:425",
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
      "addr": 18446744071582341456,
      "name": "add_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int add_master_key(struct super_block * sb, struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_key_specifier * key_spec</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fscrypt_key_specifier * mk_spec</code>
</li>
</ul>
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
