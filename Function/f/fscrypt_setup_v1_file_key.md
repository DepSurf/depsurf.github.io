# Function: <code>fscrypt_setup_v1_file_key</code>

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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312554,
      "name": "fscrypt_setup_v1_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582311840,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582598870,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:292",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598688,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582669738,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:290",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669552,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698320,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:290",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698320,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583024320,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:290",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024320,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583496560,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:290",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496560,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092512,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:292",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092512,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319472,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:292",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319472,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int fscrypt_setup_v1_file_key(struct fscrypt_inode_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536944,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:293",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536944,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493889872,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493889872,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227369984,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227369984,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287526224,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287526224,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273450010,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273450010,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281290,
      "name": "fscrypt_setup_v1_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582280576,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219050,
      "name": "fscrypt_setup_v1_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582218336,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271770,
      "name": "fscrypt_setup_v1_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582271056,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
```

```json
{
  "name": "fscrypt_setup_v1_file_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_setup_v1_file_key",
      "external": true,
      "loc": "fs/crypto/keysetup_v1.c:311",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350330,
      "name": "fscrypt_setup_v1_file_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582349616,
      "name": "fscrypt_setup_v1_file_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int fscrypt_setup_v1_file_key(struct fscrypt_info * ci, const u8 * raw_master_key)
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
