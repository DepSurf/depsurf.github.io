# Function: <code>setup_file_encryption_key</code>

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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309622,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, struct key * * master_key_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:305",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595248,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071582596979,
      "name": "setup_file_encryption_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct key * * master_key_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:346",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666288,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071591341918,
      "name": "setup_file_encryption_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct key * * master_key_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:370",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695200,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071591284663,
      "name": "setup_file_encryption_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct key * * master_key_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:414",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021072,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071592240753,
      "name": "setup_file_encryption_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct key * * master_key_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:415",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493120,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071594019546,
      "name": "setup_file_encryption_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584089256,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:437",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct fscrypt_master_key * * mk_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315680,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:437",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315680,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int setup_file_encryption_key(struct fscrypt_inode_info * ci, bool need_dirhash_key, struct fscrypt_master_key * * mk_ret)
```

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:439",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532976,
      "name": "setup_file_encryption_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071597486167,
      "name": "setup_file_encryption_key.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493887544,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227368280,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287523296,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273448312,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582278358,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582216118,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268838,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
  "name": "setup_file_encryption_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582347398,
      "name": "setup_file_encryption_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:294",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info"
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
int setup_file_encryption_key(struct fscrypt_info * ci, struct key * * master_key_ret)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool need_dirhash_key</code>
</li>
<li>
<b>Param reordered. </b>
<code>ci, master_key_ret</code> ➡️ <code>ci, need_dirhash_key, master_key_ret</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct key * * master_key_ret)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int setup_file_encryption_key(struct fscrypt_info * ci, bool need_dirhash_key, struct fscrypt_master_key * * mk_ret)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_info * ci</code> ➡️ <code>struct fscrypt_inode_info * ci</code>
</li>
</ul>
</details>
</li>
</ul>
