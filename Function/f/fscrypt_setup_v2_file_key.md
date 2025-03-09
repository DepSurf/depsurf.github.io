# Function: <code>fscrypt_setup_v2_file_key</code>

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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446744071582308864,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582310493,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:238",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594880,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071582596967,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:279",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665904,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071591341906,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:303",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694688,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071591284651,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:308",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020544,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071592240699,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:309",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583492544,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071594019506,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:332",
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
      "addr": 18446744071584088320,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071596058304,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:332",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315088,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071596582094,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int fscrypt_setup_v2_file_key(struct fscrypt_inode_info * ci, struct fscrypt_master_key * mk, bool need_dirhash_key)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:333",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532384,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071597486127,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493886672,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446603336493886672,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227367408,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 3227367408,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287522144,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 13835058055287522144,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273447666,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446743936273447666,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446744071582277600,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582279229,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446744071582215360,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582216989,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446744071582268080,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582269709,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "fscrypt_setup_v2_file_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v2_file_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:248",
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
      "addr": 18446744071582346640,
      "name": "fscrypt_setup_v2_file_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582348267,
      "name": "fscrypt_setup_v2_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int fscrypt_setup_v2_file_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool need_dirhash_key</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
