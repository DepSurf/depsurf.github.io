# Function: <code>do_remove_key</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305296,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071582307408,
      "name": "do_remove_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582592112,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:901",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592112,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582662624,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:911",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662624,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
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
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582691872,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:911",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691872,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583017648,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:911",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017648,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583489568,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:951",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489568,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584085024,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:1008",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085024,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584311600,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:1003",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311600,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:1017",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528832,
      "name": "do_remove_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
    },
    {
      "addr": 18446744071597485849,
      "name": "do_remove_key.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493881904,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493881904,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1652
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
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227363344,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227363344,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1348
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
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287516560,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287516560,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1980
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
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273444230,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273444230,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1310
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274032,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071582276144,
      "name": "do_remove_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211792,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071582213904,
      "name": "do_remove_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264512,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071582266624,
      "name": "do_remove_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```

```json
{
  "name": "do_remove_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_remove_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:757",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users",
        "fs/crypto/keyring.c:fscrypt_ioctl_remove_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343104,
      "name": "do_remove_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1287
    },
    {
      "addr": 18446744071582345184,
      "name": "do_remove_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int do_remove_key(struct file * filp, void * _uarg, bool all_users)
```
</details>
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
