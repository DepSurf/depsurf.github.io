# Function: <code>search_fscrypt_keyring</code>

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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302640,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302640,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582588496,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:135",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582659053,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:135",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582688301,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:135",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583014013,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:135",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583485838,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:135",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493878568,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493878568,
      "name": "search_fscrypt_keyring",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227360656,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227360656,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287513264,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287513264,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273442190,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273442190,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271376,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271376,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209136,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209136,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261856,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261856,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "search_fscrypt_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340448,
      "name": "search_fscrypt_keyring",
      "external": false,
      "loc": "fs/crypto/keyring.c:131",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340448,
      "name": "search_fscrypt_keyring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct key * search_fscrypt_keyring(struct key * keyring, struct key_type * type, const char * description)
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
