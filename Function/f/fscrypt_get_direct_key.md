# Function: <code>fscrypt_get_direct_key</code>

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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582311910,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598320,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598320,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669216,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:220",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669216,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697984,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:220",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697984,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023984,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:220",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023984,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:220",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496176,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071594019822,
      "name": "fscrypt_get_direct_key.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092064,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:221",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092064,
      "name": "fscrypt_get_direct_key",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319024,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:221",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319024,
      "name": "fscrypt_get_direct_key",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_inode_info * ci, const u8 * raw_key)
```

```json
{
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536448,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:222",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536448,
      "name": "fscrypt_get_direct_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493889952,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227370092,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287526324,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273450088,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582280646,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582218406,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271126,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
  "name": "fscrypt_get_direct_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582349686,
      "name": "fscrypt_get_direct_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:218",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
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
struct fscrypt_direct_key * fscrypt_get_direct_key(const struct fscrypt_info * ci, const u8 * raw_key)
```
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
