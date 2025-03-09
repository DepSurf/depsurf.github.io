# Function: <code>find_or_insert_direct_key</code>

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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311040,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311040,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597968,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597968,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668816,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668816,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697584,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697584,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023584,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
    },
    {
      "addr": 18446744071592241008,
      "name": "find_or_insert_direct_key.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495776,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071594019787,
      "name": "find_or_insert_direct_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:180",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091632,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596058364,
      "name": "find_or_insert_direct_key.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:180",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318592,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596582154,
      "name": "find_or_insert_direct_key.cold",
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_inode_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:180",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536016,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071597486216,
      "name": "find_or_insert_direct_key.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493889376,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493889376,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227369512,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227369512,
      "name": "find_or_insert_direct_key",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287524832,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287524832,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273449414,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273449414,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279776,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279776,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217536,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217536,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270256,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270256,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "find_or_insert_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348816,
      "name": "find_or_insert_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:179",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348816,
      "name": "find_or_insert_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
struct fscrypt_direct_key * find_or_insert_direct_key(struct fscrypt_direct_key * to_insert, const u8 * raw_key, const struct fscrypt_info * ci)
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
<code>const struct fscrypt_info * ci</code> ➡️ <code>const struct fscrypt_inode_info * ci</code>
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
