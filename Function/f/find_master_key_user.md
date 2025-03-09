# Function: <code>find_master_key_user</code>

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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302704,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302704,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588416,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:268",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588416,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582658976,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:277",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582658976,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688224,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:277",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688224,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013936,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:277",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013936,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583485744,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:277",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485744,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584081104,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:345",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081104,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307984,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:348",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307984,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584525024,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:355",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525024,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493878688,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493878688,
      "name": "find_master_key_user",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227360720,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227360720,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287513376,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287513376,
      "name": "find_master_key_user",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273442280,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273442280,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271440,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271440,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209200,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209200,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261920,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261920,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
```

```json
{
  "name": "find_master_key_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340512,
      "name": "find_master_key_user",
      "external": false,
      "loc": "fs/crypto/keyring.c:264",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_verify_key_added",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340512,
      "name": "find_master_key_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct key * find_master_key_user(struct fscrypt_master_key * mk)
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
